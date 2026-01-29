# 🎬 Box Office Prediction Engine

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Regression-orange?style=flat&logo=scikit-learn)

> **Projet Portfolio** (Data Science).
> Prédiction de revenus cinématographiques pour optimiser les investissements d'un studio.

## 🎯 Objectif & Contexte

Dans l'industrie du cinéma, l'intuition ne suffit plus. L'objectif de ce projet est de construire un modèle capable de **prédire les recettes mondiales** (`Gross Revenue`) d'un film en fonction de son budget et de sa popularité attendue.

Ce type d'approche quantitative est directement transférable à d'autres domaines performatifs, comme l'analyse sportive (prédiction de valeur marchande ou de performance joueurs).

## 📊 Méthodologie

1.  **Data Cleaning :** Traitement d'un dataset de ~6800 films (Nettoyage des données manquantes, gestion des devises).
2.  **EDA (Exploratory Data Analysis) :** Mise en évidence de la corrélation forte ($0.74$) entre Budget et Recettes.
3.  **Modélisation :** Entraînement d'une **Régression Linéaire** pour établir une baseline prédictive.

## 📈 Résultats

* **R² Score :** 0.64 (Le modèle explique 64% de la variance des recettes).
* **Insight :** Le nombre de votes (engagement public) est un facteur prédictif critique, souvent plus que la note critique elle-même.

## 🛠️ Installation

1.  Cloner le projet :
    ```bash
    git clone [git clone https://github.com/yanis-chergui/box-office-prediction.git](https://github.com/yanis-chergui/box-office-prediction.git)
    ```
2.  Installer les dépendances :
    ```bash
    pip install -r requirements.txt
    ```
3.  Lancer l'analyse :
    ```bash
    jupyter notebook cinema_analysis.ipynb
    ```
