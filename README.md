# INFO 49635 AI Research Project

## Abstract

This study utilized the Pycaret library to evaluate the performance of various classification models on a chess dataset, aiming to determine the most effective approach for predicting win or no-win situations in chess game outcomes. The dataset consisted of 37 attributes describing the board, with the final attribute indicating the classification. Pycaret's automated machine learning workflow was employed to compare the best models, both with default settings and customized parameters. Evaluation metrics included confusion matrices, ROC curves, and accuracy scores. The CatBoost Classifier emerged as the top performer, achieving an accuracy score of 0.9937 on the entire training set and 0.9654 on held-out data. Other notable models were Decision Tree Classifier, Extreme Gradient Boosting, Light Gradient Boosting Machine, and Random Forest Classifier, all scoring above 0.9852. These findings have significant implications for chess game analysis, suggesting that machine learning algorithms can be highly effective in predicting outcomes and providing insights into strategic decision-making.

## Video Overview

[![AI Research Overview](https://img.youtube.com/vi/1AeM5GJGSjE/0.jpg)](https://youtu.be/1AeM5GJGSjE)

## Dataset

Shapiro,Alen. (1989). Chess (King-Rook vs. King-Pawn). UCI Machine Learning Repository. <https://doi.org/10.24432/C5DK5C>.