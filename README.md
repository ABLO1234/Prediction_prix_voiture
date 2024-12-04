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
   ```
3. Assurez-vous d’avoir le fichier du modèle pré-entraîné (`model_prediction`) dans le répertoire principal du projet.

---

## Installation et Exécution 🚀

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/projet-prediction-prix.git
   ```
2. Accédez au dossier du projet :
   ```bash
   cd projet-prediction-prix
   ```
3. Lancez l'application Streamlit :
   ```bash
   streamlit run app.py
   ```

---

## Utilisation de l'Application 🖥️

1. **Section Description** :
   - Lisez les fonctionnalités et les caractéristiques du projet.
   - Explorez la base de données et comprenez ses attributs.

2. **Section Documentation** :
   - Accédez au guide complet des fonctionnalités et à un aperçu du code source.
   - Consultez les explications sur le nettoyage et la préparation des données.

3. **Section Prédiction** :
   - Remplissez les champs avec les spécifications de la voiture.
   - Cliquez sur le bouton **Prédire** pour recevoir une estimation instantanée.

---

## Structure du Projet 📂

- `app.py` : Script principal contenant le code de l'application Streamlit.
- `model_prediction` : Fichier du modèle KNN pré-entraîné pour les prédictions.
- `README.md` : Documentation du projet.

---

## Exemple de Données 📊

Voici un aperçu des colonnes utilisées dans la base de données :

| Colonne              | Description                                             |
|----------------------|---------------------------------------------------------|
| `symboling`          | Indicateur de risque d'assurance                        |
| `normalized-losses`  | Pertes normalisées                                      |
| `make`               | Fabricant de la voiture                                 |
| `fuel-type`          | Type de carburant                                       |
| `wheel-base`         | Empattement                                             |
| `length`, `width`    | Dimensions de la voiture                                |
| `horsepower`         | Puissance de la voiture                                 |
| `price`              | Prix cible (à prédire)                                  |

---

## Contributions 🖇️

Les contributions sont les bienvenues ! Si vous souhaitez signaler un problème ou ajouter des fonctionnalités :
1. Forkez le projet.
2. Créez une branche pour vos modifications.
3. Soumettez une **pull request** avec une description claire de vos changements.

---

## Auteur ✍️

- **Abdoulaye Tangara**  
  Étudiant en économie quantitative, passionné par les solutions interactives et l'application de l'intelligence artificielle dans le domaine économique.

---

## Licence 📜

Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus de détails.

---

Si vous avez des questions ou suggestions, n'hésitez pas à me contacter ! 🚀
