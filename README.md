# SnapShare - Partage tes moments en toute simplicité

## Description

**SnapShare** est une application qui permet de partager des photos entre amis en toute simplicité.  
Les utilisateurs peuvent créer des albums, uploader leurs photos, et partager leurs souvenirs en toute sécurité.

### Fonctionnalités principales

Création d'un compte utilisateur  
Upload de photos et vidéos  
Création d’albums privés ou publics  
Partage sécurisé via un lien privé  
Gestion des permissions (amis, public, privé)

---

## Technologies Utilisées

- **Frontend** : SCSS, PHP, JS
- **Backend** : PHP
- **Base de données** : MySQL

---

## Installation

### Prérequis

Avant de commencer, assure-toi d’avoir installé :

- **Node.js** npm install node
- **MySQL** apt get install mysql

### Étapes d’installation

**Cloner le projet**  
Ouvre un terminal
git clone https://github.com/NotSilverrr/PROJET-GIT-2024.git
cd PROJET-GIT-2024

---

**Installation avec Docker**

Pour simplifier le déploiement de SnapShare, un fichier docker-compose.yml est inclus.

Instructions :

Assure-toi d’avoir installé Docker et Docker Compose.

Dans le répertoire du projet, exécute :

docker-compose up --build

L’application sera disponible sur http://localhost:8080 et la base de données sur localhost:3306.

Le fichier docker-compose.yml crée un conteneur pour l'application PHP et un autre pour MySQL avec les configurations nécessaires.

---

**Comment contribuer**
Les contributions sont les bienvenues. Si tu souhaites améliorer SnapShare, suis ces étapes :

Fork le projet
Crée une branche (git checkout -b feature/ma-fonctionnalite)
Ajoute tes modifications et commits (git commit -m "Ajout de nouvelle fonctionnalité")
Pousse ta branche (git push origin feature/ma-fonctionnalite si c'est la première fois que tu l'utilise), ton push se fera sur les deux remotes :
origin https://github.com/NotSilverrr/PROJET-GIT-2024.git
origin https://github.com/JJJLM/doublepush.git
(visibles avec la commande git remote -v dans le terminal)

Crée une pull request
Merci de consulter le Code of Conduct avant de contribuer.

---

**_Code de conduite_**
Afin de garantir un environnement respectueux et collaboratif, toutes les contributions doivent respecter ces principes :

Faire preuve de respect et de bienveillance envers les autres contributeurs
Utiliser un langage inclusif et éviter tout propos offensant
Éviter les conflits et favoriser la discussion constructive
Respecter les lignes directrices du projet
Tout comportement inapproprié pourra entraîner une exclusion du projet.
