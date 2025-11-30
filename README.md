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
- Clean layered architecture (`Controller → Service → Repository`)
- JPA & Hibernate for ORM and database interaction
- Uses annotations like `@RestController`, `@Entity`, `@OneToMany`, etc.
