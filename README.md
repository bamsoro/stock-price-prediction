# 📈 Stock Price Prediction — Time Series Modeling with ARIMA, GARCH, and Deep Learning

## 🧠 Présentation du projet

Ce projet de groupe vise à comparer différentes approches pour la prévision de séries temporelles financières (ex : prix d'actions) :

- Une approche **statistique** avec les modèles **ARIMA** et **GARCH**, pour modéliser la tendance et la volatilité.
- Une approche **deep learning** avec un modèle **CNN-LSTM**, capable de capturer des motifs complexes et des dépendances temporelles.

---

## 🧩 Ma contribution

J’ai réalisé la partie **modélisation deep learning**, en développant et entraînant le modèle **CNN-LSTM** sur des données de séries temporelles.  
Cette section comprend la transformation des données, l’architecture du modèle, l'entraînement, et l’analyse des performances.

---

## 📁 Contenu du dépôt

### `Code_complet_arima_garch.Rmd`

Notebook RMarkdown :

- Prétraitement et visualisation des données temporelles
- Modélisation avec ARIMA pour la tendance
- Modélisation avec GARCH pour la volatilité
- Diagnostic des résidus
- Prévision et visualisation des résultats

**Packages R** : `forecast`, `rugarch`, `ggplot2`, `tseries`

---

### `Model_CNN_LSTM_time_series.ipynb`

Notebook Python (contribution personnelle) :

- Transformation des séries en séquences pour apprentissage supervisé
- Extraction de motifs locaux via couches CNN
- Apprentissage des dépendances via LSTM
- Évaluation des performances du modèle sur données de test

**Librairies Python** : `TensorFlow`, `Keras`, `NumPy`, `Pandas`, `Matplotlib`

---

## 🎯 Objectifs

- Comparer méthodes statistiques classiques et modèles profonds
- Tester des approches adaptées à des séries non stationnaires et volatiles
- Proposer une méthodologie hybride, robuste et explicable

---

## 🚀 Pistes d'amélioration

- Intégration d’un modèle Transformer pour séries temporelles
- Ajout d’une interface interactive via Streamlit ou Shiny
- Prévisions probabilistes avec intervalles de confiance

---

## 👤 Auteur

**Sonokoli**  
Étudiant en Data Science à l’ENSAI
Spécialisé en machine learning appliqué aux séries temporelles et à la modélisation prédictive.

---

## 📬 Contact

Pour toute question ou suggestion :  
📧 [sorobamara7@gmail.com]
