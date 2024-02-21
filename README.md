### This is a `Ecommerce Store` Project developed with `SpringBoot` and follows the `Microservices` achitecture.

### In this project there is mainly 4 microservices  which are :
* Product Service -> To add or view products , i.e a Product Catalog
* Order Service -> To order a product by checking its stock in the inventory service
* Inventory Service -> To check for the available stock of the product
* Notification Service -> To send an email notification after successfull order


### Other Technical things used in the complete project
* Api Gateway
* Service Registry
* Authorization Server using Keycloak
* Github configuration Server
* Product Service with MongoDB database
* Inventory Service with MySQL database
* Order Service with MySQL database
* Notification Service with Message Queues
* Event Driven Architecture
* Synchronous Communication between Services using RestTemplate / FeignClient 
* Ascynchronous Communication between Services using Kafka / RabbitMQ
* Zipkin
* ElasticSearch
* Centralized Logging using LOG4J / SLF4J
* Netflix Eureka Server with Spring Cloud
* LoadBalancer 
* CircuitBreaker
* and Many More... 


#### API Testing using TestContainers and JUnit5 ans Mockito