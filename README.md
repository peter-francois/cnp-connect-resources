# CNP-Connect, documentation du projet

Ce dépôt regroupe l’ensemble des **ressources de conception, modélisation et documentation** du projet **CNP-Connect**.

Il est conçu comme un point d’entrée clair pour comprendre le projet sans avoir à lire le code source.

Il complète les dépôts de code (Frontend et Backend) en présentant la réflexion, la conception et l’architecture du projet.  

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
│ ├── wireframes/
│ └── user_stories/
│
├── 02_modelisation/
│ └── merise/
|   ├── CNP_connect_MCD.jpg
|   ├── CNP_connect_MLD.jpg
│   ├── CNP-Connect_MPD.mwb
│   └── cnp_connect_mpd.sql
│
├── 03_api/
│ └── endpoints.pdf
│
├── 04_architecture/
│ └── architecture.md
│
└── 05_devops/
├── docker/
│ └── notes_docker.md
└── cicd/
  └── gitlab-ci.md
```

---

## 📐 Conception

Ce dossier contient :
- Les **wireframes** réalisés sur Excalidraw,
- Des exemples de **maquettes** réalisés avec Figma,
- Les **user stories** formalisant les besoins utilisateurs.

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

La documentation des endpoints décrit :
- les routes principales du backend,
- les verbes HTTP,
- les paramètres attendus,
- et les réponses de l’API.

---

## 🏗️ Architecture
- Architecture multicouche (3-tiers)

---

## 🚀 DevOps

Le projet intègre :
- des **Dockerfiles** pour le front et le back,
- une configuration **Nginx** pour servir le frontend,
- une **pipeline GitLab CI/CD** pour build, test et publication des images.

---

## 📬 Contact

Si vous avez des questions ou souhaitez échanger sur le projet :

- **Email :** contact@peterfrancois.dev 
- **LinkedIn :** https://www.linkedin.com/in/peterfrancois  
- **GitHub :** https://github.com/peter-francois  

N’hésitez pas à ouvrir une issue si vous souhaitez discuter du projet.