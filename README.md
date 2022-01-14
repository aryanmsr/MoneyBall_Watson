<h1 align="center">
  MoneyBall Watson (IEOR 4523 Final Project)
</h1>
<p align="center">
  This purpose of this project was to create a model that could predict the outcome of a basketball game.
</p>

<div align="center">
  <img alt="ball" src="https://dbukjj6eu5tsf.cloudfront.net/gopsusports.com/images/2021/11/1/Ball_Basket_A_21_NWU_MS_11902_71.jpg" />
</div>


- Link to Kaggle Data: https://www.kaggle.com/nathanlauga/nba-games
- Link to Medium Article: https://medium.com/@aryanmsr/moneyball-watson-predicting-basketball-games-with-data-analytics-d13beba7e645

- 5 datafiles are from the main dataset: 
games.csv, games_details.csv, teams.csv, players.csv, ranking.csv

- 2 datafiles are created by running Notebook 1.Data_Preprocessing_and_Feature_Engineering
reg_2015.csv, elo_2015.csv

- To run the models, make sure to run the notebooks in order, starting from 
  -  1.Data_Preprocessing_and_Feature_Engineering
  -  2.Exploratory_Data_Analysis 
  -  3.Modeling.

- The datafile games_details.csv should be unzipped. 

## Introduction

*As sports betting continues to rise in popularity, we are curious to see how accurately we can construct a binary classification model to predict wins and losses during the regular season games in the NBA. Our ultimate goal is to use machine learning techniques to capture useful information from game statistics and matchups to predict the winner of each game. The findings will help us identify potential factors concerning how teams win along with valuable insights for NBA sports gambling and fantasy basketball participants.*

## Snapshots
### Some Visuals

<figure class="half">
  <table>
    <tr>
      <td>
        <img src="https://miro.medium.com/max/700/1*tCJFiKj-5igXQ2lXAQXxUQ.png" alt="fig1" width = 500>
      </td>
      <td>
        <img src="https://miro.medium.com/max/700/1*fUrD3dT9UWo-BS0bbl89ww.png" alt="fig2" width = 500>
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://miro.medium.com/max/700/1*qe2jNs5tqIePCRggD8bKbA.png" alt="fig3" width = 500>
      </td>
      <td>
        <img src="https://miro.medium.com/max/700/1*1zCdOhHaPBkaPvteupJQpQ.png" alt="fig4" width = 500>
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://miro.medium.com/max/700/1*ZHJL6_4rV_Cad3wYut6WdQ.png" alt="fig5" width = 500>
      </td>
      <td>
        <img src="https://miro.medium.com/max/700/1*TPxDQBtzYwu8TkOoU1Acbw.png" alt="fig6" width = 500>
      </td>
   </tr>
  </table>
  <figcaption>Some plots created during the EDA process.</figcaption>
</figure>

### Model Accuracies 

<figure class="half">
  <div align="left">
    <img alt="fig5" src="https://miro.medium.com/max/700/1*foK6QLsSwqF276DyX0_-ZQ.png" width=500 />
    
  </div>
  <figcaption>The Plot above shows the final accuracies of some of the models used in the project.</figcaption>
</figure>


