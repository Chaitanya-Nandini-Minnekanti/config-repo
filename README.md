# config-repo
spring.application.name=Service-Registery
server.port=8761

eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false

microservice:
server.port=8081
spring.application.name=ORDER-SERVICE

spring.datasource.url=jdbc:mysql://localhost:3306/orderdb
spring.datasource.username=root
spring.datasource.password=N@ndini123
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update

eureka.client.service-url.defaultZone=http://localhost:8761/eureka/
eureka.instance.hostname=localhost
eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true

server.port=8080
spring.application.name=PRODUCT-SERVICE
spring.data.mongodb.uri=mongodb://localhost:27017/productdb

eureka.client.service-url.defaultZone=http://localhost:8761/eureka/
eureka.instance.hostname=localhost
eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true

