# Prévision des Crédits Logement

## Introduction

Ce projet de data mining vise à développer un modèle de prédiction des crédits des logements en utilisant des techniques de machine learning. La prédiction des crédits immobiliers est un aspect crucial dans le domaine financier, permettant aux institutions financières d'évaluer le risque de prêter de l'argent pour l'achat d'une propriété.

## Contenu

### Dataset

Le jeu de données `train.csv` est utilisé dans ce projet pour l'entraînement et l'évaluation du modèle. Il contient des informations pertinentes sur les demandes de crédit immobilier, comprenant diverses caractéristiques telles que les revenus, l'historique de crédit, la situation familiale, etc.

### Prévision des Crédits Logement (Prétraitement et Modèles)

Le fichier Jupyter Notebook `Prévision_des_crédits_logement.ipynb` contient le code source du projet. Il est divisé en deux parties principales :

1. **Prétraitement des Données :**
   - Exploration et analyse des données.
   - Nettoyage des données, gestion des valeurs manquantes, etc.
   - Transformation des variables catégorielles et numériques.

2. **Entraînement des Modèles :**
   - Séparation du jeu de données en ensembles d'entraînement et de test.
   - Entraînement de modèles de prédiction, notamment la régression logistique.
   - Évaluation des modèles avec des métriques appropriées.

### Modèle Sauvegardé

Le fichier `logistic_regression_model.pkl` représente le modèle de régression logistique entraîné avec les données fournies. Ce modèle a été sélectionné en raison de sa performance, mesurée par des métriques telles que l'accuracy.

## Utilisation

Vous pouvez utiliser le modèle sauvegardé pour effectuer des prédictions sur de nouvelles données. Assurez-vous d'avoir les bibliothèques Python nécessaires installées et utilisez le fichier Jupyter Notebook pour charger le modèle et effectuer des prédictions.
#DataMining
#MachineLearning
#Python
#GitHub
#Jupyter
#RandomForest
#LogisticRegression
