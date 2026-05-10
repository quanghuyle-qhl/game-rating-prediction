# Play Quest Conquer (PQC) Game Rating Prediction
## Executive Summary
This project focused on improving PQC’s business performance by identifying the key factors influencing game ratings on its platform. Using multilinear regression and exploratory data analysis, the project found that game complexity, user engagement, premium game types, and gamer interest positively influence ratings. The analysis provided actionable recommendations to improve user satisfaction, strengthen market competitiveness, and drive revenue growth.
## Business Problem
PQC operates in a highly competitive gaming market where fluctuating game ratings directly affect business performance, user satisfaction, and revenue generation. The company needed a data-driven solution to better understand what drives positive game ratings and how to strategically improve game offerings and engagement. The project aimed to help PQC make informed decisions regarding product development, marketing strategies, and platform optimization.
## Methodology
The project used exploratory data analysis and multilinear regression to analyze relationships between game features and average game ratings.

Key steps included:

- Cleaning and preparing a dataset of 24,813 games and 17 attributes.
- Removing invalid values and handling missing identifiers.
- Conducting correlation analysis between variables and average ratings.
- Selecting significant predictors based on correlation thresholds.
- Splitting data into 80% training and 20% testing sets.
- Building a multilinear regression model to predict game ratings.

Selected features included:

- Average Complexity
- High Interest Number
- Interest Number
- Average Play Time
- Game Type

Model performance was evaluated using:

- R-squared
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
## Demonstration of Skills and Capabilities
**Data-Driven Feature Selection:** Identified that game complexity, premium game type, player interest, and user engagement metrics have the strongest influence on average game ratings, while variables such as player configuration showed limited predictive value.

**Statistical & Predictive Modeling:** Applied multilinear regression to measure how multiple gameplay and engagement factors collectively impact game ratings. Model coefficients were analysed to determine the relative influence of each predictor on user satisfaction.

**Business-Oriented Data Analysis:** Conducted exploratory data analysis using histograms, scatterplots, correlation matrices, and trend analysis to uncover patterns in gamer behavior, game popularity, and rating performance.

**Model Evaluation & Optimisation:** Evaluated model effectiveness using R-squared, MAE, and RMSE metrics, while addressing challenges such as multicollinearity, outliers, and variable selection to improve interpretability and predictive reliability.

**Technical Literacy & Data Processing:** Managed a large gaming dataset containing over 24,000 games and multiple gameplay, engagement, popularity, and configuration variables to build a multidimensional understanding of rating performance.

**Business Translation & Strategic Insight:** Translated analytical findings into actionable business recommendations, including increasing game complexity, enhancing user engagement strategies, and investing more heavily in premium game development to improve ratings and profitability.
## Results and Business Recommendations
The multilinear regression model achieved:
- R-squared: 0.19
- MAE: 1
- RMSE: 1

Key findings included:
- Premium games tend to receive higher ratings.
- Higher game complexity is associated with better user ratings.
- Longer playtime and higher user engagement positively influence ratings.
- Games with higher interest and ownership generally perform better.

Business recommendations included:
- Developing more complex and engaging games.
- Increasing user engagement through events and loyalty programs.
- Expanding premium game offerings.
- Improving marketing strategies to attract and retain gamers.
## Model Integrity & Risk Assessment
Although the model produced useful business insights, several limitations were identified:
- The model explained only 19% of the variance in ratings.
- Outliers and multicollinearity may affect prediction accuracy.
- The linear approach may oversimplify complex relationships between gaming variables.
- Excluding temporal variables such as Released_Year may limit long-term predictive performance.

Future improvements may involve:
- Using larger and more diverse datasets.
- Applying advanced machine learning techniques such as nonlinear regression models.
- Incorporating additional variables related to user behavior and market trends.
## Context and Credits
Client: Play Quest Conquer

Tools Used: Python, Google Colab

Analyst: Quang Huy Le
