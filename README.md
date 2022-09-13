# House-Prices-Prediction
A machine learning project aimed to predict house prices using advanced regression techniques.

## Description
A machine learning project aimed at predicting house prices using adavanced regression techniques like elastic net regression, gradient boost regression, xgboost regression, and others.

## Dataset
House Prices Prediction dataset from Kaggle

## Tools Used
* **Pandas**
* **Numpy**
* **Matplotlib**
* **Seaborn**
* **Scipy**
* **Sklearn**

## Steps Involved / Methodology
* Data Exploration
* Data Preprocessing
  * Exploring the target variable.
  * Determining missing values in the dataset.
  * Determining relevant features through pearson correlation coefficient.
  * Visualizing the features.
  * Handling missing values.
  * Data Formatting i.e. ensuring that all the columns have valid datatypes.
  * Feature Engineering i.e. creating some new features from the existing ones.
  * Dummy Encoding i.e. converting categorical variables to numeric ones.
  * Observing skeweness in the numeric features.
  * Determining the best transformation for the given dataset.
  * Performing log transformation on the numeric features.
  * Visualizing distribution of target variable using Q-Q plots before & after transformation.
  * Exporting the processed data to CSV files.

* Model Development.
  * Hyperparameter tuning through grid search.
  * Optimizing the model using the best parameters and fitting again.
  * Evaluating model's performance.
  * Visualizing model's performance by plotting the predicted values against the actual values.
* Model Persistance.
  * Saving the trained model to a joblib file so that it doesn't have to be trained again.

## Note
This was my first machine learning project and I learned a lot while working on it. I'm sure that there's still a lot to improve here so I'll continue to work on this project going forward into the future.
Your feedback or contributions if any will be appreciated.
