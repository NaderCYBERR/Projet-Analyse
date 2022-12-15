# Projet Analyse De donnée  EPI :


# Video Game Sales Analysis

<hr>



- Analyse de l'ensemble de données "Analyse des ventes de jeux vidéo" à l'aide de la bibliothèque pandas et apprentissage
les fondamentaux de plotly en visualisant le résultat à l'aide de graphiques simples mais interactifs.
<br>
<hr>
<img src="https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2018/03/video-games-and-block-chain.jpeg"  />



<br>
<hr>

* **Objectifs** :


1.  Utilisez la bibliothèque pandas pour analyser différentes fonctionnalités de l'ensemble de données, qui comprend,
   
     * Lire l'ensemble de données.
     * Utilisez des fonctions comme df.query et df.groupby.
     * Analyser les ventes pour différentes régions en fonction de diverses fonctionnalités.
  
2. Utilisez la bibliothèque plotly pour visualiser les résultats donnés.

    * Tracer des graphiques comme des graphiques à barres et des camemberts.


# My Data Set :




* Video games data.

|Rank|Name                                        |Platform|Year|Genre       |Publisher             |NA_Sales|EU_Sales|JP_Sales|Other_Sales|Global_Sales|
|----|--------------------------------------------|--------|----|------------|----------------------|--------|--------|--------|-----------|------------|
|1   |Wii Sports                                  |Wii     |2006|Sports      |Nintendo              |41.49   |29.02   |3.77    |8.46       |82.74       |
|2   |Super Mario Bros.                           |NES     |1985|Platform    |Nintendo              |29.08   |3.58    |6.81    |0.77       |40.24       |
|3   |Mario Kart Wii                              |Wii     |2008|Racing      |Nintendo              |15.85   |12.88   |3.79    |3.31       |35.82       |
|4   |Wii Sports Resort                           |Wii     |2009|Sports      |Nintendo              |15.75   |11.01   |3.28    |2.96       |33          |
|5   |Pokemon Red/Pokemon Blue                    |GB      |1996|Role-Playing|Nintendo              |11.27   |8.89    |10.22   |1          |31.37       |
|6   |Tetris                                      |GB      |1989|Puzzle      |Nintendo              |23.2    |2.26    |4.22    |0.58       |30.26       |
|7   |New Super Mario Bros.                       |DS      |2006|Platform    |Nintendo              |11.38   |9.23    |6.5     |2.9        |30.01       |
|8   |Wii Play                                    |Wii     |2006|Misc        |Nintendo              |14.03   |9.2     |2.93    |2.85       |29.02       |
|9   |New Super Mario Bros. Wii                   |Wii     |2009|Platform    |Nintendo              |14.59   |7.06    |4.7     |2.26       |28.62       |
|10  |Duck Hunt                                   |NES     |1984|Shooter     |Nintendo              |26.93   |0.63    |0.28    |0.47       |28.31       |
|11  |Nintendogs                                  |DS      |2005|Simulation  |Nintendo              |9.07    |11      |1.93    |2.75       |24.76       |
|12  |Mario Kart DS                               |DS      |2005|Racing      |Nintendo              |9.81    |7.57    |4.13    |1.92       |23.42       |
|13  |Pokemon Gold/Pokemon Silver                 |GB      |1999|Role-Playing|Nintendo              |9       |6.18    |7.2     |0.71       |23.1        |



* Comprendre le jeu de données
Cet ensemble de données contient une liste de jeux vidéo vendus à plus de 100 000 exemplaires.
Chaque ligne de l'ensemble de données représente un jeu, tandis que chaque colonne contient des attributs différents.

* L'ensemble de données comprend des informations sur :

- Rank -Le classement général du jeu.
- Name - Le nom du jeu.
- Platform- La plate-forme sur laquelle le jeu est sorti.
- Year- L'année de sortie du jeu.
- Genre- Le genre du jeu.
- Publisher- L'éditeur du jeu.
- NA_Sales, EU_Sales, JP_Sales , Other_Sales, Global_Sales Ventes réalisées par un jeu particulier en Amérique du Nord, en Europe, au Japon, dans d'autres régions et dans le monde (en millions).





# Vous souhaitez trouver les réponses aux questions suivantes :

1. Quelle région a le mieux performé en termes de ventes ?
2. Les meilleures consoles de jeu sont Microsoft (Xbox), Sony (Playstation) et Nintendo, Google agissant comme un nouveau concurrent. L'ensemble de données contient-il également ces informations ? Analysez par rapport aux différentes régions.
3. Quels sont les 10 jeux les plus vendus actuellement dans le monde ?
4. Quels sont les meilleurs jeux pour différentes régions ?


<center>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NaderCYBERR/Projet-Analyse/HEAD)
</center>



