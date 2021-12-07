# Mobile_Price_Classification
Context du projet : un investiseur a lancé sa propre entreprise de téléphonie mobile. Il veut livrer un combat acharné aux grandes entreprises comme Apple, Samsung, etc.
Il ne sait pas estimer le prix des mobiles que son entreprise crée. Dans ce marché concurrentiel de la téléphonie mobile.
Pour résoudre ce problème, il collecte les données de vente des téléphones portables de diverses sociétés.
il veut découvrir une relation entre les caractéristiques d'un téléphone mobile (par exemple : - RAM, mémoire interne, etc.) et son prix de vente.
Dans ce problème, le but n'est pas de prédire le prix réel mais une fourchette de prix indiquant à quel point le prix est élevé(faible,moyen ,elevé,trés elevé)

demarche de travail :

Exploration de donnéés:

analyse de forme (visualisation data  ,types de variables , etude de valeurs manquantes ,visualisation des categories (variables_type=object)
, visualisation de varibles cible(price))

analyse de fond(signification varibles  , relation variables/traget )

analyse plus detailles(relation variables/variables, test d'hypothes)

preprocessing:

(standarisation,repatition de donnees , recuperation des donnees preparés)

modele de base(LinearDiscriminante analysis)

learning curve 

classification:

evaluation des differentes modeles (,LDA,KneighborsClassifier, SVC, DecisonTreeClassifier, RadomForestClassifier)

learning curve et classification report 

choix de meilleure modele(SVC)

Optimisation de modele(GridSearchCV)






