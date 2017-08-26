# eureka-discovery-registration-server
A Simple Eureka Registry Server

@EnableEurekaServer - Enables this app as a Eureka Registry Server

POM.xml - add spring-cloud-starter-eureka-server

application.yml 

eureka.instance.hostname: localhost
    
eureka.client.registerWithEureka: false
    
eureka.client.fetchRegistry: false

server.port: 1111


