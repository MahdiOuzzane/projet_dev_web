# Plateforme de Location de Salles de Réunion et d'Événements

## Description du Projet
Ce projet consiste à concevoir et développer une plateforme qui permet :  
- Aux **propriétaires** de proposer des salles de réunion ou d'événements à la location.  
- Aux **clients** de consulter et réserver ces salles.  

La plateforme inclura :  
- Un système de gestion des utilisateurs avec différents rôles.  
- Une interface intuitive pour le frontend.  
- Une API REST pour le backend.  

---

## Rôles des Utilisateurs

1. **Visiteur** :  
   - Peut consulter les salles disponibles sans créer de compte.  

2. **Client** :  
   - Peut réserver des salles après avoir créé un compte.  

3. **Propriétaire** :  
   - Peut ajouter, modifier ou supprimer les salles proposées à la location.  
   - Peut consulter les avis laissés par les clients.  

4. **Administrateur** :  
   - Peut gérer les utilisateurs (clients et propriétaires).  
   - Peut gérer et modérer les salles proposées.  

---

## Fonctionnalités Attendues

### Frontend (React ou EJS)
- **Page d'accueil** :  
  Affiche les salles disponibles.  

- **Formulaire d'inscription et d'authentification** :  
  Permet aux utilisateurs de créer un compte et de se connecter.  

- **Interface Client** :  
  - Rechercher et filtrer les salles.  
  - Visualiser les salles sur une carte interactive (Google Maps API, Mapbox, etc.).  
  - Réserver une salle.  
  - Consulter l'historique des réservations.  
  - Laisser des avis et des commentaires après une réservation.  

- **Interface Propriétaire** :  
  - Ajouter une nouvelle salle avec description, capacité, prix et localisation géographique.  
  - Modifier ou supprimer ses salles existantes.  
  - Consulter les avis et commentaires laissés par les clients.  
  - Visualiser les statistiques globales : nombre de réservations, revenus générés, avis reçus.  

- **Interface Administrateur** :  
  - Gérer les comptes utilisateurs (activation, désactivation).  
  - Supprimer des annonces si nécessaire.  
  - Superviser et modérer les avis et commentaires.  

---

### Backend (Express.js)
- **API RESTful** :  
  - Gestion de l'authentification (inscription, connexion).  
  - Opérations CRUD sur les salles.  
  - Réservation de salles.  
  - Gestion des utilisateurs selon leurs rôles.  
  - Fourniture des données de localisation des salles.  
  - Gestion des avis et commentaires des clients.  
  - Fourniture de statistiques globales (nombre de réservations, revenus générés).  

---

### Base de Données (MongoDB ou MySQL)
La base de données stockera les informations suivantes :  
- **Utilisateurs** : Rôles, comptes et informations personnelles.  
- **Salles** : Description, capacité, prix, localisation, propriétaire.  
- **Réservations** : Détails des réservations effectuées.  
- **Avis et Commentaires** : Retours des clients sur les salles.  

---

## Contraintes Techniques
- Utilisation de **Express.js** pour le backend.  
- Développement du frontend avec **React** ou **EJS**.  
- Authentification sécurisée avec **JWT (JSON Web Tokens)**.  
- Respect des bonnes pratiques de développement :  
  - Modularité du code.  
  - Validation des données côté serveur et client.  
  - Sécurisation des routes et des API.  
- Intégration d'une API de localisation pour afficher les salles sur une carte interactive.  

---

## Livrables
1. **Code Source Complet** : Contient le frontend et le backend.  
2. **Documentation** :  
   - Explication de l'architecture du projet.  
   - Étapes pour installer et configurer le projet.  
3. **Schéma de Base de Données** : Représentation des relations entre les entités.  
4. **Présentation Finale** : Démonstration complète de l'application.  

---

Ce projet est conçu pour offrir une expérience fluide et performante à la fois pour les propriétaires et les clients, tout en respectant les normes modernes de développement logiciel.
