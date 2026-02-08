# DevOps for the CNP-Connect project

This folder brings together the **orchestration** and **deployment** files for the **CNP-Connect** project, mainly based on **Docker** and **Docker Compose**.
It complements the project’s overall documentation by showing how the application is run and deployed.

---

## 🎯 Objective

This folder is used to document and centralize:

- the **docker-compose** files to run the stack,
- the **docker-compose** for the **reverse proxy** (Nginx Proxy Manager).

---

## 🐳 Docker Compose

The `compose/` folder contains the `docker-compose` files used to run locally (or on a server):

- the **Frontend** (React + Nginx),
- the **Backend** (NestJS),
- the **MySQL database**.

---

## 🔁 Reverse Proxy — Nginx Proxy Manager

The `proxy/` folder contains a `docker-compose` file to deploy Nginx Proxy Manager.

Main roles:
- manage domains,
- automatically enable HTTPS (Let’s Encrypt),
- route traffic to:
  - the frontend,
  - the backend.

---

## ☁️ Deployment

The deployment infrastructure is:

- Server : AWS (EC2),
- Reverse Proxy : Nginx Proxy Manager,
- Orchestration : Docker Compose,
- HTTPS : Let’s Encrypt certificates via Nginx Proxy Manager.

---

## 📁 Contenu du dossier

05_devops/  
│  
├── compose/ # docker-compose (dev/prod) + .env.example  
└── proxy/ # Nginx Proxy Manager (compose)
