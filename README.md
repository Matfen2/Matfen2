<div align="center">

# 👋 Mathieu FENOUIL
### Développeur Full-Stack Java/Spring Boot · Angular · Oracle

🚀 Java 25 · Spring Boot · Spring Batch · Angular · React · TypeScript · Oracle · PostgreSQL · Kafka · Docker · Kubernetes

<p>
  <a href="https://www.linkedin.com/in/mathieu-fenouil-développeur-full-stack/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Matfen2"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github"/></a>
  <a href="mailto:matfen3.05@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

</div>

---

## 🚀 Profil

Développeur full-stack avec une approche **orientée système** : je ne livre pas des features, je construis des applications qui tiennent en production, testées, mesurées et déployées en continu.

💡 Ce que j'apporte :
- Backend Java 25 / Spring Boot orienté domaine, en contract-first (OpenAPI), architecture hexagonale, traitements par lots (Spring Batch)
- Frontend Angular et React / TypeScript, structuré et maintenable
- Bases de données exploitées en profondeur : Oracle (PL/SQL, SQL analytique, plans d'exécution), PostgreSQL
- Systèmes event-driven (Kafka, Outbox Pattern, microservices)
- Qualité et DevOps de bout en bout : TDD, tests de charge et E2E, analyse de code, CI/CD, Docker, Kubernetes, cloud

👉 **Reconversion depuis l'audiovisuel : rigueur terrain, livraison sous contrainte, sens du produit.**

---

## 🔥 Projets clés

*Projets personnels, conçus et développés en autonomie pour démontrer mes compétences techniques : il ne s'agit pas de commandes clients. Chacun est traité comme un vrai projet, du cahier des charges à la mise en production.*

### 🏭 MécaDétect - Suivi de maintenance industrielle (projet personnel · Java · Angular · Oracle)
🔗 **https://mecadetect.duckdns.org** (comptes de démonstration dans le README)  
🔗 https://github.com/Matfen2/mecadetect

Application de GMAO sur un cas d'usage réaliste : déclaration des pannes, planification des interventions par technicien habilité, pilotage du parc d'équipements. Conçue en 8 sprints à partir d'un cahier des charges (modélisation Merise, critères d'acceptation), développée en TDD et déployée en continu.

**Stack :** Java 25 · Spring Boot 4 · Spring Batch · MapStruct · Angular 21 · Oracle 23 (PL/SQL) · OpenAPI · Docker · Caddy · GitHub Actions · Oracle Cloud

✔️ Contract-first : interfaces Spring et client Angular générés depuis le contrat OpenAPI  
✔️ Cycle de vie des interventions en `sealed interface` + pattern matching, verrouillage optimiste testé en concurrence réelle  
✔️ **Revue de code par un développeur Java senior** : 22 remarques traitées, dont le passage en **architecture hexagonale** vérifiée par un test d'architecture  
✔️ **Import du parc par lots avec Spring Batch** : lecture CSV, validation ligne par ligne, une transaction par lot, rejets détaillés avec leur motif  
✔️ Oracle avancé : trigger d'historique, génération de 500 000 interventions en PL/SQL, reporting analytique (`RANK`, `LAG`), archivage par lots  
✔️ Performance mesurée : première page de recherche de 480 ms à 7 ms ; sous charge Gatling, p95 de 403 ms à 21 ms  
✔️ 426 tests : JUnit 5 + Testcontainers (Oracle), Vitest, **Robot Framework** (parcours E2E dans Chromium)  
✔️ SonarCloud : 0 alerte ouverte, notes A ; Trivy analyse les dépendances et les images dans la CI  
✔️ Pipeline : tests → SonarCloud → E2E sur Docker Compose → images arm64 → Trivy → déploiement SSH → 15 vérifications en production  
✔️ Sauvegardes Data Pump chaque nuit vers Object Storage, **test de restauration automatique** chaque semaine

---

### ⚖️ JuriBook - Plateforme de réservation juridique (projet personnel · microservices)
🔗 **https://juribook.fr**

Plateforme de prise de rendez-vous avec des avocats (cas d'usage fictif, sans client réel), conçue en **architecture microservices event-driven**, déployée en production.

**Stack :** React · TypeScript · Java · Spring Boot · Kafka KRaft · PostgreSQL · Docker · Kubernetes · Terraform · Scaleway

✔️ 6 microservices indépendants (auth, avocat, réservation, notification, audit, API Gateway)  
✔️ Event-driven via Kafka KRaft (pas de ZooKeeper)  
✔️ Auth JWT centralisée dans la gateway (Spring Cloud Gateway WebMVC)  
✔️ Modération des avis côté admin : masquer/démasquer (réversible) ou supprimer définitivement, recalcul de note moyenne en temps réel dans la même transaction  
✔️ Détection d'abus et système d'audit  
✔️ Infrastructure as Code (Terraform : cluster K8s, RDB PostgreSQL, réseau privé)  
✔️ CI/CD GitHub Actions → GHCR → Scaleway Kapsule  
✔️ SSL Let's Encrypt via cert-manager · 43 tests Cypress E2E au vert

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
| **Frontend** | Angular · React · TypeScript · Angular Material · Tailwind CSS |
| **Backend** | Java 25 / Spring Boot · Spring Batch · Spring Security (JWT) · MapStruct · Node.js · Express · NestJS · API REST · OpenAPI |
| **Bases de données** | Oracle (PL/SQL, SQL analytique) · PostgreSQL · MongoDB · Flyway |
| **Tests** | JUnit · Mockito · Testcontainers · Vitest · Jest · Robot Framework · Cypress · Gatling |
| **Qualité et sécurité** | SonarCloud · Trivy · OWASP Dependency-Check · revue de code |
| **Messaging** | Apache Kafka KRaft |
| **DevOps** | Docker · Docker Compose · Kubernetes · Terraform · GitHub Actions · Caddy · Nginx |
| **Cloud** | Oracle Cloud (VM Ampere, Object Storage) · Scaleway (Kapsule, RDB) · Render |

---

## 🎯 Recherche

**CDI Développeur Full-Stack Java**  
📍 Basé en région PACA (prioritaire) - mobilité PACA + remote

Je recherche un environnement où :
- les architectures sont pensées pour durer
- la qualité technique est une priorité
- les problèmes à résoudre sont réels et complexes

📧 matfen3.05@gmail.com  
💼 [linkedin.com/in/mathieu-fenouil-développeur-full-stack](https://www.linkedin.com/in/mathieu-fenouil-développeur-full-stack/)
