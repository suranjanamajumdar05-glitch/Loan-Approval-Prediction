# Project Overview
This project predicts whether a loan application will be approved or not using Machine Learning classification algorithms. The model is trained using applicant details such as income, loan amount, credit score, employment status, and loan term.
The main objective of this project is to automate the loan approval process and compare the performance of multiple ML algorithms.

# Dataset Information
The dataset contains the following features:
Age - Applicant age
Income - Applicant income
Credit_Score - Credit score of applicant
Loan_Amount - Requested loan amount
Loan_Term - Duration of loan
Employment_Status - Employment type/status
Loan_Approved - Target variable

# Machine Learning Techniques Used
## Data Preprocessing
1. Removed duplicate values
2. Checked missing values
3. Label Encoding for categorical data
4. Feature Scaling using StandardScaler
## Exploratory Data Analysis
The following analyses were performed:
1. Dataset statistics
2. Distribution checking
3. Confusion Matrix visualization
4. Accuracy comparison graph

# Models Used
1. Logistic Regression
A linear classification algorithm used as the baseline model.
2. Decision Tree Classifier
A tree-based classification algorithm for decision making.
3. Random Forest Classifier
An ensemble learning method combining multiple decision trees.

# Technologies Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn

# Confusion Matrix
<img width="539" height="453" alt="image" src="https://github.com/user-attachments/assets/1c577b15-2a3d-4aca-8034-4af4136876fa" />

# Accuracy Comparison Graph
<img width="695" height="468" alt="image" src="https://github.com/user-attachments/assets/c5081b66-677b-4e21-ba83-59fe470d8f47" />

# Conclusion
This project successfully predicts loan approval status using supervised machine learning algorithms. Different classification models were compared, and Random Forest along with Decision Tree achieved the highest accuracy on the dataset.
