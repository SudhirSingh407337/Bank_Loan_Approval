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
