*English version below*

**Projet 10 de la formation Data Analyst Openclassrooms : CREATION D'UN ALGORITHME DE DETECTION DE FAUX BILLETS**

Projet réalisé sous python via un notebook Jupyter

Contexte: L'ONCFM, qui a pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros, souhaite créer un algorithme de détection automatique de faux billets.

Mission : A l'aide d'un jeu de données comportant les valeurs de différentes caractéristiques géométriques de billets ainsi que leur caractère 'vrai' ou 'faux', j'ai entraîné un algorithme afin qu'il reconnaisse des faux billets lorsque je lui présente de nouvelles données.

Sommaire du notebook:

1. **Importation et nettoyage des données**
    - 1.1. Détection des outliers
    - 1.2. Analyse des valeurs manquantes
        - 1.2.1. Imputation par régression linéaire
        - 1.2.2. Imputation par KNeighborsRegressor

2. **Analyse descriptive des données**

3. **Analyse en composantes principales**

4. **Prédiction par la méthode du K-means**
    - 4.1. Recherche du nombre de clusters optimal
    - 4.2. Entraînement de l'algorithme et résultats
    - 4.3. Représentation graphique en 2 dimensions via l'ACP

5. **Prédiction par régression logistique**

6. **Prédiction par la méthode du SVM**

7. **Prédiction par la méthode de la forêt aléatoire**

8. **Analyse prédictive avec le modèle de régression logistique**
    - 8.1. Définition d'une fonction de prédiction
    - 8.2. Prédiction des nouveaux billets


-------------------------------------------------------------------------------------------------


**Project 10 of the OpenClassrooms Data Analyst Program: CREATING A COUNTERFEIT DETECTION ALGORITHM**

Project executed with Python via a Jupyter Notebook

Context: The ONCFM, with the goal of implementing methods for the identification of counterfeit euro banknotes, aims to create an algorithm for the automatic detection of counterfeit banknotes.

Objective: Using a dataset containing values of various geometric features of banknotes along with their 'genuine' or 'counterfeit' status, I trained an algorithm to recognize counterfeit banknotes when presented with new data.

Notebook Outline:

1. **Data Import and Cleaning**
    - 1.1. Outliers Detection
    - 1.2. Analysis of Missing Values
        - 1.2.1. Imputation using Linear Regression
        - 1.2.2. Imputation using KNeighborsRegressor

2. **Descriptive Data Analysis**

3. **Principal Component Analysis (PCA)**

4. **Prediction using the K-means Method**
    - 4.1. Searching for the Optimal Number of Clusters
    - 4.2. Training the Algorithm and Results
    - 4.3. 2D Graphical Representation via PCA

5. **Prediction using Logistic Regression**

6. **Prediction using SVM Method**

7. **Prediction using Random Forest Method**

8. **Predictive Analysis with the Logistic Regression Model**
    - 8.1. Definition of a Prediction Function
    - 8.2. Prediction of New Banknotes
