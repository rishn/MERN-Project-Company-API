# MERN Project - Business Company API (Back-end)

This repository contains the backend of a MERN stack application developed using ExpressJS and MongoDB. It provides the API endpoints and logic necessary for the employee management and notes system.

## Features
- **Authentication & Authorization:** Implements JWT-based authentication and role-based access control.
- **Employee Management:** APIs for managing employees (Admins and Managers can create, update, or delete users).
- **Notes Management:** APIs for creating, viewing, updating, and deleting notes based on the user’s role.
- **Role-Based Access:** Employees, Managers, and Admins have different capabilities (e.g., who can view/edit/delete notes or access user settings).
- **Secure API Endpoints:** Ensures that all endpoints are protected and accessible only to users with the right permissions.

## Use Cases Addressed
1. Replace current sticky note system.
2. Employee login system.
3. Role-based access control (Employees, Managers, Admins).
4. Notes assigned to specific employees.
5. Notes management (OPEN/COMPLETED states, deletion restrictions).
6. Weekly login requirement.
7. Immediate employee access removal.
8. User management (only Managers/Admins can manage users).

## Tech Stack
- **Express.js** for the backend framework.
- **MongoDB** for the database.
- **Mongoose** for MongoDB object modeling.
- **JWT** for authentication.
- **bcrypt** for password hashing.

## Deployed API
The backend of the application is deployed and accessible at:
- [Backend Live URL](https://businesscompany-api.onrender.com)
