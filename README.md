Airbnb NYC Data Analysis
=======================

Introduction
------------

In this project, we analyze the Airbnb NYC dataset to gain insights into the Airbnb market in New York City. The dataset contains information about Airbnb listings in NYC, including the location, price, room type, and number of reviews.

Data Preparation
-----------------

We first mount the Google Drive and load the necessary libraries, including numpy, pandas, matplotlib, and seaborn. We then read the Airbnb NYC dataset from a CSV file and perform some initial data exploration, including checking the data types, shape, and missing values.

We drop the duplicate and missing values from the dataset and fill the missing values in the 'reviews\_per\_month' column with 0. We also drop the columns 'name', 'id', 'host\_name', and 'last\_review' as they are not relevant to our analysis.

Data Visualization
-------------------

We calculate the correlation between the numeric columns in the dataset and visualize the correlation matrix using a heatmap. We also create count plots to show the distribution of room types and neighborhood groups in the dataset.

We create a box plot to show the relationship between the availability of a room and the neighborhood group. We also create a scatter plot to show the location of the Airbnb listings in NYC, colored by the neighborhood group.

We create a word cloud to show the most common neighborhoods in the dataset.

Regression Analysis
--------------------

We drop the irrelevant columns from the dataset and encode the categorical variables 'neighborhood\_group' and 'room\_type'. We then calculate the correlation matrix between the encoded variables.

We create a linear regression model to predict the price of an Airbnb listing based on the other features in the dataset. We split the dataset into training and testing sets and train the model on the training set. We then evaluate the model on the testing set using the R2 score.

We also create a decision tree regression model to predict the price of an Airbnb listing and evaluate it using the R2 score.

Conclusion
----------

In this project, we performed an exploratory data analysis of the Airbnb NYC dataset and gained insights into the Airbnb market in NYC. We visualized the data using various plots and created a word cloud to show the most common neighborhoods. We also created regression models to predict the price of an Airbnb listing. The results of this analysis can be useful for Airbnb hosts and guests in NYC.
