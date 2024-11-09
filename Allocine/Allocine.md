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
Ce projet vise à analyser un jeu de données d'Allociné, une base de données cinématographique (des films & séries), afin de visualiser diverses informations clés et de comprendre les relations entre différents attributs des films et séries.

## Dataset
Le jeu de données utilisé pour cette analyse a été collecté via un projet de scraping réalisé sur une cinquantaine de films d'Allociné. Ce projet de scraping, dont les détails se trouvent ici : [Scraping Project](https://github.com/aurvl/DE_projects/blob/main/Scraping%20Allocine/Scraping%20Allocine.md), a permis de constituer la base de données utilisée dans ce projet (Base_allocine.xlsx). Les données comprennent les noms des acteurs, les genres, les chaînes de diffusion, la durée des films et les années de diffusion.

**Variables du Dataset**
Le dataset contient plusieurs variables pertinentes qui permettent d’analyser divers aspects des films et séries d'Allociné :

1. **Titre** : Le titre du film ou de la série. Cette variable est essentielle pour identifier chaque œuvre de manière unique.

2. **Acteurs** : Une liste des principaux acteurs ayant participé au film ou à la série. Cette variable est utile pour analyser la fréquence des apparitions des acteurs et créer des réseaux d'acteurs.

3. **Genre** : Le ou les genres associés au film ou à la série (ex : Comédie, Drame, Action). Cette variable permet d'explorer les tendances et préférences des genres, et d'étudier la distribution des durées par genre.

4. **Chaîne de diffusion** : La chaîne ou la plateforme où le film ou la série a été diffusé. Cette information permet d'analyser la répartition des œuvres par diffuseur et d'étudier les préférences de diffusion.

5. **Durée** : La durée du film ou de chaque épisode de la série (en minutes). Cette variable est utilisée pour comprendre la durée moyenne des œuvres par genre et identifier les tendances de durée en fonction des types d'œuvres.

6. **Année de diffusion** : L’année de première diffusion du film ou de la série. Cette variable est particulièrement utile pour observer l’évolution des productions au fil des années et identifier les tendances de sortie.

7. **Nombre de saisons** : Dans le cas des séries, cette variable indique le nombre de saisons pour chaque série, permettant d’analyser la longévité des séries en fonction de leur chaîne de diffusion.

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
