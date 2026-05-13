# Employee Attrition Prediction

## Présentation du projet

Ce projet de Machine Learning vise à prédire si un employé est susceptible de quitter l’entreprise (attrition) ou non, à partir de données issues des ressources humaines.

L’objectif est d’aider les équipes RH à anticiper les départs, comprendre les facteurs de turnover, améliorer la satisfaction des employés et renforcer les stratégies de rétention.


## Dataset

Le dataset utilisé provient de IBM HR Analytics :

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Il contient des informations sur les employés telles que :
- âge
- salaire mensuel
- ancienneté
- satisfaction au travail
- heures supplémentaires
- environnement de travail
- niveau de poste...

### Variable cible : **Attrition**
  - `Yes` : l’employé quitte l’entreprise
  - `No` : l’employé reste



## Pipeline du projet

### 1. Compréhension des données
- Analyse de la structure du dataset
- Identification des types de variables
- Statistiques descriptives
- Vérification des valeurs manquantes et doublons

### 2. Analyse exploratoire (EDA)
- Distribution de la variable cible
- Analyse des variables numériques et catégorielles
- Relations entre variables
- Visualisations :
  - Countplots
  - Boxplots
  - Heatmap de corrélation

### 3. Préparation des données
- Suppression des colonnes inutiles
- Encodage des variables catégorielles
- Normalisation des données
- Séparation Train / Test

### 4. Modélisation
Modèles utilisés :
- Régression logistique
- Random Forest
- Gradient Boosting

### 5. Évaluation
Les modèles sont évalués avec :
- Accuracy
- F1-score
- Classification report
- Matrice de confusion



## Résultats

Les facteurs les plus influents sur l’attrition sont :
- heures supplémentaires
- salaire mensuel
- satisfaction au travail
- ancienneté
- équilibre vie professionnelle / vie personnelle

La régression logistique a donné les meilleures performances globales parmi les modèles testés.


## Analyse métier

Les employés présentant :
- une forte charge de travail,
- une faible rémunération,
- une faible satisfaction,

ont une probabilité plus élevée de quitter l’entreprise.

Ces résultats peuvent aider les RH à :
- améliorer les conditions de travail
- réduire les heures supplémentaires,
- augmenter la satisfaction des employés
- renforcer la fidélisation



## Bibliothèques utilisées

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Installation

### 1. Cloner le projet

```bash
git clone https://github.com/az-oumaima/employee-attrition-prediction.git
cd employee-attrition-prediction
```

### 2. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 3. Lancer le notebook

```bash
jupyter notebook
```

---

## Structure du projet

```bash
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
```
