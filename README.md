## EDA on Titanic & Iris Datasets with Logistic Regression

# Titanic Dataset Summary

* Performed EDA and cleaned the data by dropping irrelevant columns (Name, Ticket, etc.).
* Converted categorical features (Sex, Embarked) using one-hot encoding.
* Split the data into features (X) and target (y = Survived).
* Trained a Logistic Regression model.
* Achieved about 80.5% accuracy on the test set.
* Evaluated the model using a classification report (precision, recall, F1-score).

# Iris Dataset Summary

* Loaded the Iris dataset and cleaned it by renaming columns and dropping the ID column.
* Performed Univariate Analysis to explore individual feature distributions like sepal_length across species.
* Used Bivariate Analysis (scatter plots with FacetGrid) to examine relationships between two features (petal_length vs sepal_width) by species.
* Applied Multivariate Analysis using sns.pairplot() to visualize relationships across all numeric features, helping to distinguish between the three flower species.
  
