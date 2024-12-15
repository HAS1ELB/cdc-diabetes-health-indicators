# Projet : Analyse et Prédiction sur le Dataset des Indicateurs de Santé

## Description du projet

Ce projet consiste à effectuer une analyse exploratoire des données (EDA), un nettoyage des données, une modélisation prédictive et une évaluation des modèles pour un dataset d'indicateurs de santé liés au diabète.

## Structure du répertoire

```
├── .gitattributes
├── EDA
│   ├── analyse_statistique.ipynb
│   ├── data_cleaning.ipynb
│   ├── data_loading.ipynb
│   └── data_visualisation.ipynb
├── data
│   ├── balanced_clean_data.csv
│   ├── clean_data.csv
│   ├── clean_data_with_features.csv
│   └── data.csv
├── dataset_feature_description.md
├── modelisation_predictive
│   ├── improved_prediction_evaluation.ipynb
│   ├── nv_caracteristiques.ipynb
│   └── prediction_evaluation.ipynb
├── models
│   ├── dt_model.pkl
│   ├── lr_model.pkl
│   └── tfmodel.keras
└── requirements.txt
```

## Contenu

### EDA (Analyse Exploratoire des Données)

- **analyse_statistique.ipynb** : Analyse des statistiques descriptives pour les variables continues et catégoriques.
- **data_cleaning.ipynb** : Nettoyage des valeurs aberrantes, encodage des variables, équilibrage du dataset.
- **data_loading.ipynb** : Chargement des données depuis des fichiers sources.
- **data_visualisation.ipynb** : Visualisation graphique des données pour détecter des tendances et corrélations.

### Données

- **data.csv** : Données brutes.
- **clean_data.csv** : Données nettoyées.
- **balanced_clean_data.csv** : Données nettoyées et équilibrées.

### Modélisation prédictive

- **improved_prediction_evaluation.ipynb** : Évaluation des modèles optimisés.
- **nv_caracteristiques.ipynb** : Ajout de nouvelles caractéristiques pour améliorer les prédictions.
- **prediction_evaluation.ipynb** : Évaluation des performances des modèles initiaux.

### Modèles

- **dt_model.pkl** : Modèle prédictif basé sur les arbres de décision.
- **lr_model.pkl** : Modèle de régression logistique.
- **tfmodel.keras** : Modèle entrainé avec TensorFlow.

### Autres fichiers

- **dataset_feature_description.md** : Documentation des différentes caractéristiques (colonnes) du dataset.
- **requirements.txt** : Liste des dépendances Python nécessaires au projet.

## Installation

1. Cloner ce répertoire :

```bash
git clone https://github.com/HAS1ELB/cdc-diabetes-health-indicators
```

2. Installer les dépendances :

```bash
pip install -r requirements.txt
```

## Utilisation

1. Explorer les notebooks dans le répertoire `EDA` pour comprendre les données et les transformations appliquées.
2. Lancer les notebooks dans `modelisation_predictive` pour reproduire les résultats prédictifs.

## Contributeurs

- **EL BAHRAOUI HASSAN , Dehbi kamal , El bachar walid**
