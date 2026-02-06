# Cinema Management System

**Live Demo:** https://cinema-euqq.onrender.com  

A **Dockerized ASP.NET Core MVC web application** for cinema management, featuring
role based authentication, database-backed operations, and cloud deployment.

This project demonstrates the **full lifecycle of a web application**:
development - containerization - deployment.

---

##  Overview

The Cinema Management System is a full stack web application designed to manage
cinema operations such as movies, screenings, and user interactions.

It is built using **ASP.NET Core MVC**, follows the **MVC architectural pattern**,
and is deployed as a **containerized application** using Docker.

---

## Architecture

- **Frontend:** Razor Views, HTML, CSS, Bootstrap
- **Backend:** ASP.NET Core MVC (C#)
- **Database:** SQLite (via Entity Framework Core)
- **Authentication:** Role based user authentication
- **Deployment:** Docker + Render Cloud Platform

The project is structured to clearly separate concerns:
- Controllers handle application logic
- Models define data structures
- Views manage presentation

---

## User Roles & Features

### Authentication
- User registration and login
- Session-based authentication
- Role based authorization

### Roles
- **Admin**
  - Manage users
  - Manage movies and screenings
- **Content Admin**
  - Add and manage movies
  - Schedule screenings
- **Customer**
  - Browse movies
  - View available screenings

---

## Docker & Deployment

The application is fully containerized using **Docker**, ensuring consistent
behavior across development and production environments.

### Why Docker?
- Eliminates environment-specific issues
- Ensures reproducible builds
- Simplifies cloud deployment

### Deployment Platform
- **Render** is used to host the Docker container
- The application runs in a production environment accessible via public URL

Live deployment:  
https://cinema-euqq.onrender.com

---

## Project Structure

---

## Technologies Used

- ASP.NET Core MVC
- C#
- Entity Framework Core
- SQLite
- Docker
- Render (Cloud Deployment)
- Bootstrap

---

## What This Project Demonstrates

- MVC based web application design
- Role based access control
- Database integration with EF Core
- Docker based containerization
- Cloud deployment of a production ready app

---

## Notes

This project was developed iteratively and improved over time,
reflecting real-world software development practices.


