# Microbase

I'm creating this node.js service to be the base or the core service in the microservices artitecture. It's going to handle both the authentication and the autherization of the services. what I have in mind is that you run it, and use it. nice and simple. the API should consist of:
login of users  
sign up of users
registering new services    
treating services(apps) like users in which they should have roles and permissions.    
    
     &nbsp;
     
[To the user, the process of logging in to the frontend always appears to be the same. Username or e-mail, password, press enter, done. In the backend, things look a little different. With a monolithic backend environment the authorization system is implicit, and user verification is no problem. The application can handle user tracking here. ..... but in microservice environments things get a little more difficult. Here the microservices either have to rely on the user being authorized or ask the authorization service with every call whether the user is actually allowed to access the service.](http://blog.leanix.net/en/authorization-authentication-with-microservices?hs_amp=true)

