# Projet React - Gestion de Cartes

Ce projet est une application React permettant de créer et de gérer des cartes avec divers attributs tels que le nom, le coût, le type, la description, l'artwork et les mots-clés.

## Présentation Globale du Projet

### Composant Principal

Le composant principal est le cœur de l'application. Il gère l'état global des attributs de la carte et passe ces états en tant que propriétés aux composants enfants chargés de l'affichage et de la configuration.

### Composants

- **Affichage de la Carte** : 
  - Affiche les informations de la carte, incluant le nom, le coût, le type, la description, l'artwork et les mots-clés.
  - Contient des sous-composants pour afficher le coût et l'effet de la carte.

- **Formulaire de Configuration** :
  - Permet de configurer les différents attributs de la carte (nom, coût, type, description, artwork et mots-clés).
  - Contient des champs de saisie et des cases à cocher pour ajuster les attributs de la carte.

### Fonctionnalités

- **Gestion des Attributs** : 
  - Le projet permet de gérer plusieurs attributs de la carte, comme le nom, le coût, le type, la description, l'artwork, et les mots-clés.
  
- **Mise à Jour Dynamique** : 
  - Les modifications apportées via le formulaire de configuration sont immédiatement reflétées dans la carte affichée.

### Structure du Projet

- **Composant Principal** : Gère l'état global de l'application et passe les propriétés aux composants enfants.
  
- **Point d'Entrée de l'Application** : Rende le composant principal dans le DOM.

- **Affichage de la Carte** : 
  - Affiche les informations détaillées de la carte.
  - Utilise des sous-composants pour afficher des parties spécifiques comme le coût et l'effet.

- **Formulaire de Configuration** : 
  - Interface utilisateur pour modifier les attributs de la carte.
  - Inclut des sous-composants pour des champs de saisie spécifiques tels que le coût, le nom et les mots-clés.

Ce projet offre une base solide pour développer une application de gestion de cartes avec une interface utilisateur interactive et dynamique.
