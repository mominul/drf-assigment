# Assignment

A basic user management backend project using Django Rest Framework (DRF) with JWT authentication.

## Running the project 🏃‍♂️
```
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## API Overview

### Endpoints

#### User Signup
- **POST `/users/signup/`**: Sign up a new user.

#### Users

- **GET `/users/`**: List all users.
- **POST `/users/`**: Create a new user.
- **GET `/users/{id}/`**: Retrieve a specific user by ID.
- **PUT `/users/{id}/`**: Update a user by ID.
- **PATCH `/users/{id}/`**: Partially update a user by ID.
- **DELETE `/users/{id}/`**: Delete a user by ID.

#### Schema
- **GET `/api/schema/`**: Retrieve the OpenAPI schema.

## Swagger UI
Swagger UI or Redoc is available at the path:

```
http://127.0.0.1:8000/api/schema/swagger-ui/
http://127.0.0.1:8000/api/schema/redoc/
```
