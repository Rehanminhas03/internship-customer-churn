# Customer Churn Internship Tasks

## Week 1 - Data Collection & EDA
- Loaded Telco Churn dataset
- Performed initial exploratory data analysis
- Visualized churn patterns

Dataset: [Download from Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Week 2 - Data Cleaning and Pre Processing

This week focuses on preparing the dataset for machine learning models by performing data cleaning and preprocessing tasks.  
The cleaned dataset will be used in future weeks for feature engineering and model building.

---

## **Objectives**
The key steps completed in Week 2 are:

1. **Handle Missing Values**  
   - Columns with more than 50% missing values were dropped.  
   - Remaining missing values were imputed using:
     - Median for numerical columns  
     - Mode for categorical columns  

2. **Encode Categorical Variables**  
   - **Label Encoding** was applied to binary categorical variables (e.g., `Yes/No`, `Male/Female`).  
   - **One-Hot Encoding** was used for categorical variables with more than two unique categories.  

3. **Standardize Numerical Features**  
   - Features like `tenure`, `MonthlyCharges`, and `TotalCharges` were scaled using **StandardScaler** to bring them to a similar scale.

4. **Split Dataset into Training and Testing Sets**  
   - The dataset was split into **80% training data** and **20% testing data** using `train_test_split`.  
   - This ensures proper model evaluation in later steps.

5. **Save Final Cleaned Dataset**  
   - The fully cleaned and processed dataset was saved as `Cleaned_Customer_Churn.csv`.

---

## **Folder Structure**


## Week 3 - Feature Engineering
...

## Week 4 - Model Building
...
