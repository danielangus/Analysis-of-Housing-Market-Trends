# Analysis of Housing Market Trends

This project is part of Udacity's Machine Learning Engineer Nanodegree curriculum. Using the Boston housing data collected in 1978, the purpose of this project is to predict the selling price for each home based on its' features. Features include the number of rooms, the ratio of teachers to students at the neighbourhood's school, etc. 

## Analysis

The stages in the analysis proceed as follows:
* Data Exploration - creating exploratory data plots
* Developing a Model - choosing a metric and cross-validation strategy
* Analyzing Model Performance - selecting a model to minimize bias and variance
* Evaluating Model Performace - optimizing the model, and comparing it's predictions to true values

## Technologies

This project was completed using Python 2.7. Libraries include:
* sklearn
* numpy
* pandas
* matplotlib

## Results

The analysis shows that the most important factor in determining the price of a home is the percentage of homeowners in the neighbourhood considered 'working poor,' contributing to about 69% of the price of the home. The next most important feature is the number of rooms, which affects 22% of the price.

This model is valuable in letting us know the importance of various factors relating to neighbourhoods and the prices of homes. However, it should not be used in the real world for a variety of reasons. First of all, the data was collected almost forty years ago, and extrapolating using inflation alone would not accurately reflect the modern-day prices of the homes. Prices close to the city centre would have increased much more than those of homes further away. Three variables are also not enough to predict the price of a home. We consider more variables than that when buying a home, like how close it is to work and schools, the furnishings of the home, it's age, the size of the land, etc. Based on the above "prediction trials," there is a wide range of possible values for a home, so our model is not very robust. The data would have been useful for giving a general idea of Boston home prices in various neighbourhoods through the 80s, perhaps, but the housing market has changed so dramatically that an updated model with more data points and features would be needed to accurately predict home prices in today's cities.
