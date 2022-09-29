# Spring-Data-JPA-Paging-Sort-Example-Springboot
In this video, I have discussed how to sort rest api and implement pagination using Spring Data JPA with SpringBoot. I have explained with live working code example.

Instruction
Download and extract the files Java 8 Spring Boot 2.1.1 (with Spring Data JPA) H2 (embedded in Memory database) Maven 3.8.1

Youtube Video with Explanation : https://youtu.be/bbVhdSlt9vQ
– For MySQL:

spring.datasource.url= jdbc:mysql://localhost:3306/testdb?useSSL=false spring.datasource.username= root spring.datasource.password= 123456

spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.MySQL5InnoDBDialect

Hibernate ddl auto (create, create-drop, validate, update)
spring.jpa.hibernate.ddl-auto= update

– For PostgreSQL:

spring.datasource.url= jdbc:postgresql://localhost:5432/testdb spring.datasource.username= postgres spring.datasource.password= 123

spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation= true spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.PostgreSQLDialect

Hibernate ddl auto (create, create-drop, validate, update)
spring.jpa.hibernate.ddl-auto= update
