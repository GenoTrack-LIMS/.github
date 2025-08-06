<!-- Vous pouvez créer une bannière simple sur Canva (1280x400px) et la téléverser dans ce repository -->
<p align="center">
  <img src="URL_DE_VOTRE_BANNER.png" alt="GenoTrack-LIMS Banner"/>
</p>

<h1 align="center">GenoTrack-LIMS</h1>

<p align="center">
  <strong>Un Système de Gestion d'Information de Laboratoire (LIMS) full-stack pour la recherche moderne.</strong>
  <br />
  <i>Conçu pour garantir l'intégrité des données et une traçabilité sans faille des échantillons biologiques.</i>
</p>

<p align="center">
  <!-- Badges/Shields pour un look pro. Personnalisez les versions si besoin. -->
  <img src="https://img.shields.io/badge/Java-17+-orange?style=for-the-badge&logo=openjdk" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=spring" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Angular-17+-DD0031?style=for-the-badge&logo=angular" alt="Angular">
  <img src="https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge&logo=postgresql" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Licence-MIT-blue.svg?style=for-the-badge" alt="License">
</p>

---

## 🎯 Objectif du Projet

GenoTrack-LIMS a été conçu pour répondre aux besoins critiques des laboratoires de biologie moléculaire : **la traçabilité parfaite et l'intégrité des données**. De la réception d'un échantillon brut à la génération de ses dérivés (extraits d'ADN, produits de PCR), chaque étape est suivie et enregistrée, dans le respect des Bonnes Pratiques de Laboratoire (BPL).

Ce projet démontre la construction d'une application web complète, robuste et sécurisée, avec une architecture découplée entre le front-end et le back-end.

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
| ⚙️ **Back-End**  | **Java 17+**, **Spring Boot**, **Spring Security (JWT)**, **JPA/Hibernate**, **PostgreSQL** |
| 🎨 **Front-End** | **Angular**, **TypeScript**, **SCSS**, **RxJS**, **Responsive Design**                     |

## 📂 Repositories du Projet

Découvrez le code source détaillé dans les repositories dédiés :

| Repository                                                                 | Description                                                     |
|----------------------------------------------------------------------------|-----------------------------------------------------------------|
| ➡️ **[genotrack-lims-api](./genotrack-lims-api)**                             | Le serveur back-end RESTful qui gère toute la logique métier.  |
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

<p align="center">
  Développé par <strong>[Votre Nom]</strong>
  <br />
  <a href="URL_VERS_VOTRE_LINKEDIN">LinkedIn</a> • <a href="URL_VERS_VOTRE_PORTFOLIO">Portfolio</a>
</p>
