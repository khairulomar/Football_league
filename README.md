# Football Delphi
## Author: Khairul Omar

### Introduction

This project explores the number of wins and losses each team performed in German and English football leagues in 2011, and looks into which teams performed the best when the weather is not favourable.

Data is acquired from two sources:
1. Football league matches data from a SQL database (based on <a href="https://www.kaggle.com/laudanum/footballdelphi" target=new>Kaggle</a> data set)
2. Weather information obtained from <a href="https://darksky.net/dev" target=new>DarkSky API</a>

### Summary Methodology

1. For football matches data, investigate all SQL tables to see which ones are relevant to answer the question in hand.
2. Join the tables together using SQL in order to get the number of goals, wins and losses by team.
3. Summarize and present results in tabular and graphical forms.
4. For weather data, investigate a sample output data from DarkSky API and select the relevant data.
5. Create functions to create a batch download task to retrieve a range of dates when the league took place.
6. Join downloaded API data with football matches data using Pandas.
7. Summarize and present results in tabular and graphical forms.

### Summary Findings

Here are the highlights from 2011 league season:

1. <b>Most goals scored</b>: Manchester United scored the most goals during the season with 93, followed closely by Manchester City with 83. The top scoring German team is Dortmund with 80 in the third place.
2. <b>Most wins</b>: Top 3 teams that had the most wins are the same Top 3 that scored the most goals. Manchester United came on top at 28 wins.
3. <b>Impact of weather on wins</b>: Out of 10 wins by Hoffenheim, 3 were won when it rained, which is the highest rate in our study at 30%.
  
### Conclusion

Top 10 best performing teams in 2011 in terms of both number of goals and number of wins are equally split between English and German teams. Our method may not be best way to measure how well a team performs under bad weather condition, considering a truly all-weather team may not be able to prove itself if all of its matches occured on a good day. Additionally, a loss during a rainy day can also be caused by other factors besides the weather.
