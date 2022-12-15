# Projet Analyse De donnée  EPI :


# Video Game Sales Analysis

<hr>



- Analyzing the 'Video Game Sales Analysis' dataset with the help of pandas library and learn 
the fundamentals of plotly by visualizing the result using simple yet interactive graphs.
<br>
<hr>
<img src="https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2018/03/video-games-and-block-chain.jpeg"  />



<br>
<hr>

- Objectives :


1.  Use pandas library to analyze different features of the dataset, which includes,
   
    * Read the dataset.
    * Use functions like df.query and df.groupby.
    * Analyze the sales for different regions with respect to various features.
  
2. Use plotly library to visualize the given results.

   * Plot graphs like bar graphs and pie charts.


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
|14  |Wii Fit                                     |Wii     |2007|Sports      |Nintendo              |8.94    |8.03    |3.6     |2.15       |22.72       |
|15  |Wii Fit Plus                                |Wii     |2009|Sports      |Nintendo              |9.09    |8.59    |2.53    |1.79       |22          |
|16  |Kinect Adventures!                          |X360    |2010|Misc        |Microsoft Game Studios|14.97   |4.94    |0.24    |1.67       |21.82       |
|17  |Grand Theft Auto V                          |PS3     |2013|Action      |Take-Two Interactive  |7.01    |9.27    |0.97    |4.14       |21.4        |
|18  |Grand Theft Auto: San Andreas               |PS2     |2004|Action      |Take-Two Interactive  |9.43    |0.4     |0.41    |10.57      |20.81       |
|19  |Super Mario World                           |SNES    |1990|Platform    |Nintendo              |12.78   |3.75    |3.54    |0.55       |20.61       |
|20  |Brain Age: Train Your Brain in Minutes a Day|DS      |2005|Misc        |Nintendo              |4.75    |9.26    |4.16    |2.05       |20.22       |



* Understanding the dataset
This dataset contains a list of video games with sales greater than 100,000 copies. 
Each row in the dataset represents a game, whereas, each column contains different attributes.

* The data set includes information about:

- Rank - The overall rank of the game.
- Name - The name of the game.
- Platform- The platform on which the game was released.
- Year- The year in which the game was released.
- Genre-The genre of the game.
- Publisher-The publisher of the game.
- NA_Sales, EU_Sales, JP_Sales , Other_Sales, Global_Sales Sales made by a particular game in North America, Europe, Japan, Other regions and Globally (in millions).





# You want to find the answers to the following questions:

1. Which region has performed the best in terms of sales?
2. The top gaming consoles are Microsoft (Xbox), Sony     (Playstation) and Nintendo, with Google acting as a new competitor. Does the dataset also back this information? Analyze with respect to different regions.
3. What are the top 10 games currently making the most sales globally?
4. What are the top games for different regions?
5. Are there any games with release year older than 2000 that are still making high sales? What are they?

6. What are the top gaming genres that are making high sales?
7. Does the publisher have any impact on the regional sales?
8. Is there any region that has out-performed global average sales?

<center>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NaderCYBERR/Projet-Analyse/HEAD)
</center>



