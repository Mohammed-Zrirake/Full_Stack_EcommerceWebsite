# 🛒 Full Stack E-commerce Website

A full-featured e-commerce web application built with modern technologies, offering secure user authentication, real-time shopping cart, product filtering, payment processing, and an admin dashboard.

---

## 🔧 Tech Stack

### Frontend

* React.js ^18.3.1
* React DOM
* React Router DOM ^7.0.1 (for routing)
* Axios ^1.7.7 (for API communication)
* Redux Toolkit ^2.3.0 (state management)
* React Redux
* React Hook Form ^7.54.0 (form management)
* Material UI (^6.1.8 via @mui/material)
* Emotion (CSS-in-JS via @emotion/react & @emotion/styled)
* Headless UI (via @headlessui/react)
* Stripe integration (@stripe/react-stripe-js & @stripe/stripe-js)
* React Hot Toast (notifications)
* React Icons (icons)
* React Loader Spinner (loading spinners)
* Swiper (carousel/slider)

### Backend
Developed with Java and Spring Boot following a modular layered architecture. Includes RESTful APIs, JWT-based security, and database interaction.

- **controller/** – Handles HTTP routes
- **service/** – Core business logic
- **model/** – JPA entity classes
- **repositories/** – JPA repositories for DB access
- **payload/** – DTOs for API communication
- **config/** – Security and CORS configuration
- **exceptions/** – Custom and global error handlers
- **resources/** – App config, static files
- **EcommerceApplication.java** – Main application entry point

* Java with Spring Boot
* Spring Security (JWT-based Authentication & Authorization)
* Hibernate/JPA
* MySQL/PostgreSQL (Relational Database)
* Maven (Build and Dependency Management)

### Tools & Other

* Git & GitHub
* Postman (API testing)
* IntelliJ IDEA / Eclipse for Backend
* VS Code for Frontend

---

## ✨ Features

* 🌐 User-friendly product browsing and filtering
* 🔐 Secure user registration and login (JWT Auth)
* 🛒 Shopping cart management
* 💳 Mock/real payment integration (Stripe)
* 📆 Order history and user dashboard
* 💼 Admin dashboard for inventory and order management
* 🌍 RESTful API integration between frontend and backend

---

## 🏗️ Frontend Architecture (Overview)

The frontend follows a modular React architecture:

* Routing handled by `react-router-dom`
* Global state managed with Redux Toolkit
* Forms managed using React Hook Form
* UI designed with Material-UI and Emotion
* Payments handled via Stripe API
* Axios used for all HTTP/API interactions
* Custom UI components (carousels, spinners, icons, etc.) integrated for enhanced UX

---

## 📁 Project Structure

```
├── Backend
│   └── E-commerce
│       ├── .idea
│       │   ├── .gitignore
│       │   ├── compiler.xml
│       │   ├── E-commerce.iml
│       │   ├── encodings.xml
│       │   ├── jarRepositories.xml
│       │   ├── misc.xml
│       │   └── workspace.xml
│       ├── .mvn
│       │   └── wrapper
│       │       └── maven-wrapper.properties
│       ├── src
│       │   ├── main
│       │   │   ├── java
│       │   │   │   └── com
│       │   │   │       └── ecommerce
│       │   │   │           └── project
│       │   │   │               ├── config
│       │   │   │               ├── controller
│       │   │   │               ├── exceptions
│       │   │   │               ├── model
│       │   │   │               ├── payload
│       │   │   │               ├── repositories
│       │   │   │               └── EcommerceApplication.java
│       │   │   └── resources
│       │   │       ├── application.properties
│       │   │       └── static
│       │   └── test
│       ├── pom.xml
│       └── target
│
├── Frontend
│   └── ecom-frontend
│       ├── public
│       ├── src
│       │   ├── assets
│       │   ├── components
│       │   ├── pages
│       │   ├── redux
│       │   ├── routes
│       │   ├── App.js
│       │   └── index.js
│       ├── .env
│       ├── package.json
│       └── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* Java 17+
* Node.js and npm
* MySQL/PostgreSQL

### Backend Setup

```bash
cd Full_Stack_EcommerceWebsite/Backend/E-commerce
# Configure DB credentials in src/main/resources/application.properties
mvn clean install
mvn spring-boot:run
```

### Frontend Setup

```bash
cd Full_Stack_EcommerceWebsite/Frontend/ecom-frontend
npm install
npm start
```

---

## 🌐 Author

* [Mohammed Zrirake](https://github.com/Mohammed Zrirake)
* \[https://www.linkedin.com/in/mohammed-zrirake]

> Contributions, issues, and feature requests are welcome!
