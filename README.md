# SpringBootSecurity
Learning Spring Boot Security
## 09
These two maven dependencies added in the POM
* spring-boot-starter-security
* thymeleaf-extras-springsecurity5
## 10
Spring Security Automatic log in 
## 11
HTTP Basic Authentication Configuration
https://www.youtube.com/watch?v=tYpS8BmrEyo&list=PLVApX3evDwJ1d0lKKHssPQvzv2Ao3e__Q&index=12

## 12
Configure Role based Authorization
## 13
Secure Rest Controllers
## 14
Configure Permission based authorization.
Permission based increases granurality for the complex application where role based authorization is not enough
## 15
Enable SSL/HTTPS in Spring boot
Creattin certificate: In this directory with administrative access: C:\Program Files\Java\jdk1.8.0_211\bin:
keytool -genkey -alias springbootsecurity -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore springbootsecurity.p12 -validity 3650

## 16
Database Authentication overview
## 17
Database Authentication - user Entity
## 18
Database Authentication - Create User Repository