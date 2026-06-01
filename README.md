# API Access Management System with Token Validation and Policy Enforcement

**Company:** Bhoomi Techzone Pvt. Ltd.  
**Developer:** Aman Kumar

---

## Project Objective
To design a secure API access management system that secures backend services using token validation (JWT) and policy enforcement (RBAC). The system ensures only authorized clients can access APIs while preventing abuse and unauthorized usage.

---

## Tech Stack
- **Backend:** Java 17+, Spring Boot 3
- **Security:** Spring Security, JWT (JSON Web Tokens)
- **Database:** MySQL, Spring Data JPA, Hibernate
- **Testing:** JUnit 5, Mockito
- **Tools:** IntelliJ IDEA, Postman, Maven, Git

---

## Architecture Flow
1. **Client:** Sends HTTP request with/without JWT token
2. **Security Filter (The Bouncer):** JwtAuthFilter intercepts the request, validates the token, and checks roles/policies
3. **Controller (The Waiter):** Receives the validated request and delegates to the Service layer
4. **Service (The Chef):** Executes core business logic and policy enforcement
5. **Repository (The Pantry):** Communicates with MySQL via JPA for data persistence

---

## Current Progress

### Milestone 1: Setup & Architecture Design ✅
- Spring Boot project initialized with required dependencies
- Layered package architecture created (controller, service, repository, model, security, dto, exception)
- Base Entity models (User, Role) configured with Many-to-Many relationship for RBAC
- MySQL database connected and tables auto-generated via Hibernate

### Milestone 2: Core API Development 🚧
### Milestone 3: Token Validation & Authentication 📝
### Milestone 4: Policy Enforcement & Access Control 📝
### Milestone 5: Rate Limiting & Logging 📝
### Milestone 6: Testing, Performance & Documentation 📝

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone <https://github.com/Kumar-Aman7974/API-Access-Management-System.git>