# 📈 Stock Price Prediction — Time Series Modeling with ARIMA, GARCH, and Deep Learning

## 🧠 Contexte et problématique métier

Dans un contexte où la volatilité des marchés financiers est une source majeure d'incertitude pour les investisseurs et analystes, la capacité à anticiper les évolutions de prix devient un atout stratégique.  
Ce projet vise à **comparer différentes approches de prévision de séries temporelles financières**, en particulier pour la prédiction du prix d’actions, afin de mieux comprendre et exploiter les dynamiques de marché.

Deux axes ont été explorés :

- Des méthodes **statistiques classiques** (ARIMA, GARCH) reconnues pour leur robustesse sur des séries linéaires et stationnaires.
- Une approche **deep learning** (CNN-LSTM), capable de détecter des schémas non linéaires et de capturer les relations complexes entre les données temporelles.

Ce travail s’inscrit dans une logique métier de :
- **gestion du risque**,  
- **construction de signaux d’alerte**,  
- **pilotage de portefeuille algorithmique**,  
- ou encore **optimisation des décisions d’investissement**.

---

## 🧩 Ma contribution

J’ai assuré la **conception, l’implémentation et l’analyse** de la partie deep learning du projet, en développant un modèle **hybride CNN-LSTM** :

- Préparation et structuration des données temporelles sous forme séquentielle.
- Construction de l’architecture combinant convolution (extraction locale de patterns) et LSTM (apprentissage du temps long).
- Évaluation des performances du modèle sur des séries financières simulées et réelles.

---

## 📁 Contenu du dépôt

### `Code_complet_arima_garch.Rmd`

Notebook RMarkdown pour l'approche statistique :

- Nettoyage et visualisation des séries temporelles
- Modélisation de la tendance (ARIMA)
- Modélisation de la volatilité (GARCH)
- Diagnostic des résidus
- Prévisions et visualisations comparatives

**Packages R utilisés** : `forecast`, `rugarch`, `tseries`, `ggplot2`

---

### `Model_CNN_LSTM_time_series.ipynb`

Notebook Python (contribution personnelle) :

- Transformation des séries en fenêtres temporelles
- Extraction de motifs via couches CNN
- Apprentissage séquentiel via LSTM
- Évaluation de la performance du modèle (MSE, RMSE, visualisation des prédictions)

**Librairies Python** : `TensorFlow`, `Keras`, `NumPy`, `Pandas`, `Matplotlib`

---

## 🎯 Objectifs du projet

- Explorer les complémentarités entre approches statistiques et apprentissage profond.
- Comparer la précision et la robustesse des modèles sur des données volatiles.
- Proposer un socle de modélisation réutilisable dans des environnements data-driven, à des fins de scoring, d’alerte ou d’aide à la décision.

---

## 🧭 Cas d’usage métier possibles

- Anticipation des mouvements boursiers dans un système de trading algorithmique.
- Estimation de la volatilité pour la tarification d’options ou de produits dérivés.
- Construction de scores d’instabilité pour la gestion des risques financiers.
- Intégration dans des tableaux de bord d’aide à l’investissement.

---

## 🚀 Pistes d'amélioration

- Intégration de modèles récents comme **Informer**, **N-BEATS** ou **Transformer** pour séries temporelles.
- Test sur données multi-sources (indicateurs macro, sentiment analysis).
- Industrialisation du pipeline avec Streamlit ou FastAPI pour création d’une interface utilisateur.
- Prévision probabiliste avec **intervalle de confiance**.

---

## 👤 Auteur

**Sonokoli**  
Étudiant en 3e année à l’ENSAI — Spécialisation Data Science et Statistique Appliquée  
Projet réalisé sous la supervision de **Youssef Esstafa** dans le cadre d’un travail de groupe

---

## 📬 Contact

📧 sorobamara7@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/bamarasoro/)

---

