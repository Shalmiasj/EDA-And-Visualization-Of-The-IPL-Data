
# EDA Of The IPL Data and identifying top players using Clustering Algorithms 
The top group of players were identified using various clustering algorithms such as AGNES, DBSCAN, mini batch K-means, and Birch using the history of players played in the last 12 years of IPL matches. Team-wise and player-wise analysis was performed, and the results were visualized.
## Overview
This work contains the sports analysis of all the IPL teams played in each season from 2008-
2021 and all the players data. 
## Motivation
Cricket analysis forms a bridge between the players, coaches and 
managers. Players' performance history from the past can be an invaluable tool to select or buy the best players for the teams. The history can speak more about the players' consistency 
all over the years, way of approaching the game to a great extent.

## Project Structure

![Workflow](https://imgtr.ee/images/2023/06/03/Sf9z3.png)

## Data 
The dataset used for this project is sourced from Kaggle and consists consists of features to analyse the best players for IPL.

- `IPL_Ball_by_Ball_2008_2021.csv`: This file contains the dataset used for the project.
- `IPL_Matches_2008_2021.csv`: This file contains the dataset used for the project.

## Notebooks
- `Final_EDA.ipynb`: Explore the dataset, perform descriptive statistics, and visualize key insights.
- `Final_Clustering.ipynb`: Use different Clustering models for obtaining top group of players based on their performance over the last year's IPL matches.

## Clustering  Algorithms Used
- Hierarchical Clustering
- DBSCAN Clustering
- Mini Batch K means Clustering
- Birch Clustering 

## Performance Metrics Used
- Silhouette Coefficient
- Calinski-Harabasz Index
- Davies-Bouldin Index

## Packages Used
- Pandas 
- Numpy
- Matplotlib 
- Seaborn
- Sklearn 
- Plotly 
- Ipython

## Results
Visualisation are made to draw some conclusion from the data by ranking the players based 
on their runs, number of matches played, number of balls bowled etc.,. We performed various 
analysis on each player, team and season. Then we used clustering algorithms to group the 
players based on their performance. Also we have examined which algorithm works best 
using respective evaluation metrics. 

## Conclusion

We performed Season-wise, team-wise and player wise analysis on matches and deliveries dataset and visualized the results.We extracted the details(matches played ,strike rate, balls bowled, runs etc.)of all the players through out all the seasons and created a dataset which we have used to perform clustering.The players performance using  4 clustering algorithms are compared. Based on the performance metrics we conclude that  hierarchical clustering, AGNES using average linkage  produced better clustering results compared to Mini batch k means, Birch and DBSCAN clustering.


 



