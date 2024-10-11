# NFL Data Analysis

## Project Overview

This project aims to analyze and forecast NFL player and game performance, providing valuable insights for teams, coaches, and analysts to enhance strategic decision-making. By leveraging player and game statistics, we focus on uncovering trends, evaluating player performances, and predicting future game outcomes. The analysis encompasses both historical performance data and forecasting, delivering comprehensive insights through an interactive dashboard.

## Objectives

The main objectives of the project are:
- **Player Performance Evaluation**: Assess individual player performance across various metrics using advanced clustering techniques.
- **Game Strategy Development**: Utilize game statistics to help coaches and analysts formulate strategic game plans.
- **Game Stats Forecasting**: Predict future player and team performance based on historical data trends.

## Data Sources

The datasets used for this analysis were sourced from [Kaggle](https://www.kaggle.com/datasets/kendallgillies/nflstatistics?resource=download), and they include:
- Career Stats: Defensive, Fumbles, Rushing, Kick Return, Receiving
- Game Logs: Defensive Lineman, Kickers, Punters, Quarterbacks, Running Backs

Each dataset contains unique key performance indicators (KPIs) that are vital to evaluating both player and game performance.

## Project Methodologies

- **Data ETL**: Data was extracted from Kaggle, cleaned, transformed, and merged into a single dataset using Python (Pandas and NumPy). Irrelevant entries, such as inactive players or unsorted columns, were removed.
- **Exploratory Data Analysis (EDA)**: Initial data analysis was conducted to identify patterns, missing values, and trends.
- **Data Cleaning**: Missing values were either filled with 0 or replaced based on player activity. Float conversion was applied where necessary for analysis-readiness.
- **Clustering Techniques**: K-Means clustering was employed to categorize players into performance classes (Best, Moderate, Low) for various statistical categories.
  
## Data Visualization and Forecasting

- **Dashboard Creation**: A comprehensive Tableau dashboard was built to visualize the player performance stats, game stats, and time series forecasts.
- **Key Insights**: Visualization of the trends and metrics, such as win-loss ratios and player performances, post-COVID impacts on player stats, and performance by position.
- **Forecasting**: Time series forecasting was utilized to predict future game statistics, focusing on player categories such as kickers, punters, and wide receivers.

## Key Features

1. **Player Performance Dashboard**: Interactive charts and tables highlighting individual player performances across seasons.
2. **Game Stats Dashboard**: Overview of game statistics, including wins, losses, and team performance over time.
3. **Time Series Forecasting**: Projections for future player performances and game outcomes based on historical data trends.

## Key Findings

- Player performance, especially in defense, has generally decreased over recent seasons.
- Post-COVID trends show a significant decline in overall player stats.
- Kickers, such as Stephen from the New England Patriots, are projected to perform above average in the upcoming season.
- Running backs have seen new players outperform existing ones in recent seasons.

## Future Scope

- **Real-Time Integration**: Integration with football database APIs for real-time stats and forecasts.
- **Enhanced Forecasting**: As new season data becomes available, forecasts will be continuously refined for improved accuracy.
  
## Challenges

Some challenges encountered during the project include:
- Merging complex datasets across different player stats categories.
- Tuning the clustering algorithms to accurately reflect player performance.

## Conclusion

This project provides a powerful tool for NFL teams and analysts to make data-driven decisions. Through thorough analysis and forecasting, the dashboard offers actionable insights that can enhance strategic planning for teams across the league.
