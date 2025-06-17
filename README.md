# ❤️ Prédiction des Maladies Cardiaques avec Machine Learning

## 📌 Introduction

Les maladies cardiovasculaires figurent parmi les principales causes de mortalité dans le monde. Ce projet vise à démontrer comment l’apprentissage automatique peut être utilisé pour prédire efficacement la présence de maladies cardiaques en se basant sur des données médicales.

---

## 🎯 Objectif

Développer un modèle de classification capable de prédire si un patient est susceptible de souffrir d'une maladie cardiaque, à partir de ses caractéristiques cliniques.

---

## 🗂️ Données

- **Source** : [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Description** : Le jeu de données contient des variables telles que :
  - `age`, `sex`, `cp` (type de douleur thoracique), `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, etc.
  - **Variable cible** : `target` (0 = pas de maladie, 1 = maladie cardiaque détectée)

---

## 🔍 Méthodologie

### 1. Prétraitement des données
- Nettoyage, gestion des valeurs manquantes
- Détection et gestion des valeurs aberrantes
- Normalisation des données
- Encodage des variables catégorielles si nécessaire

### 2. Analyse exploratoire (EDA)
- Visualisation des distributions des variables
- Analyse des corrélations
- Étude des relations entre variables et cible

### 3. Modélisation
- Algorithmes utilisés :
  - Régression Logistique
  - K-Nearest Neighbors (KNN)
  - Forêt Aléatoire (Random Forest)
- Validation croisée
- Optimisation des hyperparamètres

### 4. Évaluation
- Métriques de performance :
  - Précision
  - Rappel
  - F1-Score
  - Matrice de confusion
  - Courbe ROC & AUC

---

## 📈 Résultats

Les différents modèles ont été comparés en fonction de leur performance globale. La Forêt Aléatoire s'est montrée la plus performante en termes de compromis entre précision et rappel.

---

## 🛠️ Stack Technique

- Python 3.x
- Jupyter Notebook
- Bibliothèques :
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn

---

## 🚀 Exécution du projet

1. Cloner le dépôt :
```bash
git clone https://github.com/<votre-utilisateur>/heart-disease-prediction.git
cd heart-disease-prediction
