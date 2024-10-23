
# CodSoft Data Science Internship

This repository cotains my all projects which i have built during my Internship with CodSoft. 

### Project #1 : Titanic Survival Prediction
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, I have built a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

### Project #2 : Movie Rating Prediction with Python
In this project, I built a model that predicts the rating of a movie based on
features like genre, director, and actors.

I analyze and predict movie ratings, encountered various data challenges, such as missing values, typos in column names, and duplicated records. Through a series of data cleaning and preprocessing steps, I successfully prepared the dataset for analysis. 

The analysis uncovered several interesting insights about the movie dataset. I observed trends in movie durations, genre popularity, the most prolific actors and directors, and the distribution of movie ratings and votes over the years. Notably, I found that short-duration movies tend to receive higher ratings and votes, and the Drama genre has consistently performed well in terms of ratings. 

Furthermore, the evaluation of machine learning models revealed that Random Forest outperformed Linear Regression, with an impressive R-squared score of 0.94 on unseen data, highlighting the model's robustness.

### Project #3 : Iris flowers Classification
The Iris flower dataset consists of three species: setosa, versicolor,
and virginica. These species can be distinguished based on their
measurements. 

I have trained  a machine learning model that learns from
these measurements and accurately classify the Iris flowers into
their respective species.

### Project #4 : Sales Prediction using Python
Objective: The project aims to predict sales based on advertising spending on different platforms, specifically TV advertising.

I loaded and inspected the advertising dataset for missing values and outliers. The data was clean and required no significant preprocessing.

I performed univariate and bivariate analyses to explore the relationships between advertising spend across various platforms and sales. Through scatter plots and a correlation heatmap, I observed a strong positive correlation between TV advertising and sales.

I built a simple linear regression model using the statsmodels library, where TV advertising served as the predictor variable and sales as the target variable. I trained the model on 70% of the data using the Ordinary Least Squares (OLS) method.

To evaluate the model's performance, I used metrics like R-squared, F-statistic, and conducted residual analysis. The model achieved an R-squared value of 0.816, explaining 81.6% of the variance in sales. The F-statistic and its significance confirmed that the model fit was statistically sound, while residual analysis validated the normality of error terms.

I used the model to make predictions on the remaining 30% of the data (test set). The Root Mean Squared Error (RMSE) was calculated to assess the accuracy of these predictions. I also computed the R-squared value on the test data to evaluate the model’s generalization ability.

I visualized the relationship between TV advertising and sales using scatter plots, overlayed with the regression line. The plots demonstrated how well the model fit both the training and test data.

**Conclusion:**

I successfully developed a simple linear regression model to predict sales based on TV advertising spend. The model exhibited strong predictive power and explained a significant portion of the variance in sales, highlighting the positive impact of TV advertising on sales.



