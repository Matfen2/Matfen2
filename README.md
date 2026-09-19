<div align="center">

# 👋 Mathieu FENOUIL
### Développeur Full-Stack

🚀 React · TypeScript · Spring Boot · Java · PostgreSQL · Node.js · Kafka · Docker · Kubernetes 

<p>
  <a href="https://www.linkedin.com/in/mathieu-fenouil-développeur-full-stack/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Matfen2"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github"/></a>
  <a href="mailto:matfen3.05@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

</div>

---

## 🚀 Profil
 
Développeur full-stack avec une approche **orientée système** : je ne livre pas des features, je construis des architectures qui tiennent en production.
 
💡 Ce que j'apporte :
- Frontend React / TypeScript structuré et maintenable
- Backend Java Spring Boot & Node.js orienté domain
- Systèmes event-driven (Kafka, Outbox Pattern, microservices)
- DevOps end-to-end : CI/CD, Docker, Kubernetes, Terraform, cloud Scaleway / AWS

👉 **Reconversion depuis l'audiovisuel : rigueur terrain, livraison sous contrainte, sens du produit.**
 
---

## 🔥 Projets clés

### ⚖️ JuriBook - Plateforme de réservation juridique (microservices)
🔗 **https://juribook.fr**

Plateforme de prise de rendez-vous avec des avocats, conçue en **architecture microservices event-driven**, déployée en production.

**Stack :** React · TypeScript · Java · Spring Boot · Kafka KRaft · PostgreSQL · Docker · Kubernetes · Terraform · Scaleway

✔️ 6 microservices indépendants (auth, avocat, réservation, notification, audit, API Gateway)  
✔️ Event-driven via Kafka KRaft (pas de ZooKeeper)  
✔️ Auth JWT centralisée dans la gateway (Spring Cloud Gateway WebMVC)  
✔️ Modération des avis côté admin : masquer/démasquer (réversible) ou supprimer définitivement, recalcul de note moyenne en temps réel dans la même transaction  
✔️ Détection d'abus et système d'audit  
✔️ Infrastructure as Code (Terraform : cluster K8s, RDB PostgreSQL, réseau privé)  
✔️ CI/CD GitHub Actions → GHCR → Scaleway Kapsule  
✔️ SSL Let's Encrypt via cert-manager · 43 tests Cypress E2E au vert

💡 *Production-ready : https://juribook.fr*

---

### ☕ FoodExpress - API REST (Spring Boot)
🔗 https://matfen2.github.io/foodexpress/  
🔗 https://github.com/Matfen2/foodexpress

API de gestion de commandes construite avec une approche **production-ready**.

**Stack :** Java · Spring Boot · PostgreSQL · Flyway · Docker · CI/CD · Render

✔️ Architecture en couches (Controller / Service / Repository)  
✔️ Validation DTO + gestion centralisée des erreurs  
✔️ Migrations versionnées (Flyway V1→V4)  
✔️ Tests unitaires (JUnit 5, Mockito, MockMvc)  
✔️ Swagger auto-documenté  
✔️ Pipeline CI/CD : GitHub Actions → GHCR → auto-deploy Render  
✔️ Monitoring : UptimeRobot sur la sonde `/actuator/health/liveness`, alertes email

⚠️ *Démo actuellement suspendue (quota d'heures d'instance du tier gratuit Render dépassé) - reprise automatique prévue début octobre. Code, tests et documentation consultables sur le dépôt GitHub en attendant.*

---

## 💼 Expérience
 
### Développeur Full-Stack - DaftLink *(Bénévolat - Décembre 2024 - Décembre 2025)*
*SaaS B2B · Engagement compatible avec une prise de poste en CDI*
 
- Développé des fonctionnalités front-end en Vue.js puis évolué vers du full-stack Node.js / MongoDB, pour un outil SaaS B2B en livraison continue
- Conçu des endpoints REST Node.js intégrés à un pipeline CI/CD Docker
- Proposé et implémenté des solutions techniques en collaboration avec l'équipe sur des problématiques produit spécifiques
- Livré des features en production dans un contexte produit réel sous contrainte délai

---
 
## 🧠 Stack technique
 
| Domaine | Technologies |
|---|---|
| **Frontend** | React · TypeScript · Tailwind CSS |
| **Backend** | Java / Spring Boot · Node.js · Express · NestJS · API REST |
| **Tests** | Jest · Supertest · JUnit · Mockito · Cypress (E2E) |
| **Messaging** | Apache Kafka KRaft |
| **Bases de données** | PostgreSQL · MongoDB · Flyway |
| **DevOps** | Docker · Kubernetes · Terraform · GitHub Actions · CI/CD |
| **Cloud** | Scaleway (Kapsule, RDB) · Render |
| **Outils** | Swagger · Zod · JWT · bcrypt · dotenv |
 
---
 
## 🎯 Recherche

**CDI Développeur Full-Stack**  
📍 Basé en région PACA (prioritaire) - mobilité PACA + remote

Je recherche un environnement où :
- les architectures sont pensées pour durer
- la qualité technique est une priorité
- les problèmes à résoudre sont réels et complexes

📧 matfen3.05@gmail.com  
💼 [linkedin.com/in/mathieu-fenouil-développeur-full-stack](https://www.linkedin.com/in/mathieu-fenouil-développeur-full-stack/)
