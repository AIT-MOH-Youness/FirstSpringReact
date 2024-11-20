# Gestion des Comptes - FirstSpringReact

Ce projet est une application web de gestion des comptes bancaires développée avec Spring Boot (backend) et React (frontend).  Elle permet de créer, consulter, mettre à jour et supprimer des comptes, ainsi que d'effectuer des opérations comme les dépôts et les retraits.

## Fonctionnalités

* **CRUD des comptes:** Création, lecture, mise à jour et suppression des comptes bancaires.
* **Gestion des opérations:** Effectuer des dépôts et des retraits sur les comptes.
* **Consultation du solde:** Afficher le solde actuel d'un compte.
* **Persistance des données:** Utilisation d'une base de données H2 en mémoire (pour le développement et les tests).  Peut être facilement configuré pour utiliser une autre base de données.
* **API REST:** Spring Boot expose une API REST pour la gestion des comptes et des opérations.
* **Interface utilisateur React:** Une interface utilisateur interactive développée avec React pour interagir avec l'API backend.
* **Validation des données:**  Validation des entrées utilisateur côté backend et frontend pour garantir l'intégrité des données.

## Technologies utilisées

* **Backend:**
    * Spring Boot: Framework pour la création d'applications Java.
    * Spring Data JPA: Simplifie l'accès aux données avec JPA.
    * Spring Web: Pour la création de l'API REST.
    * H2 Database: Base de données en mémoire pour le développement.
* **Frontend:**
    * React: Bibliothèque JavaScript pour la création d'interfaces utilisateur.
    * Axios: Client HTTP pour les appels API.
    * Material UI (facultatif):  Bibliothèque de composants React pour l'interface utilisateur.
* **Autres:**
    * Maven: Gestion des dépendances backend.
    * NPM/Yarn: Gestion des dépendances frontend.
    * Lombok (facultatif):  Simplifie le code Java en générant automatiquement des méthodes comme les getters, setters, etc.

## Architecture

L'application suit une architecture client-serveur classique. Le frontend React communique avec le backend Spring Boot via une API REST.  Le backend gère la logique métier et la persistance des données.


## Installation et exécution

1. **Cloner le repository :**

```bash
git clone https://github.com/AIT-MOH-Youness/FirstSpringReact.git


2. **Cloner le repository :**

```bash
git clone https://github.com/AIT-MOH-Youness/FirstSpringReact.git
