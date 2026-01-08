# 🎬 Netflix Clone – Backend System (Java & Spring Boot)

## 📌 Project Overview 
This project is a **Netflix Clone backend system** designed to simulate a real-world **video streaming platform**.  
The backend is responsible for **user authentication, subscription management, content catalog, streaming metadata, user profiles, watch history, recommendations, and performance optimization**.

The main goal of this project is to demonstrate **enterprise-level backend development** using **Java, Spring Boot, RESTful APIs, and scalable system design**.

---

## 🧠 Core Objectives
- Build a **scalable and secure backend** for a streaming platform
- Apply **clean architecture and SOLID principles**
- Handle **high-volume read operations**
- Implement **authentication & authorization**
- Design **relational database schemas**
- Prepare the system for **future microservices migration**

---

## 🏗️ System Architecture
The system follows a **Layered Architecture**:


Additional components:
- **Spring Security + JWT** for authentication
- **Redis** for caching frequently accessed data
- **AWS S3 / Cloud Storage** for video storage metadata
- **Docker** for containerization

---

## 🧩 Main Features

### 🔐 Authentication & Authorization
- User registration & login
- JWT-based authentication
- Role-based access control:
  - USER
  - ADMIN
- Secure password hashing using BCrypt

---

### 👤 User Profiles
- Multiple profiles per account (similar to Netflix)
- Profile types:
  - Kids profile
  - Adult profile
- Language preferences
- Avatar management

---

### 📺 Content Management
- Movies & TV Shows
- Seasons & Episodes
- Genres & categories
- Content maturity rating (PG, +13, +18)
- Search and filtering capabilities

---

### 🕒 Watch History & Progress Tracking
- Save watch progress per profile
- Resume playback functionality
- Track recently watched content
- Watch time analytics

---

### ⭐ My List & Favorites
- Add/remove content to "My List"
- Personalized content collections
- Fast access using caching

---

### 💳 Subscription & Plans
- Multiple subscription plans:
  - Basic
  - Standard
  - Premium
- Plan limitations:
  - Video quality
  - Number of simultaneous streams
- Subscription status tracking

---

### 🎯 Recommendation Engine (Basic)
- Recommend content based on:
  - Watch history
  - Preferred genres
- Trending and popular content APIs

---

### 🚀 Performance & Optimization
- Pagination and sorting for large datasets
- Redis caching for:
  - Popular movies
  - Genres
- Database indexing
- Lazy loading and query optimization

---

## 🗄️ Database Design (High-Level)
Main entities:
- User
- Profile
- Movie
- TVShow
- Season
- Episode
- Genre
- WatchHistory
- Subscription
- Plan
- MyList

### Relationships
- One User → Many Profiles  
- One TV Show → Many Seasons → Many Episodes  
- Many Profiles → Many Movies (My List)  

---

## 🧪 Testing
- Unit testing with **JUnit 5**
- Service layer testing using **Mockito**
- API testing with **Postman**
- Global exception handling tests

---

## 🔒 Security
- JWT token validation
- Role-based endpoint protection
- Input validation
- Global exception handling
- Protection against common security vulnerabilities

---

## 🛠️ Tech Stack

### Backend
- Java 17+
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
## C1 Digram
<img width="3265" height="589" alt="Image" src="https://github.com/user-attachments/assets/d6f21fe5-fe04-4050-83ec-808c43aefeaf" />

## C2 Digram
<img width="3273" height="1101" alt="Image" src="https://github.com/user-attachments/assets/8bd1e8b3-4ae7-4b00-882c-e6d6e46ca391" />
### Database
- PostgreSQL / MySQL

### Tools & DevOps
- Maven
- Docker
- Git & GitHub
- Postman
- Redis

---

## 📦 Future Enhancements
- Microservices architecture
- Real-time streaming analytics
- Payment gateway integration
- WebSocket notifications
- Admin dashboard

---

## 🎯 What This Project Demonstrates
- Strong Java fundamentals  
- Spring Boot expertise  
- RESTful API design  
- Database modeling  
- Security best practices  
- Scalable backend architecture  

---

⭐ If you like this project, feel free to star the repository!
