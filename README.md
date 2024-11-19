# Job Teaser clone

![logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTbcOyODWAsMXB3uzJcgHoqNsmz-7tQTIMyg&s/150)  
*Application web de mise en relation entre développeurs et entreprises.*

## Table des matières
1. [Description du projet](#description-du-projet)
2. [Fonctionnalités](#fonctionnalités)
3. [Technologies utilisées](#technologies-utilisées)
4. [Installation](#installation)
5. [Utilisation](#utilisation)
6. [Structure du projet](#structure-du-projet)
7. [Contributeurs](#contributeurs)
8. [Licences](#licences)

---

## Description du projet

🔗 **AdopteUnDev** est une application web permettant aux développeurs et aux entreprises de créer des profils ou des fiches de postes et de les faire correspondre selon un modèle inspiré des sites de rencontres. L'objectif est d'optimiser la mise en relation entre développeurs et recruteurs grâce à des fonctionnalités conviviales et innovantes.

---

## Fonctionnalités

### Gestion des Utilisateurs 👤
- **Inscription distincte** : développeur ou entreprise.
- **Profil public/privé** : option pour masquer les informations sensibles.
- **Rôles** : gestion des droits utilisateur via **ROLE_DEV** et **ROLE_COMPANY**.

### Création et Gestion des Profils/Fiches de postes 📝
- **Développeur** : Profil détaillé avec des informations comme le nom, la localisation, les langages de programmation, etc.
- **Entreprise** : Création de fiches de postes avec des informations comme le titre du poste, la localisation, les technologies recherchées, etc.

### Système de Matching 💡
- Suggestions dynamiques de profils ou de postes selon des critères tels que les langages, le salaire, la localisation, et l'expérience.

### Pages d'Accueil Dynamiques 🏠
- Affichage des profils et des offres les plus populaires pour les développeurs et les entreprises.

### Recherche Avancée 🔍
- Recherche avec des filtres avancés pour les développeurs et les postes (langages, technologies, localisation, etc.).

### Évaluations et Feedbacks ⭐
- Les développeurs peuvent évaluer d'autres développeurs et voir leurs évaluations moyennes.

### Fonctionnalités sociales 💬
- **Favoris** : Ajouter des développeurs ou des fiches de poste à une liste personnelle.
- **Messagerie intégrée** : Communication directe entre développeurs et entreprises.

### Suivi et Analyses 📊
- Statistiques des vues des profils et fiches de poste.
- Top profils et top postes les plus demandés.

### Backup et Déploiement 🔒
- Sauvegarde des données et déploiement via **Docker**.

---

## Technologies utilisées

### Backend 🚀
- **Spring Boot** : Framework Java pour la création de l'application backend.
- **Spring Security** : Gestion de l'authentification et des rôles.
- **Spring Data JPA** : Gestion des données avec une base de données relationnelle (MySQL ou PostgreSQL).

### Frontend 🖥️
- **Thymeleaf** : Moteur de template pour le rendu HTML côté serveur.
- **Bootstrap** : Framework CSS pour le design responsive et rapide.
- **JavaScript** : Légèrement utilisé pour les interactions frontend.

### Base de données 🗃️
- **MySQL** ou **PostgreSQL** : Base de données relationnelle.

### Outils de développement 🛠️
- **Git** : Contrôle de version.
- **Docker** : Containerisation de l'application pour un déploiement facilité.
- **Maven** ou **Gradle** : Gestion des dépendances et de la construction du projet.

---

## Installation

1. **Clonez ce dépôt** :
   ```bash
   git clone [https://github.com/votre-utilisateur/adopteundev.git](https://github.com/BioKobena/jobteaser-clone.git)
