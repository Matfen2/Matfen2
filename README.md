<div align="center">
  
# 👋 Salut, je suis Mathieu FENOUIL
### Développeur Full-Stack | React.js · Node.js · NestJS · Kafka · Docker · AWS | Alternance Bac+5 Software Engineer
<p>
  <a href="https://www.linkedin.com/in/mathieu-fenouil/"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://freello.site"><img src="https://img.shields.io/badge/-Freello_Live-6366F1?style=for-the-badge&logo=trello&logoColor=white"/></a>
  <a href="http://techpulse-portfolio.com"><img src="https://img.shields.io/badge/-TechPulse_Live-F97316?style=for-the-badge&logo=react&logoColor=white"/></a>
  <a href="https://portfolio-lilac-five-11.vercel.app"><img src="https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="mailto:matfen3.05@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
</div>

---

## 🚀 À propos

Ancien professionnel de l'audiovisuel reconverti en développeur, je conçois des applications web robustes et scalables. Ma rigueur acquise sur les plateaux et mon appétence pour les bonnes pratiques (tests, CI/CD, conteneurisation) m'orientent naturellement vers le **Software Engineering avec spécialisation DevOps**.

🎯 **Objectif :** Maîtriser le cycle complet de conception, développement et déploiement d'applications modernes  
📍 **Localisation :** Istres, France | Mobilité France entière  
💼 **Statut :** Développeur Full-Stack chez DaftLink | Recherche alternance Bac+5 Software Engineer (18 mois – 3 sem. entreprise / 1 sem. cours) via Liora (ex-DataScientest)  
📅 **Dates de rentrée :** 13 mars, 12 juin ou 11 septembre 2026  

---

## 🟣 Projet Phare — Freello

<div align="center">

### [🔗 freello.site](https://freello.site) &nbsp;•&nbsp; [📋 Swagger](https://freello.site/api) &nbsp;•&nbsp; [💻 Code Source](https://github.com/Matfen2/freello)

**Application de gestion de projets et tâches inspirée de Trello - architecture event-driven avec Apache Kafka**

*Conçu et déployé en 8 jours — du monorepo Nx au déploiement VPS avec CI/CD automatisé*

</div>

<br>

<table>
<tr>
<td width="50%">

**🛠️ Stack technique**

| Couche | Technologies |
|--------|-------------|
| Frontend | React 18 · TypeScript · TailwindCSS · framer-motion · @dnd-kit |
| Backend | NestJS · TypeScript · TypeORM · JWT HttpOnly |
| Database | PostgreSQL 16 · Cache in-memory |
| Messaging | Apache Kafka (KRaft) · Schema Registry · Avro |
| DevOps | Nx monorepo · Docker · GitHub Actions · nginx · SSL |
| Cloud | VPS OVH · GHCR · Let's Encrypt |

</td>
<td width="50%">

**📊 En chiffres**

| Métrique | Valeur |
|----------|--------|
| Services Docker | 7 (backend, frontend, postgres, kafka, schema-registry, nginx, certbot) |
| Tests unitaires | 53 (Jest) |
| Endpoints REST | 20+ documentés Swagger |
| Pattern | Outbox Pattern + Kafka |
| CI/CD | GitHub Actions → GHCR → VPS auto-deploy |
| Temps de réalisation | 8 jours |

</td>
</tr>
</table>

**🎯 Fonctionnalités clés :**
- 🟣 **Kanban drag & drop** — déplacement inter-colonnes avec @dnd-kit et optimistic update
- 📋 **Vue liste & Kanban** — toggle animé, filtres par statut, pagination, changement de statut inline
- ⚡ **Event-driven** — chaque mutation tâche publie un événement Kafka via l'Outbox Pattern (atomique)
- 🔐 **Auth JWT** — HttpOnly cookies, Guards (JWT / Roles / SelfOrAdmin), rate limiting
- 🏗️ **Nx monorepo** — backend, frontend et libs partagées (`@freello/api-types`) dans un seul repo
- 📖 **Swagger UI** — documentation API auto-générée et interactive sur `/api`
- 🚀 **CI/CD complet** — lint + tests + Docker build + push GHCR + deploy SSH à chaque push main

---

## 🔶 Projet — TechPulse

<div align="center">

### [🔗 techpulse-portfolio.com](http://techpulse-portfolio.com) &nbsp;•&nbsp; [💻 Code Source](https://github.com/Matfen2/techpulse)

**Catalogue high-tech B2C + Marketplace C2C avec vérification vidéo obligatoire**

*Conçu et déployé en 14 jours - de l'architecture au déploiement AWS*

</div>

<br>

<table>
<tr>
<td width="50%">

**🛠️ Stack technique**

