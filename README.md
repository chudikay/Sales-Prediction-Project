# Sales-Prediction-Project

Coca cola Company is trying to find out if it’s advertising expenditure on various media channels (TV, Radio, and Newspaper) has an impact on its product sales. It decided to employ the services of a data consultant to solve this problem with particular interest in TV advertising.

STEP 1:  Exploratory data analysis

First, I imported all the required libraries -pandas, numpy, scikitlearn and matplotlib. Then, read the dataset into a dataframe and viewed the data frame to ensure it was in place. Next, I checked for data completeness and ensured that there were no NULL or missing data. I performed exploratory data analysis on the dataset to understand it’s characteristics. Here, I checked the measures of central tendency and dispersion like mean, median, mode, standard deviation, minimum and maximum values, the data types for the columns and row count.

STEP 2: Data cleaning

Independent variable or feature – TV, Radio or Newspaper
Dependent variable or label – Sales.
I did a scatter plot of one of the independent variables, TV and the dependent variable, Sales. This showed a linear relationship between the independent and dependent variables and then some outliers. Next, I removed the outliers by removing rows where they could be found.

STEP 3: Split the dataset into training and testing sets

I allotted 80% of the dataset to the training set and the remaining 20% to the testing set. These sets are responsible for training the machine learning model and evaluating the performance of the trained model.

STEP 4: Implement a linear regression model using Python’s scikit-learn

I created an instance of the linear regression model using the linear regression function provided by scikit-learn. Then, trained the model using the fit() function on the model object. Next, I applied R-squared metrics to find the coefficients of the linear equation that best fits the relationship between the feature and label. After training the model, I used it to make predictions on the dataset by calling the predict() method on the trained model object. 
