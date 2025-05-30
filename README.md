1. Data Loading & Initial Exploration
 * Loads the dataset Housing.csv using pandas.
 * Generates a detailed Exploratory Data Analysis(EDA) report using ydata-profiling (formerly  pandas-profiling), saved as report.html.
2. Data Visualization
 * Uses matplotlib and seaborn to explore distributions, correlations, and feature relationships.
 * Helps identify patterns, trends, and potential multicollinearity.
3. Data Preprocessing
 * Applies standardization using StandardScaler.
 * Splits the data into training and test sets using an 80-20 split with train_test_split.
4. Model Building
 * Trains a Linear Regression model using scikit-learn.
 * Fits the model on training data and generates predictions for the test set.
5. Model Evaluation
 * Evaluates performance using the following metrics:
   - Mean Absolute Percentage Error (MAE): 8.013308488415326
   - Mean Squared Error (MSE): 185859186550.58057
   - R² Score: 0.9339058586124845 
6. Further Optimization
 * After identifying low-performing data points, a filtering step was introduced to remove rows that negatively impacted model performance.
 * R² Score significantly improved post-filtering, confirming that the removed rows were outliers or noise affecting model accuracy.
 * This insight led to better generalization and model reliability.
7. report.html: A complete profiling report of the dataset.
8. Printed evaluation metrics to assess model accuracy.
* pandas, matplotlib, seaborn for data manipulation and visualization
* ydata-profiling for automated EDA
* scikit-learn for data preprocessing, model training, and evaluation
