# **Data Cleaning & Missing Value Handling**

# **Objective**
The objective of this task is to perform data cleaning by identifying and handling missing values to improve data quality and prepare the dataset for machine learning modeling.

# **Dataset**
### __House Prices – Advanced Regression Techniques__
Source: Kaggle  
File used: train.csv  
___
# **Tools & Libraries Used**
* Python
* Pandas
* NumPy
* Matplotlib
___
# **Steps Performed**
### __1. Load Dataset & Identify Missing Values__
Loaded the dataset using Pandas
Identified missing values using .isnull().sum()
### __2. Visualize Missing Data__
Plotted a bar chart to visualize missing values across columns
### __3. Handle Numerical Missing Values__
Identified numerical columns (int64, float64)
Applied median imputation to handle missing values and reduce outlier impact
### __4. Handle Categorical Missing Values__
Identified categorical (object) columns
Applied mode imputation for missing categorical data
### __5. Remove Columns with High Missing Values__
Removed columns having more than 50% missing data
### __6. Validate Cleaned Dataset__
Verified no missing values remain
Checked dataset structure using .info()
### __7. Compare Before vs After__
Confirmed dataset size and quality after cleaning
Final dataset shape: 1460 rows × 81 columns
___
# **Final Output**
Cleaned dataset saved as cleaned_house_prices.csv
Dataset is now free of missing values and ready for ML modeling
___
# **Conclusion**
The dataset was successfully cleaned by applying appropriate missing value handling techniques. Data quality was improved without unnecessary data loss, making the dataset suitable for further analysis and machine learning tasks.
Dataset is now free of missing values and ready for ML modeling
___