| Couche | Technologies |
|--------|-------------|
| Frontend | React 18 · Vite · Tailwind CSS 4 · Framer Motion · Recharts |
| Backend | Node.js 20 · Express · JWT · Multer · Cloudinary |
| Database | MongoDB 7 · Mongoose |
| DevOps | Docker multi-stage · Nginx · GitHub Actions |
| Cloud | AWS EC2 (Paris) · Cloudinary · Hostinger DNS |

</td>
<td width="50%">

**📊 En chiffres**

| Métrique | Valeur |
|----------|--------|
| Modèles MongoDB | 6 (User, Product, Listing, Review, Order, Favorite) |
| Endpoints REST | 25+ sécurisés (JWT) |
| Pages responsive | 16 (mobile-first) |
| Produits au catalogue | 24 (6 marques, 4 catégories) |
| Tests API | Vitest + Supertest |
| Temps de réalisation | 14 jours |

</td>
</tr>
</table>

**🎯 Fonctionnalités clés :**
- 🔶 **Catalogue B2C** - 24 produits high-tech avec filtres, tri, recherche, pagination et fiches détaillées
- 🏪 **Marketplace C2C** - Vente d'occasion entre particuliers avec upload vidéo Cloudinary obligatoire
- 📹 **Vérification vidéo** - Chaque vendeur filme son produit, un admin vérifie avant publication
- 🛒 **Panier & Checkout** - Ajout au panier, résumé, protection acheteur, paiement simulé
- 👤 **Dashboard utilisateur** - Favoris, avis, annonces, paramètres
- 🔧 **Panel Admin** - Dashboard Recharts, gestion produits CRUD, modération annonces, gestion utilisateurs
- 🐳 **Docker prod** - Multi-stage builds (Nginx + Node.js), docker-compose.prod.yml
- 🚀 **Déployé sur AWS EC2** - Instance Paris, Elastic IP, domaine custom

---

## 💼 Expérience Actuelle

### 🔗 [DaftLink](https://daftlink.com) • Développeur Full-Stack
> Startup SaaS B2B - Plateforme DropChain de recommandation virale | *Décembre 2024 - Présent*

**Stack :** Vue.js 3 • Tailwind CSS • Node.js • Express • MongoDB • Docker • GitHub Actions

- ✅ Développement de 15+ composants Vue.js modulaires et réutilisables
- ✅ Intégration Stripe pour les chaînes professionnelles
- ✅ Implémentation d'une prévisualisation mobile responsive
- ✅ Automatisation CI/CD via GitHub Actions (tests, linting, déploiement)
- ✅ Containerisation de l'environnement de développement avec Docker

---

## 💻 Stack Technique

### Frontend
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Backend
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS_EC2-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### En apprentissage
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### Outils & Productivité
![Claude](https://img.shields.io/badge/-Claude_AI-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/-Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/-Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

---

## 🎓 Parcours

| Formation | Établissement | Période | Statut |
|-----------|---------------|---------|--------|
| **Software Engineer** (Bac+5 - Niveau 7 RNCP) | Liora (ex-DataScientest) | À partir de 2026 | 🔍 Alternance recherchée |
| **Concepteur Développeur Logiciel** (Bac+3 - Niveau 6 RNCP) | OpenClassrooms | 2025 | ✅ Validé |
| **Développeur Informatique** (Bac+2) | OpenClassrooms | 2024 | ✅ Validé |

### 🔄 Reconversion professionnelle
Ancien professionnel de l'audiovisuel et du cinéma (2018-2024) - régisseur, machino, ingénieur son :
- 🎯 Rigueur acquise sur des productions avec deadlines serrées
- 👥 Travail d'équipe sur des projets techniques complexes
- 🔧 Autonomie, adaptabilité et résolution de problèmes
- 💡 Apprentissage du développement en autodidacte depuis 2022

---

## 📫 Me Contacter

<div align="center">

| 📧 Email | 💼 LinkedIn | 🟣 Freello | 🔶 TechPulse | 🌐 Portfolio |
|----------|-------------|-----------|-------------|--------------|
| [mathieu.fenouil.pro@gmail.com](mailto:mathieu.fenouil.pro@gmail.com) | [Mathieu FENOUIL](https://www.linkedin.com/in/mathieu-fenouil/) | [freello.site](https://freello.site) | [techpulse-portfolio.com](http://techpulse-portfolio.com) | [Portfolio](https://portfolio-mathieu-fenouil.vercel.app) |

</div>

---

<div align="center">

### 💡 "De l'audiovisuel au code — autodidacte devenu développeur, futur Software Engineer"

**🟢 Ouvert aux opportunités** • **📍 France entière** • **🚀 Disponible 2026**

![Profile Views](https://komarev.com/ghpvc/?username=matfen2&color=6366F1&style=flat-square)

</div>
