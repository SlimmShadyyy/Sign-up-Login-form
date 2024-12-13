# Sign-up-Login-form
# Signup/Login Form using Node.js  

## Description  
This is a basic user signup and login form implemented using **Node.js**. The application validates user input (name, last name, email, password, and phone number) and provides endpoints for user registration and authentication.  

---

## Features  
- **Signup API**: Validates user input and registers users.  
- **Login API**: Authenticates users based on email and password.  
- **Get Users API**: Retrieves all registered users.  

---

## APIs  

### 1. Signup  
- **Endpoint**: `POST /signup`  
- **Request Body**:  
  ```json
  {
    "name": "John",
    "lastname": "Doe",
    "email": "john.doe@example.com",
    "password": "John@1234",
    "phone_no": "1234567890"
  }
