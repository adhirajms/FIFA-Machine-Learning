# Predicting FIFA Video Game Player Ratings

This project is a part of the Machine Learning and Predictive Analytics Class (MScA 31009) at the University of Chicago's Master in Science in Analytics Program.  


## Project Intro/Objective
The purpose of this project is to predict the FIFA video game rating of soccer players. The end goal is to be able to suggest a mechanism to companies that they can adopt in order to give players video game rating based on their actual performances.


### Methods Used
* Neural Networks
* Machine Learning
* Data Visualization
* Predictive Modeling


### Technologies
* Python 
* Excel

## Dataset
The data has been acquired from two different sources.

The data based on the FIFA video games has been acquired from this source. There is data for all the games from FIFA 16 till FIFA 22
The dataset, with more information can be found on kaggle, linked [here](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset) 

The real statistics of the soccer players across the 5 major soccer leagues- English Premier League, Ligue 1, Bundesliga, La Liga, Serie A- have been acquired from https://www.rotowire.com/soccer/

For each player there are over 85 performance indicators.

## Methodology

For this analysis we narrowed our scope to just the top 5 soccer leagues across Europe. We standardized the name of the player by using fuzzy partial ratio across the name column across the 2 datasets (real data and the video game data). In order to save time, we applied blocking based upon the Season the player performed in and the club the player belonged to at the time of the particular season.

After this process, we combine the real statistics and the video game game statistics by creating an unique key based upon the player name, the player club and the Season.

Adter EDA and feature engineering, we use use 5 different models to predict the players' FIFA video game rating:
- Logistic Regression
- Decision Tree
- Random Forest 
- XGBoost
- Neural Networks 


## Contributing Members

|Name     |  GitHub Handle   | 
|---------|-----------------|
|[Adhiraj M Srivastava](https://github.com/[adhirajms]) |     @adhirajms   |
|[Shikhar Madrecha](https://github.com/[madrechashikhar])| @madrechashikhar        |
|[Haider Waseem](https://github.com/[haiderwaseem1]) |     @haiderwaseem1    |
|[Akhir Saybani](https://github.com/[syb8])| @syb8        |
