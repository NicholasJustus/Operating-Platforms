# Project 4: Game Authentication System

## Project Overview
**Client**: Draw It or Lose It  
**Objective**: Design and implement a secure authentication system for the *Draw It or Lose It* gaming application. The system ensures user account creation, secure login, and access validation.

## Key Requirements
1. **User Login and Registration**: Provide secure account creation and login functionality.  
2. **Session Management**: Implement session handling with token-based or session-based authentication.  
3. **Secure Storage**: Ensure passwords are hashed and stored securely to prevent unauthorized access.  

## Design Constraints
- **Security**: Use secure hashing algorithms (e.g., BCrypt or SHA-256) for password management.  
- **Scalability**: Design the authentication system to support multiple simultaneous user requests.  
- **Integration**: Ensure compatibility with the existing backend and REST API architecture.  

## Reflection
- **Strengths**: Developed a robust and secure authentication mechanism to meet user and system requirements.  
- **Improvements**: Additional logging and error-handling could improve debugging and system monitoring.  
- **Design Insight**: Implementing secure password hashing and session-based validation ensures both system integrity and user trust.  

## Files
- **`AuthService.java`**: Contains core logic for user login and registration.  
- **`User.java`**: User model class with attributes such as username, email, and hashed password.  
- **`Database.java`**: Handles user data storage, retrieval, and validation.  
- **`Utils.java`**: Utility functions for hashing passwords and managing tokens.  
