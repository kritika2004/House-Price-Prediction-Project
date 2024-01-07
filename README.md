# House-Price-Prediction-Project

# **Problem Statement**
The problem addressed in this project is housing price prediction. Home buyers often consider various factors beyond just the number of bedrooms or kitchen layout. The challenge is to develop a predictive model that takes into account multiple features and accurately predicts the final price of residential homes.

# **Abstract**
This project aims to predict the final price of residential homes in Ames, Iowa, utilizing a dataset with 79 explanatory variables. The prediction model is built using machine learning techniques, with a focus on exploring PySpark for data analysis.

# **Dataset Description**
The dataset contains information about various aspects of residential homes, including zoning classification, lot size, street type, alley access, and many other features. The goal is to develop a machine learning model that accurately predicts the sale price of houses based on these features.
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/

# **Data Analysis**
The project involves data preprocessing steps, such as handling missing values and converting categorical variables into numerical format. Exploratory data analysis is performed using both PySpark for scalable data processing and Scikit-Learn for traditional machine learning tasks. Visualization is done with Python libraries like Matplotlib and Seaborn.

![image](https://github.com/kritika2004/House-Price-Prediction-Project/assets/112310702/311fb8d3-77d0-4e1f-bc62-ff96a429f00b)

**Key Observations:**

Zone 3 has the highest frequency of properties: This suggests that Zone 3 is the most prevalent zoning type in the dataset, indicating it covers a significant portion of the area under study.
Zone 0 and 2 have the lowest frequency of properties: This implies that Zone 0 and 2 are less common, potentially covering a smaller area or having more restrictive regulations.
The distribution of properties across zones is not uniform: There's a clear pattern in the distribution, suggesting that zoning regulations play a significant role in shaping the development of properties in the area

![image](https://github.com/kritika2004/House-Price-Prediction-Project/assets/112310702/e0cef593-ee3a-464d-9093-817defc4d732)

**Interpretation:**

The distribution of sale prices provides insights into the housing market characteristics, such as:
Affordability: The concentration of houses in the lower price range suggests that a significant portion of the market caters to buyers with lower budgets.
Price variability: The wide range of prices indicates that there are options available for different income levels and preferences.
Potential market segmentation: The distinct peak in the distribution might suggest that there's a particularly common or desirable price point for houses in this market.


# **Machine Learning Model**
A Random Forest Regressor is chosen as the machine learning model for predicting house prices. The model is trained on the training dataset and validated on the test dataset.



# **Results and Interpretation**
The project provides a summary of statistics for the dataset, including mean, standard deviation, minimum, and maximum values for each feature. Additionally, the machine learning model predicts house prices for the test dataset, and the root mean squared error (RMSE) on the training dataset is calculated for model evaluation.
RMSE on the training dataset: 11450.296499486678




# **Setup and Run**
Clone the repository.
Install the required dependencies (pandas, matplotlib, seaborn, scikit-learn, pyspark).
Run the provided Python scripts for data analysis and machine learning model training.
Data Preprocessing
Handle missing values and convert categorical variables into numerical format using the provided Python script.

Model Training
Train the Random Forest Regressor model on the training dataset and evaluate its performance on the test dataset.

Results
Review the predicted house prices for the test dataset and analyze the RMSE on the training dataset for model evaluation.
