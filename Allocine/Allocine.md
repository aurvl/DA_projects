# Data Visualization - Allociné

#### Structure du Repo
```
Allocine/
    - Allocine.md : Project description
    - allocine.ipynb : This Jupyter Notebook contains the python script used to create all visualizations
    - Base_allocine.xslx : Dataset that contains moovies informations
```

Link to the Notebook : [https://aurvl.github.io/NotebookSites/m2_exercices_py/allocine/allocine.html](https://aurvl.github.io/NotebookSites/m2_exercices_py/allocine/allocine.html)

## Description du Projet
Ce projet vise à analyser un jeu de données d'Allociné, une base de données cinématographique française, afin de visualiser diverses informations clés et de comprendre les relations entre différents attributs des films et séries.

## Dataset
Le jeu de données utilisé pour cette analyse a été collecté via un projet de scraping réalisé sur une cinquantaine de films d'Allociné. Ce projet de scraping, dont les détails se trouvent ici : [Scraping Project](https://github.com/aurvl/DE_projects/blob/main/Scraping%20Allocine/Scraping%20Allocine.md), a permis de constituer la base de données utilisée dans ce projet (Base_allocine.xlsx). Les données comprennent les noms des acteurs, les genres, les chaînes de diffusion, la durée des films et les années de diffusion.

## Tools
Les principales bibliothèques Python utilisées sont :

- **Pandas** : pour le chargement et la manipulation des données
- **NumPy** : pour les opérations numériques
- **Matplotlib & Seaborn** : pour les visualisations graphiques
- **NetworkX** : pour la création de réseaux relationnels entre les acteurs

**Visualisations Clés**

- **Nombre d'apparitions des acteurs** : Un graphique qui montre le nombre d'apparitions des acteurs présents dans plus de deux films, afin de visualiser leur fréquence dans la base de données.

- **Nombre de saisons par chaîne de diffusion** : Un graphique qui présente le nombre de saisons d'un film ou d'une série en fonction de la chaîne de diffusion.

- **Durée des films par genre** : Une visualisation qui explore la durée moyenne des films en fonction de leur genre, permettant d'analyser les tendances de durée pour différents types de films.

- **Nombre de séries diffusées par année** : Un graphique qui montre l'évolution du nombre de séries diffusées par année, permettant de suivre les tendances de popularité dans le temps.

## Key Functions
Le notebook utilise plusieurs fonctions personnalisées pour extraire et analyser les données, comme :

* La séparation des noms d'acteurs pour compter leur fréquence d'apparition.
* La création de réseaux d'acteurs pour visualiser leurs relations en fonction des films dans lesquels ils apparaissent ensemble.
<br>
<br>

*Enjoy ! 🎉*
