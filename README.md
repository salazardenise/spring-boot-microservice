# Spring-Boot-Microservice

This is a Microservice lab from General Assembly's Software Engineering Career Accelerator that is a Spotify clone. A
Service Registry, created with Netflix Eureka, keeps track of requests and matches that with the the corresponding
server which it sends back to an API Gateway. An API Gateway is created with Netflix Zuul. Its purpose is to ask the
service registry for service that services endpoints from clients. It also gives back list of service to client,
and implements load balancing. There are two APIs: Users and Songs. Each is a standard Spring Boot MVC app and they each
have the ability to register with the service regsitry on start-up. 

Note: Supplied .gitignore files within each microservice do not ignore cache. I added all cache directories to the top
level .gitignore.
