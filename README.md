# Gestion intelligente de la consommation énergétique

[Accéder à l'application Streamlit](https://emmanuelsakpleto.streamlit.app/)

## Présentation du projet

Ce projet vise à analyser, prédire et optimiser la consommation énergétique d'une habitation résidentielle à partir de données issues de capteurs et de la météo locale. Il combine des approches de data science supervisée et non supervisée, ainsi que des techniques d'apprentissage par renforcement pour proposer des stratégies d'optimisation.

## Objectifs
- Prétraiter et explorer les données pour comprendre les tendances et la structure temporelle de la consommation.
- Construire des modèles de prévision supervisée (régression linéaire, forêts aléatoires, XGBoost).
- Identifier des profils d’usage par clustering (KMeans) et réduction de dimension (PCA).
- Détecter des anomalies de consommation (Isolation Forest).
- Proposer une base d’analyse pour l’optimisation via l’apprentissage par renforcement (Q-learning).

## Structure du projet
- `Streamlit/app_streamlit.py` : Application web interactive pour l’exploration et la prédiction.
- `ML_Energy_Appliances.ipynb` : Notebook complet d’analyse, modélisation et visualisation.
- `Dataset/energydata_complete.xlsx` : Jeu de données principal.
- `requirements.txt` : Dépendances Python nécessaires.

## Installation et exécution locale
1. Clonez le dépôt ou téléchargez les fichiers.
2. Installez les dépendances :
   ```sh
   pip install -r requirements.txt
   ```
3. Lancez l’application Streamlit :
   ```sh
   streamlit run Streamlit/app_streamlit.py
   ```

## Résumé des analyses (voir le notebook pour le détail)
- Nettoyage et enrichissement temporel des données.
- Visualisations : tendances horaires, journalières, mensuelles, corrélations.
- Modélisation supervisée :
  - Régression linéaire
  - Random Forest
  - XGBoost (meilleur compromis après tuning)
- Clustering (KMeans) et analyse de profils d’usage.
- Détection d’anomalies (Isolation Forest).
- Optimisation par apprentissage par renforcement (Q-learning).

## Liens utiles
- [Application Streamlit en ligne](https://emmanuelsakpleto.streamlit.app/)

## Auteur
Emmanuel Sakpleto
