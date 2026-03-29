# Loan_Approval_System
Fundamentals of AI and ML Evaluated Course Project

# Overview of the project
Loan Approval Sysytem is a Machine Learning-based system designed to automate the loan eligibility process. Using historical data, the project predicts whether a loan application will be approved or rejected based on applicant profiles (Income, Credit History, Education, etc.). This project aims to help financial institutions reduce manual errors and speed up decision-making.

# Features
1.Data Cleaning: Handles missing values and encodes categorical data for ML processing.

2.Exploratory Data Analysis (EDA): Deep dive into factors affecting loan status using Seaborn/Matplotlib.

3.Predictive Modeling: Uses a Random Forest Classifier for high-accuracy predictions.

4.Model Persistence: The trained model is saved as a .pkl file for real-time deployment.

# Technologies/Tools used
1.Language: Python 3.x

2.Libraries: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

3.Environment: Google Colab / VS Code

4.Deployment Ready: Model saved using joblib

# System Prerequisites
1.Python 3.8 or higher: The system is built using Python 3. This is required to handle the latest versions of Scikit-Learn and Pandas.

2.Execution Platforms (Choose One)

(i)Google Colab: No local installation required.

(ii)VS Code: Install the "Python" and "Jupyter" extensions for a professional local setup.

(iii)Jupyter Notebook: A standard tool for running and documenting data science experiments.

# Steps to Install & Run the Project
1.Clone the project: git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

2.Install dependencies: pip install -r requirements.txt

3.Run the notebook: Open LoanApproval.ipynb in your preferred editor (VS Code or Colab) and run all cells.

# Instructions for testing
1.Accuracy Check: Run the evaluation cells to see the Random Forest accuracy score.

2.Manual Test Case: Use the bottom cell to input custom data and check for "Approved" or "Rejected" labels.

3.Model Integrity: Verify that loan_approval_prediction.pkl is generated after running the training code.

4.Data Validation: Ensure loan_data.csv is uploaded and readable without path errors.
