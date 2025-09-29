# Data-Analysis-Task-5
Titanic Dataset Analysis
Project Overview
This project performs an exploratory data analysis (EDA) on the Titanic passenger dataset. The goal is to understand the data, uncover patterns, and visualize key characteristics related to passenger survival during the Titanic disaster. The analysis covers data cleaning, data transformation, and multiple visualizations to highlight factors that influenced survival chances.

What Was Done
Loaded the Titanic dataset containing passenger details like age, sex, class, fare, and port of embarkation.

Cleaned the data by removing records missing key information about embarkation and filling missing ages with a median value.

Transformed port codes into full, descriptive port names for clarity.

Analyzed and visualized distributions of important categories like sex, passenger class, and embarkation port.

Explored numerical data relationships through correlation matrices and identified outliers with boxplots.

Investigated survival rates across different passenger groups using barplots.

Visualized the overall count of survivors versus non-survivors for quick insights.

Created scatterplots to explore relationships between age and fare, colored by survival status and passenger class.

Visualization Explanations
Categorical Distributions: Countplots for variables like sex, passenger class, and embarkation port show the demographic makeup and boarding patterns of passengers.

Correlation Heatmap: Displays correlations between numeric features, revealing how variables like age, fare, and survival relate to each other.

Boxplots: Show distributions and potential outliers for age and fare, helping detect unusual data points.

Survival Rate Barplots: Highlight the differences in survival probability by sex and class, illustrating how factors like gender and socioeconomic status affected survival.

Survival Count Plot: A simple visualization showing the overall number of survivors versus non-survivors.

Scatterplots: Demonstrate interaction between age and fare, with coloring to indicate survival status or passenger class, uncovering hidden patterns.

Why This Matters
This analysis helps both technical and non-technical users explore historical data to understand the factors that affected survival. It combines data cleaning, statistical exploration, and visual storytelling to make complex data accessible and interpretable.

How to Use This Repository
The code is written in Python and organized in Jupyter Notebook cells for straightforward execution.

Each cell performs a distinct part of the analysis, including data cleaning, transformation, and visualization.

Simply run the cells step-by-step to reproduce the analysis and visualize the results.

Tools and Libraries Used
Python for data manipulation and analysis.

Pandas for data handling and cleaning.

Seaborn and Matplotlib libraries for creating visual plots and charts.

Data Source
The original Titanic dataset was obtained from Kaggle Titanic dataset, which provides comprehensive passenger information recorded during the ship's maiden voyage.

Future Work
Future extensions can include building predictive models to classify passenger survival, deeper feature engineering, and interactive visualizations to enhance user exploration.
