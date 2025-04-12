# 🫐 Wild Blueberry Yield Prediction

Ce projet est basé sur la compétition Kaggle **Wild Blueberry Yield Prediction**. L'objectif est de prédire le rendement de cultures de myrtilles sauvages à partir de variables environnementales comme la température, la pluviométrie, ou encore l’humidité du sol.

# 📊 Objectif
Prédire le rendement (yield) en myrtilles sauvages à partir de plusieurs variables :

Température

Précipitations

Humidité de l’air et du sol

Utilisation d’herbicides et d’engrais

# 📊 Étapes réalisées

1. Importation et exploration des données
Chargement de train.csv et test.csv

Aperçu général : dimensions, types, valeurs manquantes

Visualisation des distributions de features

2. Nettoyage et preprocessing
Vérification des valeurs nulles

Analyse de la corrélation avec la variable cible

Normalisation ou standardisation éventuelle des données

3. Modélisation
Le modèle de régression est entraîné pour prédire la variable cible (yield).
Modèles testés :

XGBoost

RandomForestRegressor

DecisionTreeRegressor

Deep Neural Network

4. Prédiction et évaluation
Prédiction sur l’ensemble de test

Évaluation avec des métriques comme :

MAE (Mean Absolute Error)