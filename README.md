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

# Week 3 - Visualization and Feature Engineering

In Week 3, we dive deeper into the **Telco Customer Churn dataset** to gain meaningful insights and improve our data for modeling.  
This week involves **cleaning the raw dataset again**, creating **advanced visualizations**, performing **feature engineering**, and applying **dimensionality reduction techniques (PCA)** to prepare the dataset for machine learning in Week 4.

---

## **Objectives**
The main goals for Week 3 are:

1. **Load and Clean the Raw Dataset**
   - Handle missing values in numerical and categorical features.
   - Convert `TotalCharges` to a numeric type.
   - Encode categorical variables using:
     - **Label Encoding** for binary categories.
     - **One-Hot Encoding** for multi-class categories.
   - Scale numerical features (`tenure`, `MonthlyCharges`, `TotalCharges`) using **StandardScaler**.

2. **Advanced Visualizations**
   - **Correlation Heatmap** to identify relationships between features and churn.
   - **Histograms** to compare churn vs. non-churn customers.
   - **Bar Plots** for churn comparison across demographics (e.g., gender, contract type).

3. **Feature Engineering**
   - Create new features to improve model predictions:
     - `EngagementScore` → tenure × TotalCharges
     - `AvgMonthlyCharges` → TotalCharges ÷ tenure
     - `TotalServices` → Sum of all subscribed services
     - `CostPerService` → TotalCharges ÷ TotalServices
   - Combine and transform existing variables to generate meaningful predictors.

4. **Dimensionality Reduction (PCA)**
   - Apply **Principal Component Analysis (PCA)** to reduce feature space for visualization and modeling efficiency.

5. **Save Refined Dataset**
   - Save the cleaned and engineered dataset as:
     ```
     Refined_Customer_Churn.csv
     ```
   - This dataset will be used in Week 4 for machine learning model building.

---

## **Folder Structure**
Your Week 3 folder should look like this:



## Week 4 - Model Building
...
