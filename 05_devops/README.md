# DevOps du projet CNP-Connect

Ce dossier regroupe les **fichiers d’orchestration et de déploiement** du projet CNP-Connect, principalement basés sur **Docker et Docker Compose**.  
Il complète la documentation globale du projet en montrant comment l’application est exécutée et déployée.

---

## 🎯 Objectif

Ce dossier sert à documenter et centraliser :

- les fichiers **docker-compose** pour exécuter la stack,
- le **docker-compose** du **reverse proxy (Nginx Proxy Manager)**,

---

## 🐳 Docker Compose

Le dossier `compose/` contient les fichiers `docker-compose` permettent de lancer localement (ou sur serveur) :

- le **Frontend** (React + Nginx),
- le **Backend** (NestJS),
- la **Base de données MySQL**.

---

## 🔁 Reverse Proxy — Nginx Proxy Manager

Le dossier `proxy/` contient un `docker-compose` permettant de déployer Nginx Proxy Manager.

Rôles principaux :
- gérer les domaines,
- activer automatiquement HTTPS (Let’s Encrypt),
- rediriger le trafic vers :
  - le frontend,
  - le backend.

---

## ☁️ Déploiement

L’infrastructure de déploiement est :

- Serveur : AWS (EC2),
- Reverse Proxy : Nginx Proxy Manager,
- Orchestration : Docker Compose,
- HTTPS : Certificats Let’s Encrypt via NPM.

---

## 📁 Contenu du dossier

05_devops/  
│  
├── compose/ # docker-compose (dev/prod) + .env.example  
└── proxy/ # Nginx Proxy Manager (compose)
