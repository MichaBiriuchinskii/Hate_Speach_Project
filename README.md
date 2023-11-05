# Projet de Détection de Discours Haineux

Bienvenue dans le projet de détection de discours haineux ! Ce référentiel contient le code, les documents et le rapport de notre projet visant à détecter le discours haineux et abusif dans les messages en ligne.

## Aperçu

Ce projet repose sur un modèle de détection de discours haineux élaboré par des chercheurs, que nous avons adapté à un jeu de données en russe. Notre objectif est de contribuer à la création d'un environnement numérique plus sûr et respectueux pour les utilisateurs de la langue russe en ligne.


## Contenu

Ce référentiel est organisé de la manière suivante :

/Code : Ce répertoire contient le code source utilisé pour le prétraitement des données, l'entraînement du modèle, l'évaluation et la génération des résultats.

/Library : Ce dossier contient un rapport détaillé de notre expérience, y compris la méthodologie, les résultats et les conclusions.

/dataset_raw : Le dossier "dataset_raw" contient les tableaux csv avant et après l'annotation manuelle, les matériaux sur l'évaluation de l'annotation (gold).

## Comment utiliser ce projet

Pour utiliser ce projet, suivez les étapes suivantes :

1. Clonez ce référentiel sur votre machine locale en utilisant la commande git clone.

2. Accédez au répertoire /Code pour trouver le code source.

3. Suivez les instructions dans le fichier README du répertoire /Code pour exécuter le code, prétraiter les données, entraîner le modèle, et évaluer les résultats.

4. Vous pouvez également explorer les documents et le rapport dans les répertoires /Library et /dataset_raw pour une compréhension approfondie de notre expérience.

The main dataset can be seen with labels information as follows:

- HS : hate speech label;
- Abusive : abusive language label;
- HS_Individual : hate speech targeted to an individual;
- HS_Group : hate speech targeted to a group;
- HS_Religion : hate speech related to religion/creed;
- HS_Race : hate speech related to race/ethnicity;
- HS_Physical : hate speech related to physical/disability;
- HS_Gender : hate speech related to gender/sexual orientation;
- HS_Gender : hate related to other invective/slander;
- HS_Weak : weak hate speech;
- HS_Moderate : moderate hate speech;
- HS_Strong : strong hate speech.

## Remerciements
  
Nous tenons à remercier les [chercheurs](https://aclanthology.org/W19-3506/) dont le modèle initial a servi de base à ce projet, ainsi que tous ceux qui contribuent à la création d'un environnement en ligne plus inclusif et respectueux.


