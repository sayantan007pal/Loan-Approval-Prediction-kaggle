# Loan-Approval-Prediction-kaggle
# Loan Eligibility Prediction

## Project Overview
This project aims to automate the loan eligibility process for a company based on customer details provided in online application forms. The goal is to identify customer segments eligible for loan amounts, allowing the company to target these customers specifically.

## Dataset
The project uses three datasets:
1. Training Dataset: Contains customer information and loan approval status.
2. Testing Dataset: Similar to the training set but without the loan approval status.
3. Sample Submission Dataset: Provides the format for submitting predictions.

### Features
- Loan_ID: Unique identifier for each loan application
- Gender: Male/Female
- Married: Applicant's marital status (Y/N)
- Dependents: Number of dependents
- Education: Graduate/Under Graduate
- Self_Employed: Self-employment status (Y/N)
- ApplicantIncome: Income of the applicant
- CoapplicantIncome: Income of the co-applicant
- LoanAmount: Requested loan amount (in thousands)
- Loan_Amount_Term: Term of loan in months
- Credit_History: Credit history meets guidelines
- Property_Area: Urban/Semi-Urban/Rural
- Loan_Status: (Target variable) Loan approved (Y/N)

## Setup and Installation
1. Ensure you have Python installed (preferably Python 3.x).
2. Install required libraries:

pip install numpy pandas scikit-learn

3. Clone this repository or download the Jupyter notebook and dataset files.

## Running the Notebook
1. Launch Jupyter Notebook.
2. Navigate to and open the `kaggle-loan-approval-prediction.ipynb` file.
3. Run each cell in the notebook sequentially.

## Project Structure
The notebook follows these main steps:
1. Data loading and exploration
2. Data preprocessing (handling missing values, encoding categorical variables)
3. Feature scaling
4. Model training (Logistic Regression and Random Forest)
5. Model evaluation and comparison
6. Final prediction on the test set
7. Submission file generation

## Model Evaluation
The models are evaluated using accuracy scores and classification reports. The better-performing model is selected for final predictions.

## Generating Predictions
After running all cells, the notebook will generate a 'Final_Submission.csv' file containing predictions for the test set.

## Evaluation Metric
The model's performance is evaluated based on the accuracy of loan status predictions for the test data.

## Note
Ensure all dataset files ('Training Dataset.csv', 'Test Dataset.csv', 'Sample_Submission.csv') are in the same directory as the Jupyter notebook for successful execution.
