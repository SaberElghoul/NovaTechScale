
# 🚀 NovaTechScale

### *Laboratoire d’Ingénierie et d’Innovation Continue*

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?logo=springboot)
![Angular](https://img.shields.io/badge/Angular-18-DD0031?logo=angular)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes)
![Terraform](https://img.shields.io/badge/Terraform-IaC-844FBA?logo=terraform)
![DevSecOps](https://img.shields.io/badge/DevSecOps-Automation-red?logo=githubactions)

---
## 📚 Table des matières
- [Introduction](#-introduction)
- [Objectifs](#-objectifs)
- [Stack technique](#-stack-technique)
- [Architecture cible](#-architecture-cible)
- [Auteur](#-auteur)

---

## 🧭 Introduction

**NovaTechScale** est un **laboratoire d’ingénierie et d’innovation continue personnelle**, imaginé et développé par **Saber ELGHOUL**.
Ce projet constitue un **écosystème technique complet** permettant de concevoir, expérimenter et perfectionner des solutions basées sur les principes d’**architecture logicielle moderne**, de **DevSecOps** et de **Cloud Engineering**.

L’objectif : construire et faire évoluer une **plateforme SaaS multi-services** intégrant les meilleures pratiques d’ingénierie logicielle — une approche centrée sur la **performance**, la **sécurité**, la **scalabilité** et l’**innovation continue**.

---

## 🎯 Objectifs

### 1. 🚧 Ingénierie logicielle complète

* Développer des microservices Java avec Spring Boot, Quarkus et Micronaut.
* Intégrer un front-end Angular modulaire et des micro-frontends.
* Structurer une architecture multi-tenant et sécurisée.

### 2. ☁️ DevSecOps & Cloud

* Automatiser les pipelines CI/CD avec **GitLab**, **Jenkins**, **SonarQube** et **Nexus**.
* Orchestrer les environnements via **Docker**, **Kubernetes**, **Terraform**, **Ansible** et **AWS EC2/RDS/S3/Route 53**.
* Surveiller et tracer les systèmes avec **Prometheus**, **Grafana** et **Loki**.
* Gérer la sécurité avec **Keycloak**, **Vault**, **OAuth2**, **OIDC** et **best practices DevSecOps**.

### 3. 🧠 Innovation continue

* Expérimenter les patterns d’architecture : **API Gateway**, **Service Discovery**, **Event-Driven Architecture** (Artemis/Kafka).
* Explorer de nouvelles approches techniques et documenter chaque apprentissage.
* Construire une base de connaissances d’ingénierie reproductible.

---

## 🧱 Stack technique

| Domaine             | Technologies                                                         |
| :------------------ |:---------------------------------------------------------------------|
| **Backend**         | Java 17+, Spring Boot, Quarkus, Micronaut                            |
| **Frontend**        | Angular 18+, Micro-Frontends                                         |
| **Database**        | PostgreSQL                                                           |
| **Messaging**       | Artemis, Kafka                                                       |
| **CI/CD**           | Jenkins, GitLab CI/CD, SonarQube, Nexus                              |
| **Infra & Cloud**   | AWS (EC2, RDS, S3, Route 53), Docker, Kubernetes, Terraform, Ansible |
| **Monitoring**      | Prometheus, Grafana, Loki                                            |
| **Sécurité**        | Keycloak, Vault, OAuth2, OIDC                                        |
| **Gestion du code** | GitLab                                                               |

---

## 🧭 Architecture cible

```
                  +-----------------------------------+
                  |        🧩 Micro Frontends         |
                  |-----------------------------------|
                  |   UI-A   |   UI-B   |   UI-C      |
                  +-------------------+---------------+
                                      |
                           API Gateway / Auth (Keycloak)
                                      |
                  +-------------------+-------------------+
                  |   Nginx / Traefik Reverse Proxy       |
                  +-------------------+-------------------+
                                      |
                     Config / Discovery / Tenant Registry
                                      |
          +-------------+-------------+-------------+-------------+
          |             |             |             |             |
         SvcA          SvcB          SvcC          SvcD          SvcE
          |             |             |             |             |
          |------> Redis Cache / Session Store <----|             |
          |             |             |             |             |
     PostgreSQL     PostgreSQL    PostgreSQL    PostgreSQL    PostgreSQL
                                      |
          +-------------+-------------+-------------+-------------+
                        Kafka / Artemis Message Bus
                                      |
                           Monitoring & Observability
                                      |
       Prometheus + Grafana + Loki + Jaeger + AlertManager + Vault


    Schéma simplifié de l’architecture NovaTechScale : micro-frontends Angular, microservices Java,
     Redis, Kafka, observabilité et sécurité intégrée.

```

NovaTechScale est bien plus qu’un projet :
c’est une **initiative personnelle d’ingénierie continue**, un **laboratoire vivant** pour explorer, apprendre et innover sans limite.

---

## 👨‍💻 Auteur

**Saber ELGHOUL**
📍 Bordeaux, France
💼 Développeur Full-Stack Java / Angular | DevSecOps Engineer
🌐 [https://novatechscale.com](https://novatechscale.com) *(en cours de construction)*
📧 [saber.elghoul.pro@gmail.com](mailto:saber.elghoul.pro@gmail.com)

---

> *« NovaTechScale – Think big. Build smart. Evolve continuously. »*


<p align="center">
  <sub>🧩 NovaTechScale © 2025 — Laboratoire d’Ingénierie et d’Innovation Continue personnelle par <strong>Saber ELGHOUL</strong></sub><br/>
  <sub>🌐 <a href="https://novatechscale.com">novatechscale.com</a></sub>
</p>


