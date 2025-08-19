
# 🚢 Titanic Competition - Kaggle

## 📋 Description

Ce repository contient mon travail sur la célèbre compétition **Titanic: Machine Learning from Disaster** de Kaggle. L'objectif est de prédire quels passagers ont survécu au naufrage du Titanic en utilisant les données des passagers (nom, âge, sexe, classe socio-économique, etc.).

> **⚠️ Statut : En développement**  
> Ce projet est actuellement en cours de développement. Certaines fonctionnalités et analyses peuvent être incomplètes.

## 🎯 Objectif

Prédire la survie des passagers du Titanic en analysant les caractéristiques démographiques et socio-économiques des passagers. Il s'agit d'un problème de **classification binaire** : survie (1) ou décès (0).

## 📊 Données

La compétition fournit deux datasets principaux :
- **train.csv** : Données d'entraînement avec les labels de survie
- **test.csv** : Données de test pour les prédictions finales

### Variables principales
- `PassengerId` : Identifiant unique du passager
- `Survived` : Variable cible (0 = décédé, 1 = survécu)
- `Pclass` : Classe du billet (1ère, 2ème, 3ème classe)
- `Name` : Nom du passager
- `Sex` : Sexe
- `Age` : Âge
- `SibSp` : Nombre de frères/sœurs/conjoints à bord
- `Parch` : Nombre de parents/enfants à bord
- `Ticket` : Numéro de billet
- `Fare` : Prix du billet
- `Cabin` : Numéro de cabine
- `Embarked` : Port d'embarquement


## 🔍 Approche méthodologique

1. **Exploration des données (EDA)**
   - Analyse descriptive des variables
   - Visualisation des distributions
   - Identification des valeurs manquantes
   - Analyse des corrélations

2. **Préparation des données**
   - Gestion des valeurs manquantes
   - Encodage des variables catégorielles
   - Ingénierie des features
   - Normalisation/standardisation

3. **Modélisation**
   - Modèles testés : Logistic Regression, Random Forest, XGBoost, etc.
   - Validation croisée
   - Optimisation des hyperparamètres
   - Évaluation des performances

4. **Soumission**
   - Prédictions sur le set de test
   - Format de soumission Kaggle

## 📈 Résultats actuels

> **🚧 En cours de développement**  
> Les résultats seront mis à jour au fur et à mesure de l'avancement du projet.

- **Score Kaggle actuel** : À venir
- **Meilleur modèle** : En cours d'évaluation
- **Accuracy** : À déterminer

## 🚀 Utilisation

### Prérequis
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```


## 📚 Ressources

- [Compétition Kaggle Titanic](https://www.kaggle.com/c/titanic)
- [Documentation Scikit-learn](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)

## 🤝 Contributions

Ce projet étant personnel et éducatif, les contributions ne sont pas attendues. Cependant, les suggestions et retours sont les bienvenus !

## 📝 Licence

Ce projet est à des fins éducatives dans le cadre de l'apprentissage du Machine Learning.

---

**Statut du projet** : 🚧 En développement actif  
**Dernière mise à jour** : Août 2025
