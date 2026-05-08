# carprice_model
Car Price Prediction (Linear Regression)

A machine learning project using Python and Scikit-Learn to predict car resale prices based on mileage and age. Includes data visualization and a Linear Regression model.

This project demonstrates a simple yet effective application of Linear Regression to predict the resale value of cars. By analyzing historical data, the model learns the relationship between a car's physical attributes and its market price.

Summary of WorkflowData Acquisition: 
1. Loads a dataset (carprices.csv) containing mileage, age, and selling price.
2. Exploratory Data Analysis:
     i. Visualized the negative correlation between Mileage and Price.
     ii. Visualized the negative correlation between Car Age and Price.
3. Data Splitting: Used an 80/20 train-test split with a fixed random_state to ensure reproducible results.
4. Modeling:
     i. Algorithm: Multiple Linear Regression.
     ii. Features ($X$): Mileage, Age(yrs).
     iii. Target ($y$): Sell Price($).
5. Evaluation: Predicted values on unseen test data and calculated the model's accuracy score.
  
Tech StackLanguage: 
1. Python
2. Libraries:
     i. Pandas: For data manipulation.
     ii. Matplotlib: For data visualization.
     iii. Scikit-Learn: For model training (LinearRegression) and data splitting (train_test_split).

Key Insights
1. The model accounts for multiple variables simultaneously, allowing for a more accurate price estimation than a single-variable model.
2. Fixed random_state implementation ensures that the model training process remains consistent across different runs.

How to RunClone the repository.
1. Ensure carprices.csv is present in the root directory.
2. Open carprice_model.ipynb in Jupyter Notebook or VS Code.
3. Execute the cells sequentially to see the visualization and model results.
