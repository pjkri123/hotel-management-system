# Foodie Website – Online Food Ordering Platform

## 📝 Project Description

Foodie Website is a Java-based project developed using the Spring Boot framework. It provides a RESTful API for managing restaurants, menus, customers, orders and reviews.

The application models real-world relationships between Restaurants, Menu Items, Customers, Orders, and Reviews and supports order lifecycle operations.

---

## 🚀 Features

- REST APIs for Restaurants, Menu Items, Customers, Orders and Reviews
- Entity relationships:
   - One-to-Many: `Restaurant` → `MenuItem`
   - One-to-Many: `Restaurant` → `Review`
   - One-to-Many: `Customer` → `Order`
   - One-to-Many: `Order` → `OrderItem`
- Full CRUD support for Restaurants, Menu Items, Customers, Orders, and Reviews
- Order lifecycle: `PLACED` → `CONFIRMED` → `PREPARING` → `OUT_FOR_DELIVERY` → `DELIVERED`/`CANCELLED`
- Clean layered architecture (`Controller → Service → Repository`)
- JPA & Hibernate for ORM and database interaction
- Uses annotations like `@RestController`, `@Entity`, `@OneToMany`, etc.

---

## 📦 Technologies Used
- Java 17+
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven (or Gradle)
- Relational Database (e.g., MySQL or H2)

---

## 🛠 Tech Stack Used
- IDE:Intellij IDEA
- Framework: Spring Boot
- Database: H2 (In-Memory Database for testing)
- API Testing: Postman
- Build Tool: Maven
- Version Control: Git & GitHub

---


