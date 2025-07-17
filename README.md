# Summary
In this project, I analyze a dataset of 22,000 board games in order to 1) identify features of successful board games and 2) develop a recommendation system based on similar games. 

# Data
Data was scrapped from Board Game Geek’s API in 2022 and contains 19mil ratings of 22k board games. 
[Dataset on Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek)

# Analyses

After preprocessing, cleaning the data and examining descriptive statistics of interest, I preformed the following analysis:
1.	Lasso regression and shap scores for XGBoost regression to identify the features that were most predictive of game popularity.  
2.	Non-negative matrix factorization (NMF) to identify the most and least popular kinds of games.
3.	Cosine Similarity to recommend the next most similar games to any one of interest. 
