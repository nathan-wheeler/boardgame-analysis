# Summary
In this project, I analyze a dataset of 22,000 board games in order to 1) identify features of successful board games and 2) develop a recommendation system based on similar games. A summary of these analyses and thier findings can be found [HERE](https://github.com/nathan-wheeler/boardgame-analysis/blob/main/BGG_EDA.pdf))

# Data
Data was scrapped from Board Game Geek’s API in 2022 and contains 19mil ratings of 22k board games. 
[Dataset on Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek)

# Notable Analyses

After preprocessing, cleaning the data and examining descriptive statistics of interest, I preformed the following analysis:
1.	XGBoost regression with extracted SHAP scores to identify the feature importance in predicting of game popularity.  
2.	Non-negative matrix factorization (NMF) to identify the most and least popular kinds of games.
3.	Cosine Similarity to recommend the next most similar games to any one of interest. 
