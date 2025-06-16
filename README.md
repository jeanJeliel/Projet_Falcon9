# Projet_Falcon9
Prédiction de l’atterrissage du premier étage de la fusée Falcon 9

Objectif du projet

Ce projet vise à prédire si le premier étage de la fusée Falcon 9 atterrira avec succès, ce qui est un élément crucial pour réduire les coûts de lancement de SpaceX. Alors que le coût moyen d’un lancement Falcon 9 est de 62 millions de dollars, les concurrents facturent plus de 165 millions, en grande partie parce que SpaceX réutilise le premier étage de ses fusées.
L’objectif est d’utiliser des techniques de data science et de machine learning pour analyser les données de lancement et prédire la probabilité de réussite de l'atterrissage. Cette analyse pourrait être précieuse pour des entreprises souhaitant collaborer avec ou concurrencer SpaceX.

Objectifs d’apprentissage
Formuler un problème commercial réel sous forme de problème de data science.

Manipuler et transformer des données à l’aide de Python (Pandas, NumPy).

Charger et convertir des fichiers JSON en DataFrames Pandas.

Nettoyer les données et extraire des informations pertinentes.

Construire, évaluer et comparer plusieurs modèles de machine learning.

Créer des visualisations interactives pour explorer les résultats.

Comprendre les facteurs qui influencent le succès de l'atterrissage.

Technologies utilisées
- Python 3
- Pandas / NumPy / Matplotlib / Seaborn
- Scikit-learn (Régression logistique, Arbres de décision, SVM, etc.)
- Plotly Dash – pour le tableau de bord interactif
- Folium – pour les cartes interactives
- API SpaceX RESTful + Web scraping
- Jupyter Notebook

Aperçu du projet

- Collecte des données
- Récupération des données via l’API REST de SpaceX
- Extraction complémentaire via Web scraping
- Nettoyage et préparation
- Normalisation des colonnes, gestion des valeurs manquantes
- Conversion du JSON brut en DataFrame
- Analyse exploratoire
- Visualisation des tendances
- Analyse des sites de lancement, types d’orbites, types de boosters
- Modélisation prédictive
- Création d’un pipeline de machine learning
- Comparaison de plusieurs modèles (régression, arbres, SVM)
- Évaluation des performances avec accuracy, f1-score, confusion matrix
- Visualisation & Dashboard
- Création d’un tableau de bord interactif avec Plotly Dash
- Carte des sites de lancement et succès avec Folium

