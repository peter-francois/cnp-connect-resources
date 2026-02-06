# CNP-Connect – Project Documentation

This repository gathers all **design, modeling, and documentation resources**, as well as some orchestration and configuration files (e.g., docker-compose) for the **CNP-Connect** project.

It is intended as a clear entry point to understand the project without having to read the source code.

It complements the code repositories (Frontend and Backend) by presenting the project’s reflection, design, and architecture.

---

## 🔗 Links to Code Repositories

- **Frontend:** https://github.com/peter-francois/cnp-connect-frontend  
- **Backend:** https://github.com/peter-francois/cnp-connect-backend  

---

## 📱 Application Overview

CNP-Connect is an internal web application designed for public transportation companies.

It allows:

- **Field agents** to view their assignments and receive alerts,  
- **Supervisors** and **coordinators** to monitor team availability in real time and reassign agents when necessary.  

---

## 🛠️ Tech Stack

### Frontend

- React, TypeScript, Vite, Tailwind  
- Axios, TanStack Query, React Hook Form, Zod  

### Backend

- Node.js, NestJS  
- Prisma, MySQL  
- JWT, Guards, Middlewares  

---

## 📁 Repository Structure
```
cnp-connect-docs/
│
├── 01_conception/
│ ├── backlog/
│ ├── mock_ups/
│ ├── sequence_diagrams/
│ └── wireframes/
│
├── 02_database_modeling/
│ └── merise/
│
├── 03_api/
│ └── endpoints.pdf
│
├── 04_architecture/
│
└── 05_devops/
├── compose/
└── proxy/
```

---

## 📐 Design

This folder contains:

- **Wireframes** created with Excalidraw,  
- **Mock-ups** created with Figma,  
- **Sequence diagrams** created in VSCode using PlantUML,  
- Prioritized **user stories** (backlog) formalizing user needs.  

These elements illustrate the design approach prior to development.

---

## 🗄️ Modeling (MERISE)

The project is based on MERISE modeling, including:

- **MCD (Conceptual Data Model)**  
- **MLD (Logical Data Model)**  
- **MPD (Physical Data Model)** created in MySQL Workbench  
- An **SQL script** to recreate the database  

---

## 🌐 API – Endpoints

The endpoint documentation details:

- Main backend routes,  
- HTTP verbs,  
- Expected parameters,  
- API responses.  

---

## 🏗️ Architecture

This section contains diagrams for:

- The **global architecture**,  
- The **frontend architecture**,  
- The **backend architecture**.  

---

## 🚀 DevOps

The project includes:

- **docker-compose** files (dev/prod) to run the stack,  
- A **docker-compose** setup for the **reverse proxy (Nginx Proxy Manager)**.  

---

## 📬 Contact

If you have any questions or would like to discuss the project:

- **Email:** contact@peterfrancois.dev  
- **LinkedIn:** https://www.linkedin.com/in/peterfrancois  
- **GitHub:** https://github.com/peter-francois  

Feel free to open an issue if you would like to discuss the project.
