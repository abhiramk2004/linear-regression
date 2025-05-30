Data Loading & Initial Exploration
 *Loads the dataset Housing.csv using pandas.
 *Generates a detailed Exploratory Data Analysis(EDA) report using ydata-profiling (formerly  pandas-profiling), saved as report.html.
Data Visualization
 *Uses matplotlib and seaborn to explore distributions, correlations, and feature relationships.
 *Helps identify patterns, trends, and potential multicollinearity.
Data Preprocessing
 *Applies standardization using StandardScaler.
 *Splits the data into training and test sets using an 80-20 split with train_test_split.
Model Building
 *Trains a Linear Regression model using scikit-learn.
 *Fits the model on training data and generates predictions for the test set.
Model Evaluation
 *Evaluates performance using the following metrics:
   -Mean Absolute Error (MAE): 
   -Mean Squared Error (MSE):
   -R² Score: 
Further Optimization
 *After identifying low-performing data points, a filtering step was introduced to remove rows that negatively impacted model performance.
 *R² Score significantly improved post-filtering, confirming that the removed rows were outliers or noise affecting model accuracy.
 *This insight led to better generalization and model reliability.
report.html: A complete profiling report of the dataset.
Printed evaluation metrics to assess model accuracy.

* pandas, matplotlib, seaborn for data manipulation and visualization
* ydata-profiling for automated EDA
* scikit-learn for data preprocessing, model training, and evaluation
