# 🏦 Bank Loan Approval

## 📌 Project Overview
This project demonstrates how to **predict loan approval** based on various applicant features with a focus on **data preprocessing**, **feature engineering**, and **model evaluation**.

- 🧹 **Data Preprocessing** – techniques for handling missing values and encoding categorical variables
- 🔍 **Feature Engineering** – creation of new features to improve model performance
- 🤖 **Machine Learning** – trained classification models to predict loan approval with comprehensive evaluation metrics
- 🎯 **Goal** – develop an efficient and accurate loan approval prediction model while understanding the impact of preprocessing and feature engineering

## 📊 Dataset

[![Bank Loan Approval: Dataset](https://img.youtube.com/vi/n6Kdhp0xm2s/0.jpg)](https://youtu.be/n6Kdhp0xm2s)

[Bank Loan Approval: Dataset](https://youtu.be/n6Kdhp0xm2s)  

The Bank Loan Approval dataset contains applicant information with the following key features:
- Gender
- Marital Status
- Education Level
- Applicant and Co-applicant Income
- Loan Amount and Loan Term
- Credit History
- Property Area

Each record has an associated loan approval status (0: Not Approved, 1: Approved) which is the target variable for prediction.

## 🛠 Key Techniques Implemented

1. **Data Preprocessing**

[![Bank Loan Approval: Preprocessing](https://img.youtube.com/vi/Q9LIZ3uM298/0.jpg)](https://youtu.be/Q9LIZ3uM298)

[Bank Loan Approval: Preprocessing](https://youtu.be/Q9LIZ3uM298)  

   - Handling missing values for numerical and categorical features
   - Encoding categorical variables using one-hot encoding
   - Scaling numerical features for consistent model input
   - Data cleaning to ensure quality inputs for modeling

2. **Data Exploration & Visualization**

[![Bank Loan Approval: Data Exploration & Visualization](https://img.youtube.com/vi/9GLBDpNkpVI/0.jpg)](https://youtu.be/9GLBDpNkpVI)

[Bank Loan Approval: Data Exploration & Visualization](https://youtu.be/9GLBDpNkpVI)  

   - Distribution analysis of loan approvals
   - Statistical summary of numerical features
   - Visualization of feature distributions by loan approval status
   - Correlation analysis between applicant features

3. **Feature Engineering**

[![Bank Loan Approval: Feature Engineering](https://img.youtube.com/vi/M74m-THUv8g/0.jpg)](https://youtu.be/M74m-THUv8g)

[Bank Loan Approval: Feature Engineering](https://youtu.be/M74m-THUv8g)  

   - Creation of new features such as income-to-loan ratio
   - Transformation of skewed features for better model performance
   - Feature selection to identify the most relevant predictors

4. **Model Training & Evaluation**
   
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Comprehensive metrics:
     - Accuracy
     - Precision, Recall, and F1-Score
     - Confusion matrices for error analysis
   - Model comparison to identify the best approach

## 📈 Results
The analysis revealed that Random Forest generally performed better for loan approval prediction, with an accuracy of 89.5% compared to Logistic Regression's 85.2%.

Key findings:
- The most predictive features for loan approval were credit history and income-to-loan ratio
- Feature engineering significantly improved model performance
- Random Forest showed better performance particularly in recall for approved loans (82% vs 75%)
- Logistic Regression provided more interpretable results but struggled with non-linear relationships

## 📦 Requirements
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🚀 How to Use
1. Clone this repository
2. Ensure you have all required packages installed
3. Open the Jupyter notebook `Bank_Loan_Approval.ipynb`
4. Run the cells sequentially to see the analysis and results

## 📂 File Structure
- `Bank_Loan_Approval.ipynb` - The main Jupyter notebook containing all analysis and code
- `bank_loan_approval_dataset.csv` - The dataset file
- `README.md` - This file with project information

## 💡 Key Insights
- Credit history is the strongest predictor of loan approval, aligning with financial industry practices
- Feature engineering, such as income-to-loan ratio, can significantly enhance model performance
- Random Forest outperformed Logistic Regression, likely due to its ability to capture complex relationships in applicant data
- The models showed high accuracy but slightly lower recall for approved loans, suggesting potential for further optimization to reduce false negatives
- Class imbalance (fewer approved loans than not approved) impacts model performance and should be considered in real-world applications
