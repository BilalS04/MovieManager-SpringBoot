# Movie Manager - CRUD Application (Spring Boot + PostgreSQL + JSP)

This is a full-stack Java web application that allows users to manage a collection of movies. It implements full CRUD functionality (Create, Read, Update, Delete) using Spring Boot and PostgreSQL, with a JSP-based front-end.

---

## ✨ Features

- ✅ Add new movies with title and release year
- 📝 Edit existing movies
- 🗑️ Delete movies
- 📄 View list of all movies

---

## 💻 Technologies Used

- Java 17+
- Spring Boot
- Spring MVC
- Spring Data JPA
- PostgreSQL
- JSP / JSTL
- HTML/CSS
- Bootstrap
- IntelliJ IDEA
- Maven

---

Configure your database credentials by creating a local file:

📁 src/main/resources/application.properties
properties
Kopier
Rediger
spring.mvc.view.prefix=/WEB-INF/jsp/
spring.mvc.view.suffix=.jsp

spring.datasource.url=jdbc:postgresql://localhost:5432/moviedb
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

---

▶️ Run the App

./mvnw spring-boot:run

Then visit: http://localhost:8080/movies

---

🧠 What I Learned

Creating full CRUD functionality using Spring Boot and JSP

Integrating PostgreSQL with Spring Data JPA

Using MVC architecture in a real-world project

Building dynamic server-side web pages with JSP

---
