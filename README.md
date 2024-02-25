## Telcommunication Customer Churn
-------

This PySpark code involves the exploration and analysis of telecommunications data with the goal of predicting customer churn. It covers essential steps like data loading, transformation, feature engineering, and logistic regression modeling. The logistic regression model is used to predict customer churn based on various features. The accuracy of the model is evaluated,and it has an accuracy of 8 and predictions are made on a new dataset. 

This code can be a part of a larger churn prediction and analysis pipeline in the telecommunications domain, helping businesses understand and address customer retention challenges.

**Code Summary:**

The provided PySpark code involves the following steps:

1. **Data Loading:**
   - Connects to IBM Cloud Object Storage (COS) to load a CSV file containing telecommunications data into a PySpark DataFrame.

2. **Data Exploration and Transformation:**
   - Displays the schema and top rows of the DataFrame.
   - Performs operations like dropping columns, changing data types, and creating a new DataFrame (`d1`).


3. **Descriptive Statistics:**
   - Displays basic statistics and information about the dataset.


4. **Feature Engineering:**
   - Creates a feature vector using selected columns.

5. **Logistic Regression Model:**
   - Splits the data into training and testing sets.
   - Fits a logistic regression model on the training data and evaluates it on the testing data.


6. **Model Evaluation and Prediction:**
   - Uses an evaluator to calculate accuracy and makes predictions on a new dataset.




