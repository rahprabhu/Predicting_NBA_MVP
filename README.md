# Predicting the NBA MVP


<b>Question</b>: Can we predict which NBA players will win the MVP award in a given season? 

Methods used to tackle this question:
- <b>Web Scraping with Beautiful Soup</b>
  - To acquire the data, I will scrape historical player statistics and MVP voting history from the past 30 seasons from Basketball Reference to use as my training and testing data to make predictions.
- <b>Data Cleaning with Pandas</b>
  - After acquiring the data, I will use Pandas to clean and combine the datasets so that it is compatible accurate for regression models.
- <b>EDA with Matplotlib</b>
  - Before creating the models, I will used the cleaned dataset to answer a few preliminary questions that help me better understand the top players in the dataset and some of the relationships that exist between variables.
- <b>Ridge Regression and Random Forest Regression</b>
  - Finally, I'll test out both a Ridge Regression and Random Forest and compare the two models. Our models will both predict MVP voting results for each year over the last 30 seasons, however we will judge our model based on an average precision score that looks at how correctly we predicted the top 5 MVP vote-getters.
<br><br>
#### Data Source: Basketball Reference
- MVP Data: https://www.basketball-reference.com/awards/awards_2022.html
- Player Stats: https://www.basketball-reference.com/leagues/NBA_2022_per_game.html
