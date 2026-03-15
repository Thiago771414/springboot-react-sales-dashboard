# Sales Performance Analytics Dashboard (Spring Boot + React)

![Frontend](https://img.shields.io/badge/frontend-React-blue)
![Backend](https://img.shields.io/badge/backend-Spring%20Boot-green)
![Language](https://img.shields.io/badge/language-Java-orange)
![Database](https://img.shields.io/badge/database-SQL-lightgrey)
![Architecture](https://img.shields.io/badge/Architecture-Full%20Stack-purple)
![Project Type](https://img.shields.io/badge/Project%20Type-Engineering%20Case%20Study-yellow)

---

# Overview

This project demonstrates the development of a **full stack analytics dashboard** using **Spring Boot (Java) and React**.

The system analyzes **sales performance data** and presents visual insights through interactive charts and tables.

The application is designed using a modern full-stack architecture:

- REST API backend with Spring Boot
- React frontend interface
- dashboard data visualization
- API-driven communication between frontend and backend

---

# Case Study

## Problem

Sales teams often need a clear overview of:

- sales performance
- conversion rates
- total revenue
- sales representative performance

Without proper dashboards, analyzing this information becomes difficult.

---

## Solution

This application provides a **sales analytics dashboard** that aggregates backend data and displays performance metrics using charts and tables.

The system uses a **REST API architecture**, where the React frontend consumes endpoints exposed by the Spring Boot backend.

---

# Application Features

✔ Sales performance dashboard  
✔ Success rate analysis  
✔ Sales representative performance comparison  
✔ Paginated sales list  
✔ Data visualization charts  

---

# Application Interface

## Sales Dashboard

<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/SDS3.jpg" width="900">
</p>

---

# Architecture

The application follows a **modern full-stack architecture**.
```text
Browser (React Frontend)
│
▼
React Components
│
▼
REST API Requests
│
▼
Spring Boot Backend
│
▼
Database
```

Frontend communicates with the backend using HTTP REST APIs.

---

# Folder Structure
```text
AnaliseDesempenho
│
├── backend
│ ├── controllers
│ ├── services
│ ├── repositories
│ └── entities
│
├── frontend
│ ├── components
│ ├── pages
│ ├── services
│ └── assets
│
└── README.md
```

---

# Technologies

## Frontend

- React
- TypeScript / JavaScript
- HTML
- CSS
- Chart libraries

## Backend

- Java
- Spring Boot
- REST API
- JPA / Hibernate

---

# Live Demo

Frontend deployed on Netlify:

https://thiagoreislima-dsvendas.netlify.app/

⚠️ **Important**

The backend was originally deployed on Heroku.  
Since the free tier was discontinued, the cloud demo currently loads **only the frontend interface**.

The **complete backend implementation is fully available in this repository** and can be executed locally.

---

# How to Run

### Clone repository
```text
git clone
```
---

### Run Backend
```text
cd frontend
npm install
npm start
```

---

# Learning Outcomes

This project demonstrates:

- full-stack development
- React frontend architecture
- REST API development with Spring Boot
- dashboard data visualization
- frontend-backend communication
- enterprise web application architecture

---

# Author

Thiago Reis Lima

LinkedIn
```text
https://www.linkedin.com/in/thiago-lima-2a5896166
```
