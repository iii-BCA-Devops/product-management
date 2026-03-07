# Textile Product Management – Backend

## 📌 Project Overview
This project is the **backend service** for the Textile Product Management System.  
It is developed using **Spring Boot** and provides REST APIs to manage products and orders.

The backend is containerized using **Docker**, analyzed using **SonarCloud**, and deployed on **Render** as part of the DevOps workflow.

---

## 🛠️ Technologies Used

### Backend Development
- Java 17
- Spring Boot
- Spring Data JPA
- Maven

### Database
- H2 Database / MySQL

### DevOps Tools
- **Docker** – Used to containerize the backend application.
- **SonarCloud** – Used for static code analysis to detect bugs, vulnerabilities, and code smells.
- **Render** – Used to deploy and host the backend application.

### Version Control
- Git
- GitHub

---

## 🐳 Docker Support

Docker is used to containerize the backend application for easy deployment.

### Build Docker Image

```
docker build -t textile-backend .
```

### Run Docker Container

```
docker run -p 8080:8080 textile-backend
```

Application will run at:

```
http://localhost:8080
```
Docker Image 

<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/f791bbbc-8795-4cc4-b390-aa40794c78fd" />

---

## 🔍 Code Quality – SonarCloud

Code quality and security analysis are performed using **SonarCloud**.

SonarCloud automatically scans the codebase and detects:

- Bugs
- Security vulnerabilities
- Code smells
- Maintainability issues

### SonarCloud Dashboard
View the analysis report here:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5ff2541-261f-4eff-b29c-70c980f388e1" />

### Quality Gate Status

✔ Passed  
Security → A  
Reliability → A  
Maintainability → A  

---

## 🚀 Deployment – Render

The backend application is deployed on **Render**.

Deployment platform:
- Render Cloud Platform

Backend Live URL:

```
https://your-backend-url.onrender.com
```

---

