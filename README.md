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
CONTAINERS ON EC2
<img width="1263" height="98" alt="Screenshot 2025-07-24 000929" src="https://github.com/user-attachments/assets/2dc03736-e6df-425c-867c-85f29d3ad0f7" />

FRONTEND RUNNING ON EC2
<img width="1919" height="1006" alt="Screenshot 2025-07-24 000654" src="https://github.com/user-attachments/assets/c625ffd7-654b-40db-a021-fd7d8bb84d67" />

BACKEND RUNNING ON EC2
<img width="1908" height="981" alt="Screenshot 2025-07-24 000702" src="https://github.com/user-attachments/assets/147833a8-131a-406d-86c2-c14d1f5f330b" />

RUNNING EC2 INSTANCE
<img width="901" height="329" alt="Screenshot 2025-07-24 000720" src="https://github.com/user-attachments/assets/d06cb2f0-08f1-46ea-9e2e-7edae26f3176" />

WORKING FRONTEND AFTER GETTING CONNECTED TO BACKEND
<img width="1919" height="872" alt="Screenshot 2025-07-24 000820" src="https://github.com/user-attachments/assets/f884f27c-e30a-4d6f-93ec-669fee9ef9ec" />






