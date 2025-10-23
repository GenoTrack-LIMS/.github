<!-- Vous pouvez créer une bannière simple sur Canva (1280x400px) et la téléverser dans ce repository -->
<p align="center">
    <img width="1920" height="384" alt="Bannière Reddit Illustrative Minimale Violet et Rose" src="https://github.com/user-attachments/assets/6dbbe7a5-2dfd-4411-a2c1-58782597c2fb" />
</p>

<h1 align="center">GenoTrack-LIMS</h1>

<p align="center">
  <strong>Un Système de Gestion d'Information de Laboratoire (LIMS) full-stack pour la recherche moderne.</strong>
  <br />
  <i>Conçu pour garantir l'intégrité des données et une traçabilité sans faille des échantillons biologiques.</i>
</p>

<p align="center">
  <!-- Badges/Shields pour un look pro. Personnalisez les versions si besoin. -->
  <img src="https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=springboot" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Angular-19-DD0031?style=for-the-badge&logo=angular" alt="Angular">
  <img src="https://img.shields.io/badge/PostgreSQL-17-336791?style=for-the-badge&logo=postgresql" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Licence-MIT-blue.svg?style=for-the-badge" alt="License">
</p>

---

## 🎯 Objectif du Projet

J'ai conçu GenoTrack-LIMS en pensant aux besoins critiques des laboratoires de biologie moléculaire : **la traçabilité parfaite et l'intégrité des données**. De la réception d'un échantillon brut à la génération de ses dérivés (extraits d'ADN, produits de PCR), chaque étape est suivie et enregistrée, dans le respect des Bonnes Pratiques de Laboratoire (BPL).

Ce projet (bien que ce soit quelques fonctionalités) démontre la construction d'une application web complète, robuste et sécurisée, avec une architecture découplée entre le front-end et le back-end.

<img width="1917" height="908" alt="02" src="https://github.com/user-attachments/assets/523e517a-558a-4157-a4e1-f4680f737055" />



## ✨ Fonctionnalités Clés

*   **👣 Traçabilité Complète :** Suivi de la filiation des échantillons (parent-enfant) pour remonter à l'origine de n'importe quel dérivé.
*   **🔬 Gestion de Plaques 96 Puits :** Un composant Angular interactif et visuel pour gérer le contenu des plaques expérimentales.
*   **🔒 Sécurité Basée sur les Rôles :** Authentification par token JWT et autorisations granulaires (Technicien, Chercheur) via Spring Security.
*   **✍️ Journal d'Audit (Audit Log) :** Chaque création, modification ou suppression est tracée pour garantir la conformité et l'intégrité des données.
*   **🎨 Interface Moderne et Responsive :** Une expérience utilisateur soignée, fonctionnelle sur ordinateur, tablette et mobile.

## 🛠️ Stack Technologique

Ce projet est divisé en deux repositories principaux, chacun avec sa propre stack technologique.

| Domaine       | Technologie                                                                           |
|---------------|---------------------------------------------------------------------------------------|
| ⚙️ **Back-End**  | **Java 21**, **Spring Boot**, **Spring Security (JWT)**, **JPA/Hibernate**, **PostgreSQL 17** |
| 🎨 **Front-End** | **Angular 19**, **TypeScript**, **SCSS**, **RxJS**, **Responsive Design**                     |

## 📂 Repositories du Projet

Découvrez le code source détaillé dans les repositories dédiés :

| Repository                                                                 | Description                                                     |
|----------------------------------------------------------------------------|-----------------------------------------------------------------|
| ➡️ **[genotrack-lims-api]([./genotrack-lims-api](https://github.com/GenoTrack-LIMS))**                             | Le serveur back-end RESTful qui gère toute la logique métier.  |
| ➡️ **[genotrack-lims-client](./genotrack-lims-client)**                       | L'application cliente Angular qui fournit l'interface utilisateur. |

## 🚀 Démarrage Rapide (Local)

Pour lancer le projet sur votre machine :

1.  **Base de données :** Assurez-vous d'avoir une instance PostgreSQL en cours d'exécution.
2.  **Back-End (`genotrack-lims-api`) :**
    *   Clonez le repository.
    *   Configurez vos identifiants de base de données dans `src/main/resources/application.yml`.
    *   Lancez l'application via votre IDE ou avec `mvn spring-boot:run`.
3.  **Front-End (`genotrack-lims-client`) :**
    *   Clonez le repository.
    *   Installez les dépendances : `npm install`.
    *   Lancez le serveur de développement : `ng serve`.
    *   Ouvrez votre navigateur sur `http://localhost:4200`.

---
### [Interface] Page de Connexion
<img width="1902" height="905" alt="01" src="https://github.com/user-attachments/assets/f5b2e13a-3eb1-47be-9cc2-21d68092a2b4" />

### [Interface] Page de Visualisation de Plaques 
<img width="1916" height="907" alt="03" src="https://github.com/user-attachments/assets/6829fa79-7a4d-4c15-8fb1-d134222f6c70" />

### [Interface] Page Détails Echantillons 
<img width="1917" height="908" alt="02" src="https://github.com/user-attachments/assets/2c60a554-70c1-4588-913e-0df49eb50099" />

### [Interface] Base de données PostgresSQL 
<img width="1918" height="1033" alt="04" src="https://github.com/user-attachments/assets/1cda2bbe-caac-4745-858e-32d3126b0cd3" />

### [Backend] Controller Spring
<img width="1389" height="849" alt="codeimage-snippet_23 (1)" src="https://github.com/user-attachments/assets/05d10562-6c40-4414-a361-c1c2b0279be8" />

### [Backend] SecurityConfig (chaine de sécurité)
<img width="1389" height="1297" alt="codeimage-snippet_23 (2)" src="https://github.com/user-attachments/assets/b5a055eb-3119-475f-ab76-a99c4fe7228b" />

<p align="center">
  Développé par <strong>Romeo Djoman</strong>
  <br />
  <a href="URL_VERS_VOTRE_LINKEDIN">LinkedIn</a> • <a href="URL_VERS_VOTRE_PORTFOLIO">Portfolio</a>
</p>
