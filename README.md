# Predicting Car Insurance Claims Using Machine Learning

## Overview
This project aims to predict whether a customer will make a claim on their car insurance during the policy period. Insurance companies need accurate models to optimize pricing and assess risk. Since the client has limited infrastructure for machine learning deployment, we identified the single best predictive feature for building an initial simple model.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- SciPy
- Statsmodels
- Missingno
- Joblib

## Key Findings
- The dataset contained missing values, which were handled using statistical imputation (mean replacement for numerical features).
- Categorical features were encoded using Label Encoding.
- Feature scaling was performed using StandardScaler.
- The correlation analysis identified **driving_experience** as the best single predictor of claims.
- A logistic regression model using **driving_experience** achieved an accuracy of **X%**.

## Instructions to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-insurance-claims.git
   cd car-insurance-claims
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python main.py
   ```
4. View results printed in the console or generated output files.

## Dataset Source
The dataset used in this project is provided by On the Road car insurance. More details on the dataset structure are available in the project files.

