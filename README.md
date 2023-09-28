# PFA_Project_football_result_prediction_using_NN_ML
This is a Neural Network (NN) model for predicting Premier League football results. The "matches.csv" file was extracted using web scraping code. I used pandas to manipulate the data and TensorFlow with Keras to build and train my NN learning model.

I began by importing the data from the "matches.csv" file and performed various cleaning and preprocessing operations. I removed the "comp" and "notes" columns using the "del" function, converted the "date" column to date format using "pd.to_datetime," and categorized the "venue" and "opponent" columns using "astype" and "cat.codes." Furthermore, I transformed the target variable "result" into a numerical form using "np.where" to enable data training.

Using the scikit-learn library, I split my dataset into training and testing sets using "train_test_split." Then, I separated the features from the labels using the "drop" function and indexing.

As for model creation, I opted for an architecture composed of 7 layers using Keras' Sequential class.

# Projet_PFA_foot_result_prediction_using_RNA_ML
c'est un modèle RNA pour la prédiction des résultats de football de la premier League 
Le fichier "matche.csv" a été extrait à partir d'un code de web scraping.
J'ai exploité pandas pour manipuler les données et Tensorflow avec Keras pour bâtir et entraîner mon modèle d'apprentissage en RNA. 
J'ai commencé par importer les données depuis le fichier "matches.csv" et exécuté diverses opérations de nettoyage et de prétraitement.
J'ai éliminé les colonnes "comp" et "notes" en utilisant la fonction "del", converti la colonne "date" au format de date via "pd.to_datetime",
et catégorisé les colonnes "venue" et "opponent" à l'aide de "astype" et "cat.codes".
De plus, j'ai transformé la variable cible "result" en une forme numérique avec "np.where" afin de permettre l'entraînement des données.
Au moyen de la bibliothèque scikit-learn, j'ai fractionné mon ensemble de données en ensembles d'entraînement et de test en recourant à "train_test_split".
Ensuite, j'ai séparé les caractéristiques des étiquettes à l'aide de la fonction "drop" et de l'indexation.
Quant à la création du modèle, j'ai opté pour une architecture composée de 7 couches en utilisant la classe séquentielle de Keras.
