# Projet React - Gestion de Cartes

Ce projet est une application React permettant de créer et de gérer des cartes avec divers attributs tels que le nom, le coût, le type, la description, l'artwork et les mots-clés.

## Présentation Globale du Projet

### Composant Principal : `App.jsx`

Le composant `App.jsx` est le cœur de l'application. Il gère l'état global des attributs de la carte et passe ces états en tant que propriétés aux composants enfants `Card` et `Config`.

### Composants

- **Card.jsx** : Affiche les informations de la carte, incluant le nom, le coût, le type, la description, l'artwork et les mots-clés.
  
- **CardCost.jsx** : Affiche le coût de la carte.
  
- **CardEffect.jsx** : Affiche la description de l'effet de la carte ainsi que les mots-clés actifs.

- **Config.jsx** : Formulaire permettant de configurer les différents attributs de la carte (nom, coût, type, description, artwork et mots-clés).
  
- **ConfigCost.jsx** : Champ de saisie pour configurer le coût de la carte.
  
- **ConfigKeywords.jsx** : Liste de cases à cocher pour configurer les mots-clés de la carte.
  
- **ConfigName.jsx** : Champ de saisie pour configurer le nom de la carte.

### Fonctionnalités

- **Gestion des Attributs** : Le projet permet de gérer plusieurs attributs de la carte, comme le nom, le coût, le type, la description, l'artwork, et les mots-clés.
  
- **Mise à Jour Dynamique** : Les modifications apportées via le formulaire de configuration sont immédiatement reflétées dans la carte affichée.

### Structure du Projet

- **App.jsx** : Composant principal gérant l'état global.
  
- **main.jsx** : Point d'entrée de l'application, rendant le composant `App`.
  
- **Card.jsx** : Affichage de la carte.
  
- **CardCost.jsx** : Affichage du coût de la carte.
  
- **CardEffect.jsx** : Affichage des effets et des mots-clés de la carte.
  
- **Config.jsx** : Formulaire de configuration des attributs de la carte.
  
- **ConfigCost.jsx** : Champ de saisie pour le coût.
  
- **ConfigKeywords.jsx** : Configuration des mots-clés.
  
- **ConfigName.jsx** : Champ de saisie pour le nom.

Ce projet offre une base solide pour développer une application de gestion de cartes avec une interface utilisateur interactive et dynamique.
