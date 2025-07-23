# 🧾 Employee Records Manager — MERN Stack (Dockerized) 🚀

A robust, scalable, and containerized MERN (MongoDB, Express, React, Node.js) stack application designed for managing employee records. Fully Dockerized and deployed on AWS EC2 for high availability and modularity.

---

## 📦 About the Project

This project is a full-stack web application to **Create, Read, Update, and Delete (CRUD)** employee records.

What makes it powerful?

> ✅ **Fully containerized architecture** using Docker & Docker Compose  
> ✅ Seamless **service-to-service networking** between frontend, backend, and database  
> ✅ Clean, modular code — easy to scale and maintain  
> ✅ Deployed on **AWS EC2** with production-ready practices  

---

## ⚙️ Tech Stack

| Layer         | Technology               |
|---------------|--------------------------|
| Frontend      | React                    |
| Backend       | Node.js, Express         |
| Database      | MongoDB                  |
| Containerization | Docker, Docker Compose |
| Deployment    | AWS EC2 (Ubuntu)         |

---

## 🐳 Why Docker?

Containers enable this app to:

- Run identically across any environment (dev, staging, production)
- Isolate dependencies for each service
- Use **internal Docker networking** (`http://backend:5050`) for secure service discovery
- Scale effortlessly (scale backend or database independently)
- Enable fast CI/CD pipeline setups in future

---

## 🧱 Project Architecture

