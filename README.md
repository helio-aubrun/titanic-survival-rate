# titanic-survival-rate

## Contexte
Etant à l'heure où nous faisont ce projet en 1ère année d'une école d'informatique en spécialité IA. Il étant tant que nous attaquions enfin cette parti "IA".

## Nous allons avons clarifier quelques notions d'IA

1 Qu’est ce que l’apprentissage automatique supervisé ?  
L’apprentissage automatique supervisé est une branche de l’apprentissage automatique où le modèle est formé sur un ensemble de données étiquetées. Cela signifie que chaque exemple d’entrée dans l’ensemble de formation est associé à une sortie correcte ou étiquette. Le but est de créer un modèle qui, lorsqu’il est présenté à de nouvelles entrées non vues auparavant, peut prédire avec précision la sortie correspondante.  

2 Qu’est ce que les données étiquetées ou labellisées ?  
Les données étiquetées, également appelées données labellisées, sont des exemples d’observations pour lesquels nous connaissons déjà la réponse correcte. Ces données sont essentielles pour former un modèle d’apprentissage automatique car elles fournissent au modèle des informations sur ce qu’est la bonne réponse pour chaque exemple d’entrée.  

3 En particulier, qu’est ce que la classification supervisée ou méthode de classement ?  
La classification supervisée est une méthode spécifique d’apprentissage automatique supervisé où le but est de prédire une catégorie ou une classe pour une nouvelle observation basée sur un ensemble de caractéristiques. Par exemple, classer des emails comme spam ou pas spam.  

4 Qu’est ce qu’on appelle un modèle d’apprentissage automatique ?  
Un modèle d’apprentissage automatique est une représentation mathématique ou algorithmique d’un processus qui permet à un ordinateur d’apprendre à partir de données. Ce modèle est entraîné sur un ensemble de données d’entraînement et peut ensuite être utilisé pour faire des prédictions sur de nouvelles données.  

5 Qu’est ce que les données d’entraînement ? Qu’est ce que l’entraînement d’un modèle de classification supervisée ?  
Les données d’entraînement sont un ensemble de données utilisé pour former un modèle d’apprentissage automatique. L’entraînement d’un modèle de classification supervisée implique de présenter ces données au modèle afin qu’il puisse apprendre à reconnaître les caractéristiques importantes qui différencient les classes.  

6 Qu’est ce que la donnée cible (ou le target) ?  
La donnée cible (ou le target) est la variable que nous essayons de prédire ou de comprendre à partir des autres variables dans notre jeu de données. Dans le contexte de l'apprentissage automatique, elle est souvent ce que nous voulons prévoir à partir des caractéristiques explicatives.  

7 A quoi sert la phase d’entraînement d’un modèle d’apprentissage automatique ?  
La phase d’entraînement d'un modèle d'apprentissage automatique consiste à utiliser un ensemble de données d'entraînement pour ajuster les paramètres du modèle afin qu'il puisse apprendre à partir de ces données. Pendant cette phase, le modèle apprend à reconnaître les relations entre les caractéristiques explicatives et la donnée cible.  

8 A quoi sert la phase de prédiction d’un modèle d’apprentissage automatique ?  
La phase de prédiction d'un modèle d'apprentissage automatique utilise le modèle formé pendant la phase d'entraînement pour faire des prédictions sur de nouvelles données, c'est-à-dire pour prédire la valeur de la donnée cible pour des observations jamais vues auparavant.  

9 Qu’est ce que le prétraitement des données et pourquoi est-il important à réaliser avant l’entraînement d’un modèle d’apprentissage automatique ?  
Le prétraitement des données est une étape cruciale avant l'entraînement d'un modèle d'apprentissage automatique. Il s'agit de nettoyer et de transformer les données pour améliorer leur qualité et rendre le modèle plus efficace. Le prétraitement peut inclure la suppression des valeurs manquantes, la normalisation des données, la conversion des caractéristiques catégorielles en numériques, etc. C'est important car un mauvais prétraitement peut entraîner des performances médiocres ou même rendre le modèle instable.  

10 Comment l’évaluation d’un modèle d’apprentissage automatique pour une tâche de classification peut-elle se faire ? Etudiez en particulier et seulement, la métrique d’accuracy. En quoi est-elle un indicateur de performance d’un modèle ?  
L'évaluation d'un modèle d'apprentissage automatique pour une tâche de classification peut se faire à travers plusieurs métriques, dont l'accuracy. L'accuracy, ou taux de réussite, est l'une des métriques les plus simples : elle mesure le pourcentage de prédictions correctes par rapport au total des prédictions faites. Cependant, elle peut être trompeuse si les classes sont très déséquilibrées. Une meilleure compréhension des performances d'un modèle peut nécessiter l'utilisation de métriques supplémentaires comme la précision, le rappel, le score F1, ou encore l'AUC-ROC.  

11 Qu’est ce que l’AutoML et pourquoi est-il pertinent pour vous en tant que débutant dans le domaine de l’intelligence artificielle ?  
L'AutoML (Automated Machine Learning) est une approche qui automatise le processus d'entraînement, d'évaluation et de sélection de modèles d'apprentissage automatique. Pour un débutant dans le domaine de l'intelligence artificielle, l'AutoML est pertinent car il simplifie grandement le processus d'apprentissage automatique, permettant ainsi de se concentrer sur l'exploration des problèmes plutôt que sur la complexité technique liée à l'entraînement des modèles.  

12 Qu’est ce qu’un arbre de décision pour la classification supervisée ? Comment fonctionne–t-il ?  
Un arbre de décision pour la classification supervisée est un type de modèle d'intelligence artificielle qui fonctionne en divisant répétitivement l'espace des caractéristiques en sous-espaces jusqu'à ce qu'un critère d'arrêt soit atteint. Chaque nœud interne de l'arbre représente une condition sur une caractéristique, tandis que chaque feuille représente une classe prédite. Lorsqu'on présente une nouvelle observation à l'arbre, il suit les branches en fonction des conditions rencontrées jusqu'à atteindre une feuille, qui indique la classe prédite pour cette observation.  

## Le notebook
Nous nous sommes donc entraîné avec la bibliothèque pycaret sur le dataset du titanic afin de déterminer la chance de survie d'une personne

## Comment lancer le projet
Pour ce projet, le notebook peut être lu avec n'importe quel outil de lecture de notebook ( jupyter, vscode ). La bibliothèque pycaret est à installer et ne marche que sur des versions de python antérieur ( 3.11 )
