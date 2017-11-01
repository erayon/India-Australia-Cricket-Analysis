# India-Australia-Cricket-Analysis
The stats for Australia (over 60 matches) &amp; India (over 50 matches) from January 2015 to September 2017

## 1. Visualize the performance of India’s batting in the match where they scored highest runs in 2016 (India’s_batting_performance_2016.ipynb)
1. We have the table with columns Player,Player link,Minutes, Runs, Ball faced, Fours, Sixes, Strike Rate, Inns, Opposition,Ground,Stat date
of player 2016
2. Then Split the year from Start Date columan and created the new column name 'year'
3. Find the rows in year 2016 and remove all the rows having 'DND' rows which is present in 'Runs' column
4. Created a dataframe of unique players(Batting) having maximum runs and total runs in year 2016
5. Then visually plotted the graph  having 'Players with Maximum runs of playes in year 2016'
6. In the same way plotted another graph  having 'Players with total runs of player in year 2016' 
![Alt text](im1.png?raw=true "Batting") 

## 2. Compare best bowlers (measured by runs/wicket or runs/over) from India and Australia. (bowling_comaprism .ipynb)
1. We have the table wigh columns Player,Maiden,Overs,Runs,Wickets,Economy,Inn,Opposition,Gound,Start Date of Indian bowlers angainst Austrailia.
2. Added a column having 'run/wicket' which displays each Indian bowlers runs per wicket.
3. Created Dataframe having Player name, Maximum runs/wicket and Total runs/wicket.
4. Plottted graph with maximum runs/wicket and Indian bowlers and Australian bowlers.
5. Alos plotted graph with Total runs/wicket Indian bowlers and Australian bowlers.
 Indian Bowlers      :  ![Alt text](im2.png?raw=true "Batting")
 Australian Bowlers  :  ![Alt text](im3.png?raw=true "Batting") 
 
## 3. Which players (one from India and one from Australia) have similar performance record in the given timeframe? (bowling_comaprism .ipynb)
1. Follow the same as above 
2. Include a threshold value such that a particular bowler consider as best bowler if he play more than a threshold number of innings.
3. find the mean of innings of indian bowler dataframe, its around 13, so cosider thoes bowler who have played more than 13 innings as a best bowlers.
4. Same for Australian bowler too and for them threshold around 12, so consider thoes bowler who have played more than 13 innings as a best bowlers.
5. and plot both of them in a scatter plot such that X_axis : Runs_per_wicket and Y_axis : Wickets_per_innings with annotation
![Alt text](imx.png?raw=true "Batting") 
6. So as we can see from that plot they both have more or less similar performance record in the given timeframe
```
JJ Bumrah   : India
JW Hastings : Australia

```

