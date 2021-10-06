# Keycloak
### Readme
Keycloak is a ID services that adds authentication to applications and secures services. 
## Research

We use keycloak because we choose to use a fully functional login system instead of making our own. This way we have a more secure login system with integrated google login. This way our users will be able to login with google instead of making an separate account. We could also not make our own login system as secure as keycloak already is. This way we also spared time within our project to work on the other services.w

In our application we use keycloak to as a ID service. This way we have a secure login system where users can register and login to use our application. We will use their user accounts to be able to show users what other users are in the lobby at the given moment. 

## Setup
First you setup keycloak as a service. You need to run it either on docker or on a webserver. Our keycloak service that is connected to this application currently runs on Heroku. When you set it up you need to create a realm in the backend of the keycloak service. Our realm is called Lobby. When this is done you need to create a client within the clients tab of the backend. We called this lobbyapplication. When this is done the basic setup of keycloak is finished. If you want to use our Heroku server it doesn’t require a setup to intergrate it into the project. 

