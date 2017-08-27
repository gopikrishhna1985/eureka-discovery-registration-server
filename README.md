# eureka-discovery-registration-server
A Simple Eureka Registry Server

@EnableEurekaServer - Enables this app as a Eureka Registry Server

POM.xml - add spring-cloud-starter-eureka-server

application.yml 

eureka.instance.hostname: localhost
    
eureka.client.registerWithEureka: false
    
eureka.client.fetchRegistry: false

server.port: 1111

########################################################

In order to see the full usage of this application you will have to download and run the below projects also,

1. eureka-student-client (microservice)

2. eureka-web-consumer (web application)



