# Customer Churn Prediction

Predict and analyze customer churn using Python. This project demonstrates an end-to-end workflow including data preprocessing, feature engineering, exploratory data analysis (EDA), and machine learning models to identify customers likely to leave.

## Dataset
The dataset contains information about Telco customers, including demographics, account details, and subscribed services. The target variable `Churn` indicates whether a customer left in the last month.  

**Dataset Source:** [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### Key Features
- Customer demographics: gender, age range, partner/dependent status  
- Account information: tenure, contract type, payment method, paperless billing, monthly charges, total charges  
- Services: phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV/movies  

## Libraries Used
- `pandas` – data manipulation  
- `matplotlib` & `seaborn` – visualization  
- `scikit-learn` – machine learning  

## Algorithms Implemented
- Logistic Regression  
- Random Forest  
- CatBoost  

## Project Workflow
1. **Data Preprocessing:** Handle missing values, encode categorical variables  
2. **Exploratory Data Analysis (EDA):** Understand distributions, correlations, and patterns  
3. **Feature Engineering:** Create meaningful features and scale/transform data as needed  
4. **Model Training & Evaluation:** Train models, evaluate using metrics like accuracy, precision, recall, F1-score, and confusion matrix  
5. **Insights:** Identify key factors influencing churn and suggest business actions  

## How to Run
1. Clone this repository:  
```bash
git clone https://github.com/AmolBansal26/Customer-Churn-Prediction-Analysis--Classification.git
