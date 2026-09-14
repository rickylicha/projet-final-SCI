# Projet final en science des données

Ce dépôt contient mon projet final réalisé dans le cadre du cours **SCI 1402 - Projet en science des données**.

Le projet a pour objectif de mettre en pratique les différentes compétences acquises au cours du programme de science des données. J'ai choisi de travailler sur des données de compétitions internationales de patinage artistique.

La question principale de mon analyse est :

**Est-ce que les juges de patinage artistique donnent des scores plus élevés aux patineurs de leur propre pays ?**

Pour répondre à cette question, j'ai analysé les scores accordés par les juges lors de plusieurs compétitions internationales et ajouté manuellement des informations sur la nationalité des juges.

## Compétences utilisées

Ce projet m'a permis d'utiliser plusieurs compétences acquises durant le programme :

- utilisation du langage **R** et du logiciel **RStudio**;
- importation, préparation, fusion et agrégation de données;
- analyse exploratoire et visualisation de données;
- réalisation et interprétation de tests statistiques, notamment un **test t**;
- création et interprétation d'un **modèle linéaire**;
- création de cartes géographiques avec R;
- création d'un rapport reproductible avec **R Markdown**;
- présentation et interprétation des résultats obtenus.

## Contenu du dépôt

- `analyse.R` : code R utilisé pour préparer les données, effectuer les analyses statistiques et créer les visualisations.
- `rapport_final_patinage.Rmd` : fichier R Markdown contenant le rapport complet, le code, les analyses et les interprétations.
- `index.html` : version HTML du rapport final générée à partir du fichier R Markdown.
- `data/` : dossier contenant les fichiers CSV utilisés pour réaliser les analyses.

## Données

Les données principales proviennent du projet **figure-skating-scores** de BuzzFeed News et contiennent des scores de compétitions internationales de patinage artistique de 2016 et 2017.

Les données originales ne contenant pas la nationalité des juges, cette information a été ajoutée manuellement pour une partie des compétitions afin de permettre l'analyse du biais national.

## Rapport final

Le rapport HTML présente l'ensemble de la démarche, des analyses, des visualisations, des résultats et de leur interprétation.

**[Consulter le rapport final](LIEN_GITHUB_PAGES_ICI)**
