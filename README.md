# E-Commerce App

## 🔎 About the project

E-CommerceApp is a REST API for an e-commerce store aimed at the PC-Gaming market, based on microservices architecture, it has both operations carried out for the customer and operations carried out by employees and administrators.


## 🖥️ Functionalities


- ✅ Users CRUD divided between `account-ms` and `users-ms`

- ✅ Authentication and authorization also divided between `account-ms` and `users-ms`

- ✅ Orders CRUD

- ✅ Products CRUD

- ✅ Highly parameterized search for products

- ✅ Payment persistence based on messaging

- ✅ Updates from related entities in different services through messaging

## 🛠️ Tecnologies

- [TestContainers](https://testcontainers.com/)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Modelmapper](https://modelmapper.org/)
- [Lombok](https://projectlombok.org/)
- [JWT](https://github.com/auth0/java-jwt)
- [MySQL](https://dev.mysql.com/downloads/connector/j/)
- [Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-netflix/reference/html/)
- [Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway)
- [Spring Cloud OpenFeign](https://spring.io/projects/spring-cloud-openfeign)
- [Spring Security Crypto](https://docs.spring.io/spring-security/reference/features/integrations/cryptography.html)
- [SpringBoot Starter JPA](https://spring.io/projects/spring-data-jpa)
- [SpringBoot Starter Web]()
- [SpringBoot Starter Validation](https://docs.spring.io/spring-framework/reference/core/validation/beanvalidation.html)

## ⚙️ System overview
![application-schema](readme/application.svg)


## 📦 Endpoints 


[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://app.getpostman.com/run-collection/31232249-f8298dc1-e513-4900-9548-385b6d19c3e7?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D31232249-f8298dc1-e513-4900-9548-385b6d19c3e7%26entityType%3Dcollection%26workspaceId%3Daae15406-ac2a-4087-8c9e-47072e8aa119)

- **To log in as an ADMIN use username `root` and password `root@123` or create the environment variables `ADMIN_USERNAME` and `ADMIN_PASSWORD`.**

# 🤝 Credits

- Special thanks to [@AlexandreMadeira](https://github.com/MadeiraAlexandre) for helping me with several suggestions, such as creating the concept of system services, and with the relationships of some entities.
