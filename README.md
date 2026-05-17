# Dota Rank Prediction 2026

This repository contains a course project prepared for **Statistics in Artificial Intelligence and Data Analysis 2025/26**. The goal of the project is to predict the Dota 2 match rank tier based on match-level information and aggregated player statistics.

## Project overview

The task is a supervised multi-class classification problem. For each match, the model predicts the `tier` label, corresponding to one of the Dota 2 rank groups:

- Herald
- Guardian
- Crusader
- Archon
- Legend
- Ancient
- Divine
- Immortal

The project follows a typical statistical learning workflow:

1. load and inspect JSON match data,
2. transform nested match/player data into a tabular format,
3. engineer aggregated numerical features,
4. clean missing values and outliers,
5. compare several classification models,
6. choose the best model using a validation set,
7. generate predictions for the competition test set.
