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
