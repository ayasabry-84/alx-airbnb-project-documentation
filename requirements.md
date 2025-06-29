# Backend Feature Specifications – Airbnb Clone

This document outlines the technical and functional requirements for selected backend features.

---

## 1. User Authentication

### 🧩 Description
Handles user registration and login using secure authentication mechanisms (JWT).

### 🔌 Endpoints

#### POST /api/auth/register
- **Input**:  
```json
{
  "first_name": "Aya",
  "last_name": "Sabry",
  "email": "aya@example.com",
  "password": "StrongP@ss123",
  "role": "guest"
}
