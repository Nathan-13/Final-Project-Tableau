# Final-Project-Tableau
## Project/Goals
The primary goals are to analyze the FIFA 18 player dataset using Tableau to accomplish the following:
* Create diverse visualizations for deeper insights,

* Determine the most critical features among 70 attributes,  

* Detect patterns and trends and identify critical insights,

* Build an interactive data dashboard and ultimately present the findings.

## Process
### Step 1: 
Add the FIFA 18-player dataset to Tableau and evaluate the essential data types.

### Step 2:
Create diverse visualizations (tables, bar charts, heatmaps, histograms) to explore player attributes and formulate questions.

### Step 3: 
Analyze the visualizations and data in Tableau to identify interesting patterns, trends, outliers, or anomalies in player data. Define a research question, "What factors are most strongly correlated with a player's overall rating in FIFA 18, and how do these factors vary across different player positions?" To address this question, plot a graph of players' overall ratings vs. players' value. In addition, it explores the behaviour of players' values and wages over players' ages. See the workbook served in the data folder.

### Step 4:
Develop an interactive Tableau dashboard, the fifa18 Dashboard in the workbook (this can be found in the data folder), that answers questions and showcases insights. And then the Fifa18 story that tells the story of this project. See the presentation/dashboard pdf in the data folder.

## Results
Successfully classified data types and identified some missing essential data types. Created six diverse visualizations to explore player attributes and gain insights. Developed an interactive Tableau dashboard that answers questions and presents insights.

### Navigating the Dashboard
To navigate the Dashboard, at the top is the dataset overview, which includes Total Players, Total Nationality, Average Age, Average Overall ratings, Average Market Value and Wages, and the number of Clubs. 

The different clubs can be searched via the "Search Club" filter, and then the List of Players, Category and Player Rating tables show the result and the average club rating for different attributes, respectively. 
Select individual player names to see their ratings for the different attributes of a soccer player.
Use the "Reset Filters" on the search panel to reset the Dashboard or return to the "all" search.

Also, foreign nationality can be searched using the "Search Nationality" filter. The total number of players from each nationality can be obtained by hovering on the heatmap. With these searches, there are interactions of the club or nationality search with both Wages and Value vs. Age and Overall Ratings vs. Value graphs. 

### Answer to Research Question
I discovered exciting patterns, trends, and outliers in player data. The Wages and Value vs. Age bar chart shows that players' value and wages increase until the age of 26 and then a drastic decline. Also, there is an exponential relationship between the overall ratings and players' market value. The R-squared of 0.888 and a p-value less than 0.0001 suggested that the exponential regression model fits the data well, and the relationship between the variables is substantial and statistically significant. This indicates that the overall ratings substantially impact explaining the variation in the players' market value exponentially.

 ## Challenges 
* Ensuring data quality and dealing with missing values, outliers, and inconsistencies in the dataset.

* Balancing the depth of analysis with the need for clear and concise presentation in Tableau.

* Interpretation of feature importance and its impact on player performance.

* Ensuring the Tableau dashboard is user-friendly and provides valuable information to stakeholders.


## Future Goals
* Extend the analysis to compare player attributes across different FIFA versions and leagues.

* Collaborate with domain experts to gain deeper insights into the factors influencing player performance.

* Explore additional data sources, such as player injury history and transfer market data, to enrich the analysis in Tableau.


