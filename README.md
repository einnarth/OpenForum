Open Forum

Open Forum is a full-stack web application that allows users to share programming problems, discuss solutions and collaborate with other students.

The project was developed as part of the Open Lab mentoring program in collaboration with Siemens Healthineers.

Features

User registration and authentication

Email verification

Password reset functionality

Creating and managing posts

Commenting on posts

Like system for comments

Sorting comments by popularity

User profile management

Technologies
Backend

C#

ASP.NET Core

ASP.NET Identity

Entity Framework Core

MSSQL

JWT Authentication

Frontend

Angular

TypeScript

HTML

CSS

Other Tools

Firebase (notifications / services)

Git & GitHub

SMTP email service

Architecture

The application follows a client-server architecture:

Frontend (Angular) communicates with the backend via REST API.

Components:

Frontend – Angular SPA

Backend – ASP.NET Core Web API

Database – MSSQL

Authentication – ASP.NET Identity + JWT
