---

# Analyse et Prédiction des Données 🚗

Cette application **Streamlit** interactive est conçue pour analyser des données et prédire des prix de voitures en utilisant un modèle **K-Nearest Neighbors (KNN)**. 

Elle propose une interface conviviale pour explorer, nettoyer, et prédire des données de manière efficace.

---

## Fonctionnalités Principales 🚀

### 🔍 Exploration et Description des Données
- **Téléchargement de fichiers** : Chargez vos données au format CSV pour une exploration interactive.
- **Nettoyage et Préparation des Données** :
  - Remplacement des valeurs manquantes.
  - Conversion automatique des colonnes pour assurer la cohérence des données.
- **Analyse Exploratoire (EDA)** :
  - Statistiques descriptives pour les variables quantitatives et qualitatives.
  - Visualisations telles que histogrammes, boxplots, et diagrammes de corrélation.

### 🔢 Prédiction du Prix
- Modèle KNN pré-entraîné pour prédire le prix d'une voiture en fonction de ses caractéristiques.
- Formulaire utilisateur interactif permettant d'entrer les spécifications d'une voiture et de recevoir une estimation de prix.

### 🎨 Interface Personnalisée
- Arrière-plan dynamique pour une meilleure expérience utilisateur.
- Menu latéral pour naviguer facilement entre les différentes sections :
  - **Description** : Présentation des fonctionnalités.
  - **Documentation** : Guide d'utilisation et informations sur les bibliothèques utilisées.
  - **Prédiction** : Section dédiée à la prédiction de prix.

---

## Prérequis 🛠️

1. **Python 3.8+**.
2. Installation des bibliothèques nécessaires :
   ```bash
   pip install streamlit pandas numpy seaborn scikit-learn joblib
