# Prédiction de l’Attrition des Employés

## Objectif

Dans ce projet, on essaie de prédire si un employé va quitter son entreprise ou non.

Le but est d’aider les ressources humaines à comprendre les facteurs qui influencent les départs et à mieux anticiper les situations à risque.

## Données utilisées

Le dataset contient des informations sur les employés :

- âge  
- salaire  
- poste  
- heures supplémentaires  
- satisfaction au travail  
- ancienneté  

La variable cible est l’attrition :
- Yes : l’employé quitte l’entreprise  
- No : l’employé reste  


## Démarche du projet

### 1. Compréhension des données
Chargement du dataset et étude des variables.

### 2. Analyse exploratoire
On analyse :
- la répartition de la variable cible  
- l’impact des heures supplémentaires  
- la relation entre salaire et attrition  
- les corrélations entre variables  

### 3. Préparation des données
- suppression des colonnes inutiles  
- encodage des variables catégorielles  
- normalisation des données  
- séparation train/test  

### 4. Modélisation
On teste plusieurs modèles :
- Régression Logistique  
- Random Forest  
- Gradient Boosting  

### 5. Évaluation
On compare les modèles avec :
- accuracy  
- F1-score  
- matrice de confusion  
- ROC-AUC  

### 6. Interprétation
On analyse les facteurs les plus importants dans le départ des employés.

## Résultats

Les modèles d’ensemble comme Random Forest et Gradient Boosting donnent les meilleurs résultats.

Les facteurs principaux qui influencent l’attrition sont :
- les heures supplémentaires  
- le salaire  
- la satisfaction au travail  
- l’ancienneté  

## Outils utilisés
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
          
## Conclusion

Ce projet montre comment le machine learning peut aider à comprendre les départs des employés et à améliorer la prise de décision en entreprise.
