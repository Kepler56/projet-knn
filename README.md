# projet-knn

Description du challenge knn : 

Le challenge consiste à construire un modèle de classification ou de régression qui peut prédire la classe ou la valeur d’une nouvelle observation en se basant sur ses voisins les plus proches dans un ensemble de données d’apprentissage. 
Le modèle KNN utilise une mesure de distance pour identifier les k observations les plus proches de la nouvelle observation, pour ensuite utiliser la classe majoritaire de ces k observations afin de prédire la classe de la nouvelle observation.

  -Données mises à notre disposition : 
 Le premier jeu de données ‘data.txt’ est constitué de 7 variables d’entrée et d’une variable de sortie avec 4 classes différentes (0,1,2 ou 3) et contient 1012 exemples. Le deuxième jeu de données ‘preTest.txt’ sera utilisé pour tester notre modèle sur de nouvelles données. Enfin, le troisième jeu de données ‘finalTest.txt’ sera utilisé pour la prédiction des classes de sortie. 

  -Carnet de bord : 
Nous avons réalisé plusieurs tests en utilisant différentes valeurs impaires de k afin de déterminer la meilleure valeur pour notre modèle. Après évaluation de la précision obtenue pour chaque valeur, nous avons choisi k=1 car il a généré la précision la plus élevée de 98.6%, surpassant ainsi les autres valeurs testées. Nous avons donc décidé de conserver cette valeur pour notre mod

Dans l’ensemble, nous avons obtenus des résultats convenables, avec une précision de 98% sur le jeu de données preTest.txt.
