# Open Forum 

> A full-stack web application for students to share programming problems, discuss solutions, and collaborate.

This project was developed as part of the **Open Lab mentoring program** in collaboration with **Siemens Healthineers**. It serves as a practical implementation of a client-server architecture, modern web frameworks, and secure authentication.

## ✨ Features
- **User System & Security:** Registration and authentication (JWT), email verification, password reset functionality, and profile management.
- **Content Management:** Creating, managing, and browsing discussion posts.
- **Community Interaction:** Commenting on posts, a like system for comments, and dynamic sorting by popularity.

## 🏗️ Architecture
The application follows a standard client-server architecture:
- **Frontend (Angular)** communicates with the backend via REST API.
- **Backend (ASP.NET Core Web API)** handles business logic, security, and database operations.

## 🛠️ Tech Stack

**Backend**
* C# / ASP.NET Core
* ASP.NET Identity + JWT Authentication
* Entity Framework Core
* MSSQL

**Frontend**
* Angular / TypeScript
* HTML5 / CSS3

**Other Tools & Services**
* Firebase (notifications / services)
* SMTP email service
* Google ReCaptcha
* Git & GitHub
