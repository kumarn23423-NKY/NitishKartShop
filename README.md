# NitishKart

Full-stack e-commerce web application.

## Project structure
- `backend/`  - Spring Boot 3 REST API (Java 17, Spring Security + JWT, Spring Data JPA, MySQL)
- `frontend/` - React 18 + Vite web app

## Features
- Register / login with JWT and role-based access (Admin and Customer)
- Product search, category filter and pagination
- Cart, checkout, order placement and cancellation with stock update
- Admin dashboard for products and order status

## Run locally

### Backend
1. Install JDK 17+, Maven and MySQL 8
2. Set environment variables: `DB_USER`, `DB_PASSWORD`
3. `cd backend` then `mvn spring-boot:run`
4. API runs on http://localhost:8080 (Swagger: /swagger-ui.html)
5. Default admin: admin@shop.com / admin123

### Frontend
1. Install Node.js 18+
2. `cd frontend`
3. `npm install` then `npm run dev`
4. Open http://localhost:5173
