# Drug Regulatory Classification Model

This project predicts whether a drug is Regulated or Non-Regulated using Machine Learning.

### Dataset
- Columns used: Manufacturer, Drug Name, etc.
- Target Column: Target_Regulatory_Class

### Steps Performed
1. Data Cleaning & Dropping high-cardinality columns
2. Encoded Categorical Features using get_dummies
3. Encoded Target Column using LabelEncoder
4. Train-Test Split
5. Model Training - Logistic Regression & Random Forest

### Model Results
- Random Forest Accuracy: 50.36%
- Classification Report includes Precision, Recall, F1-Score

### Tech Stack
Python, Pandas, Scikit-Learn, Jupyter Notebook

### How to Run
1. Clone the repo
2. Open Model_Train.ipynb
3. Run all cells

Created by Mayuri More
