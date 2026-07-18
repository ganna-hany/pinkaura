# Pink Aura

A full-stack e-commerce platform for cosmetics and skincare products built with Java, Spring Boot, MySQL, and Thymeleaf. The application provides customers with a seamless shopping experience while offering administrators a comprehensive dashboard for managing products, users, and orders.

---

## Overview

Pink Aura is designed following modern backend development practices using the MVC architecture. It integrates a responsive user interface with a robust backend and relational database to deliver a complete e-commerce solution.

---

## Features

### Customer

- Browse products by category
- Register and log in securely
- Add and manage items in the shopping cart
- Persistent shopping cart across user sessions

### Administrator

- Manage products (Create, Read, Update, Delete)
- Manage customer orders
- Manage user accounts
- Access protected administrative features

### Authentication

- Secure user authentication
- Session-based authorization
- Protected administrative routes

---

## Tech Stack

### Backend

- Java
- Spring Boot
- Spring Data JPA
- Hibernate

### Frontend

- Thymeleaf
- HTML5
- CSS3
- JavaScript

### Database

- MySQL

### Architecture

- MVC (Model-View-Controller)
- Layered Architecture

### Tools

- Git
- GitHub
- Maven
- Eclipse IDE

---

## Project Structure

```text
src/
├── main/
│   ├── java/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── entities/
│   │   └── config/
│   │
│   └── resources/
│       ├── templates/
│       ├── static/
│       └── application.properties
```

---

## Screenshots

Screenshots will be added soon.

- Home Page
- Product Catalog
- Shopping Cart
- User Authentication
- Admin Dashboard

---

## Technical Highlights

- Developed a full-stack e-commerce application using Spring Boot.
- Applied Object-Oriented Programming principles.
- Implemented MVC and layered architecture.
- Designed and integrated a relational MySQL database.
- Built secure authentication and session management.
- Developed CRUD functionality for products, users, and orders.
- Created dynamic server-rendered pages using Thymeleaf.

---

## Future Improvements

- Product search
- Wishlist
- Product reviews and ratings
- Online payment integration
- Order tracking
- REST API for mobile applications
- Docker support
- Cloud deployment

---

## Getting Started

### Prerequisites

- Java 17+
- Maven
- MySQL

### Installation

```bash
git clone https://github.com/ganna-hany/pink-aura.git
cd pink-aura
```

Configure your MySQL database in `application.properties`, then run:

```bash
mvn spring-boot:run
```

The application will be available at:

```
http://localhost:8080
```

---

## License

This project was developed for educational and portfolio purposes.
