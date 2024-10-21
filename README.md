Minnesota Twins 2024 Season Record Prediction
Project Overview

This project aims to predict the Minnesota Twins' 2024 season record by leveraging historical data and individual player statistics. Using machine learning techniques, the model will forecast the outcome of each game in the season, providing insights into potential win-loss records, game-by-game predictions, and overall season performance.
Project Goals

    Develop a predictive model using historical Minnesota Twins data.
    Incorporate player statistics to improve the accuracy of game outcomes.
    Predict game results for the entire 2024 season.
    Analyze the factors that most significantly influence game outcomes (e.g., player performance, team matchups).

Data Sources

    Historical Game Data: Data from previous seasons, including game outcomes, team statistics, and opponent information.
    Player Statistics: Detailed player performance data (e.g., batting averages, pitching performance, fielding stats) for both the Minnesota Twins and their opponents.

The data has been cleaned and processed for modeling purposes. All necessary preprocessing steps are documented in the associated R Markdown files.
Tools & Technologies

    Programming Languages: R
    Libraries:
        dplyr, tidyr for data manipulation
        ggplot2 for visualizations
        caret, randomForest, xgboost for model training and evaluation
        MASS for implementing LDA and QDA models
    R Markdown: Used for documenting the analysis, modeling, and results.

Methodology

    Data Cleaning & Preprocessing:
        Merging historical game data with player statistics.
        Handling missing data, removing outliers, and normalizing variables.
    Exploratory Data Analysis (EDA):
        Visualizing trends and patterns in the data.
        Identifying key factors influencing game outcomes.
    Modeling:
        Applying various machine learning models, such as Random Forest, Gradient Boosting, and Logistic Regression, to predict game outcomes.
        Using feature importance to determine the most influential variables.
    Evaluation:
        Assessing model accuracy using cross-validation and performance metrics like ROC AUC, precision, recall, and F1-score.
    Prediction:
        Simulating the 2024 season and predicting the outcome of each game.
        Estimating the overall season win-loss record for the Minnesota Twins.

How to Run the Project

    Clone the Repository:

    bash

git clone https://github.com/your-repo/twins-2024-prediction.git
cd twins-2024-prediction

Install Required Packages: Ensure you have R installed, then run the following command to install all necessary packages:

r

    install.packages(c("dplyr", "ggplot2", "caret", "randomForest", "xgboost"))

    Run the R Markdown Files: Use RStudio or a similar IDE to open and run the R Markdown files in sequence:
        Data_Cleaning.Rmd: Processes and prepares the data.
        Exploratory_Analysis.Rmd: Performs EDA on the dataset.
        Model_Training.Rmd: Trains the predictive models.
        Season_Prediction.Rmd: Predicts the results for the 2024 season.

    View Results: The predictions will be saved as a CSV file and visualized within the final R Markdown file.

Results

Upon running the project, the predicted outcomes for each of the Minnesota Twins' 2024 games will be available. The results will include:

    Game-by-game predicted outcomes (win/loss).
    Final projected win-loss record for the season.
    Visualizations of key player statistics and their impact on game results.

Future Enhancements

    Integrating real-time player performance updates throughout the 2024 season.
    Expanding the model to include advanced metrics such as WAR (Wins Above Replacement) and defensive stats.
    Developing a web-based dashboard for live game outcome predictions.

Authors

    Christian DeJong, Collin Thompson, Matthew Niblock
