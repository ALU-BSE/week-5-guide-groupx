# GroupX breakout group
## Team Members
- Nmesoma Peter - Nmesoma-solomon-peter
- Christelle Usanase - usanas7
- Agape Ineza - Ineza-Agape

## What We Built
Setup & Configuration
Serializers & Initial Setup
Registration Endpoint
Login Endpoint
Protected Profile Endpoint
URL Configuration & Documentation
Run the Swagger UI


## API Endpoints

### Public Endpoints
- `POST /api/users/register/` - User registration
- `POST /api/users/login/` - User login
- `POST /api/users/token/refresh/` - Refresh access token

### Protected Endpoints (Requires Authentication)
- `GET /api/users/profile/` - Get user profile
- `PUT /api/users/profile/` - Update user profile

### Documentation
- Swagger UI: http://127.0.0.1:8000/api/docs/