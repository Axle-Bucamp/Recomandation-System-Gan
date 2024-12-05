# 🎬 Moteur de Recommandation Exploratoire par GAN

## 🔍 Contexte du Projet

Ce projet de recherche, réalisé dans le cadre d'un mémoire de fin d'année à l'IAE de Lille, vise à résoudre le problème des "chambres d'écho" dans les systèmes de recommandation de films. L'objectif est de permettre aux utilisateurs de découvrir de nouveaux contenus de manière plus dynamique et moins frustrante.

## 🚀 Approche Scientifique

Utilisation de Réseaux Antagonistes Génératifs (GAN) pour :
- Briser les biais de recommandation traditionnels
- Favoriser la diversité et l'exploration culturelle
- Générer des recommandations plus créatives et inattendues

## 🗂️ Structure du Projet

### Anciens Modèles (Dataset MovieLens Original)
- `Gan_recomandation_WithTimestamp`
- `Demo_recomandation_system`
- `recomandation_system_CalculDiversityOverTime`

### Nouveaux Modèles (25 Millions d'Utilisateurs)
- `Training_Optimized_recommandationGAN`
- `CalculDiversityOverTime_Optimized_recommandationGAN`
- `APP_demo_Optimized_recommandationGAN`

## 🔧 Prérequis et Dépendances

### Anciens Modèles
- Télécharger les datasets MovieLens
- Placer les fichiers dans le dossier racine
- Pré-entraîner un modèle avant les tests

### Nouveaux Modèles
- Pas de dépendances externes
- Scripts auto-suffisants pour le téléchargement des données
- Modèle à entraîner avant utilisation des scripts de test

## 📦 Installation

Je vous recommande d'utiliser google collab qui permet de générer l'environnement nécessaire au lancement de chaque partie.

## 🧪 Utilisation

### Entraînement du Modèle
Notebook : 
- Training_Optimized_recommandationGAN

### Démonstration
une fois le model entrainé extrait et join, notebook : 
- Demo_recomandation_system

## 📊 Méthodologie

Notre approche combine :
- Apprentissage par réseaux antagonistes
- Analyse de la diversité des recommandations
- Optimisation continue du modèle

## 🔬 Recherche Académique

Pour plus de détails, consultez le mémoire inclus dans le dépôt Git. Une lecture attentive et une compréhension approfondie sont recommandées.

⚠️ **Avertissement** : Ce projet est un travail de recherche académique. Une utilisation rigoureuse et éthique est impérative.

## 📄 Licence

[MIT]

## 👥 Contacts

- Auteur : [Bucamp Axle]
- Tuteur académique : [Dominique Crié]
- Institution : IAE de Lille

## 🙏 Contributions

Les contributions, retours et suggestions sont les bienvenus sous forme d'issues ou de pull requests.
