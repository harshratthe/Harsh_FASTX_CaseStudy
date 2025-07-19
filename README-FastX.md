
# 🚌 FastX - Full Stack Bus Ticket Booking System

**FastX** is a full-stack web application for online bus ticket booking. It includes:
- A **React.js frontend** for users, bus operators, and admins.
- A **Spring Boot backend** to manage business logic, security, data, and APIs.

The project supports functionalities like route search, seat booking, payment handling, admin management, operator dashboards, and secure JWT authentication.

---

## 🚀 Setup Instructions

### 🔧 Backend (Spring Boot)

#### Prerequisites
- Java 17
- Maven
- MySQL or H2 Database
- IDE (IntelliJ / Eclipse)



1. Configure DB in `src/main/resources/application.properties`
2. Run with:
```bash
mvn spring-boot:run
```

---

### 🌐 Frontend (React)

#### Prerequisites
- Node.js v14+
- npm or yarn

#### Steps
```bash
cd FastX-frontend
npm install
npm start
```
Visit: `http://localhost:3000`

---

## 🧰 Tech Stack

### Frontend
- React JS
- Semantic UI React
- Axios
- React Router DOM
- CSS Modules
- JWT Auth Integration

### Backend
- Java 17
- Spring Boot
- Spring MVC, Spring Data JPA
- Spring Security + JWT
- Hibernate
- MySQL / H2
- ModelMapper
- JUnit & Mockito

---

## 🧪 Test Coverage

### ✅ Frontend (Manual)
- JWT login & role protection
- Booking flow (search → book → pay)
- Admin/Operator dashboard actions
- Mobile responsiveness

> 📝 Jest / React Testing Library can be integrated

### ✅ Backend (Automated)
Path: `src/test/java/com.hexaware.fastx.test`
- Amenity, Booking, Auth, User tests
- Route/Seat/Bus logic
- Exception handling
- Tools: `JUnit 5`, `Mockito`

---

## 📁 Folder Structures

### Frontend
```
FastX-frontend/
├── public/
├── src/
│   ├── components/
│   │   ├── admin/
│   │   ├── auth/
│   │   ├── busOperator/
│   │   ├── common/
│   │   └── user/
│   ├── App.js
│   └── App.css
```

### Backend
```
fastx-backend/
└── src/
    ├── main/java/com.hexaware.fastx/
    │   └── demo/
    │   ├── controller/
    │   ├── dto/
    │   ├── entity/
    │   ├── exceptions/
    │   ├── mappers/
    │   ├── repositories/
    │   ├── security/
    │   ├── service/
    │   ├── serviceImplementation/
    │   ├─   config/
    │   ├── filter/
    │   ├─ util/
        
    ├── resources/
    │   └── application.properties
    └── test/java/com.hexaware.fastx.test/
```     

---

## 🔐 Authentication & Security

- JWT token-based auth
- Role-based access (Admin, Operator, User)
- Secured endpoints using Spring Security filters
- AuthController generates and verifies tokens

---

## ✨ Features

### Admin
- Manage Users,  Routes

### Operator
- Add/Update Buses & Routes
- View Bookings

### User
- Search Buses, Select Seats
- Enter Passenger Info
- Make Payments
- View/Download Tickets

### UI
- CSS/Tailwind
- Component-driven design
- Navigation via React Router

---

## 📌 Future Enhancements

- Swagger API docs
- Email notifications
- Admin dashboard analytics
- OTP-based login
- Jest test integration
- Google Maps for routes

---

## 🔗 Repository Structure

```
root/
├── FastX-frontend/
├── fastx-backend/
└── README.md (this file)
```


