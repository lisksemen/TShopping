## TShopping project

### This is a simple microservice java project
### Project technologies:
- Spring Boot
- Spring Data JPA (MySQL)
- Spring Data MongoDB
- Spring Cloud (Gateway, Micrometer, Eureka)
- Spring Security (OAuth 2.0 with Keycloak)
- Zipkin (with micrometer to trace requests)

### Project structure
![](img/structure.png)


### Inter Service communication
#### Two approaches were used to communicate between services:
- Synchronous communication (WebClient direct http API calls)
![](img/synchronous.png)
- Asynchronous communication (Kafka message system)
![](img/asynchronous.png)


### Data sources
#### For data storages two databases were used (MySQL and MongoDB)
![](img/databases.png)


### Security
#### This application was secured using OAuth 2.0 with Keycloack server
![](img/security.png)