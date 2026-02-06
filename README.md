# CNP-Connect, documentation du projet

Ce dépôt regroupe l’ensemble des **ressources de conception, modélisation et documentation**, ainsi que certains fichiers d’orchestration et de configuration (ex : docker-compose) du projet **CNP-Connect**.

Il est conçu comme un point d’entrée clair pour comprendre le projet sans avoir à lire le code source.

Il vient compléter les dépôts de code (Frontend et Backend) en présentant la réflexion, la conception et l’architecture du projet.

---

## 🔗 Liens vers les repos de code

- Frontend : https://github.com/peter-francois/cnp-connect-frontend
- Backend : https://github.com/peter-francois/cnp-connect-backend

---

## 📱 Description de l’application

CNP-Connect est une application web interne destinée aux entreprises de transport en commun.

Elle permet notamment :

- aux **agents de terrain** de consulter leurs affectations et recevoir des alertes,
- aux **superviseurs** et aux **coordinateurs** de suivre la disponibilité des équipes en temps réel et de réaffecter des agents si nécessaire.

---

## 🛠️ Stack technique

### Frontend

- React, TypeScript, Vite, Tailwind
- Axios, TanStack Query, React Hook Form, Zod

### Backend

- Node.js, NestJS
- Prisma, MySQL
- JWT, Guards, Middlewares

---

## 📁 Organisation du dépôt

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

## 📐 Conception

Ce dossier contient :

- Les **wireframes** réalisés sur Excalidraw,
- Des exemples de **maquettes** (mock-ups) réalisés avec Figma,
- Des exemples de **diagramme de séquence** (sequence_diagrams) réalisés avec sur VSCode en PlantUML,
- Les **user stories** priorisées (backlog) formalisant les besoins utilisateurs.

Ces éléments montrent la démarche de conception en amont du développement.

---

## 🗄️ Modélisation (MERISE)

Le projet s’appuie sur une modélisation MERISE comprenant :

- **MCD (Modèle Conceptuel des Données)**
- **MLD (Modèle Logique des Données)**
- **MPD (Modèle Physique des Données)** sous MySQL Workbench
- Un **script SQL** permettant de recréer la base.

---

## 🌐 API — Endpoints

La documentation des endpoints détaille :

- Les routes principales du backend
- Les verbes HTTP
- Les paramètres attendus
- Les réponses de l’API

---

## 🏗️ Architecture

Les shémas de l'architecture pour :  
- L'architecture globale  
- L'architecture du frontend
- L'architecture du backend

---

## 🚀 DevOps

Le projet intègre :

- les fichiers **docker-compose** (dev/prod) pour exécuter la stack,
- le **docker-compose** du **reverse proxy (Nginx Proxy Manager)**,

---

## 📬 Contact

Si vous avez des questions ou souhaitez échanger sur le projet :

- **Email :** contact@peterfrancois.dev
- **LinkedIn :** https://www.linkedin.com/in/peterfrancois
- **GitHub :** https://github.com/peter-francois

N’hésitez pas à ouvrir une issue si vous souhaitez discuter du projet.

