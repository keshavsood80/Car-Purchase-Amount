# Car Purchase Prediction
## Project Overview:
- **Client** : Automobile company
- **Objective**: Develop a predictive model for estimating customers' willingness to pay for a new car. This information will be used by the company to do the targeted marketing based on the customer profile.

You are given the following attributes:
-	Customer Name
-	Customer e-mail
-	Country
-	Gender
-	Age
-	Annual Salary 
-	Credit Card Debt 
-	Net Worth (Asset – Liabilities)

The model should predict: 
-	How much customers are willing to pay (Car_purchase_prediction) for the new vehicle?

## Dataset Overview
- **Data Source**: [Car_Purchasing_Data](https://github.com/keshavsood80/Car-Purchase-Amount/blob/main/Car_Purchasing_Data%20(1).csv)
- **Data Types**: Demographic (Country, Gender, Age) and Financial (Salary, Credit Card Debt, Net Worth).
- **Dataset Size**: Approximately 50,000 rows of data.

## Agenda
- Step 1: Import Libraries
- Step 2: Import Dataset 
- Step 3: Exploratory Data Analysis
- Step 4: Univariate Data Analysis
- Step 5: Bi-variate Analysis
- Step 6: Data Preparation
- Step 7: Modelling
- Step 8: Evaluate Performance

## Methodology:
### 1.	Data Collection and Preprocessing:
-	Collected a comprehensive dataset encompassing diverse customer attributes.
-	Conducted thorough data cleaning to handle missing values, outliers, and inconsistencies.
### 2.	Feature Engineering:
-	Segregated data into demographic and financial categories to facilitate targeted analysis.
-	Engineered relevant features to enhance the predictive capabilities of the model.
### 3.	Regression Modeling:
-	Framed the problem as a regression task, given the goal of predicting a continuous variable (total amount customers are willing to pay).
-	Implemented regression algorithms, leveraging the Scikit-learn library.
### 4.	Train-Test Split:
-	Utilized the test-train split technique with a split ratio of 70% training data and 30% testing data (35,000 and 15,000 rows, respectively).
### 5.	Evaluation Metrics:
-	Employed standard regression metrics, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared, to evaluate model performance.
### 6.	Targeted Marketing Insights:
-	The model's predictions empowered the company to strategically target marketing efforts based on individual customer profiles.
-	Provided valuable insights into the key drivers influencing customers' willingness to pay.


## Results and Impact:
-	Achieved a robust predictive model with significant accuracy in estimating customers' willingness to pay for a new car.
-	The insights gained from the model facilitated the creation of targeted marketing campaigns, optimizing resource allocation and enhancing customer engagement.
-	Contributed to a data-driven approach in the marketing domain, aligning strategies with individual customer preferences.

## Technologies Used:
-	Programming Language: Python
-	Libraries/Frameworks: Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn
-	Tools: Jupyter Notebooks, GitHub


# Notebook
- **Google Collab** : [Car_purchase_prediction.ipynb](https://github.com/keshavsood80/Car-Purchase-Amount/blob/main/Car_purchase_prediction.ipynb)





