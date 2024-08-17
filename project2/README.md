# Credit Card Approval Prediction Project

## Overview

This project aims to predict whether a credit card applicant will be classified as a 'good' or 'bad' client based on their historical application and credit record data. The project leverages machine learning models, including Random Forest and Neural Networks, to make predictions that help financial institutions minimize defaults while optimizing credit allocation.

## Project Structure

The project consists of the following key components:

- **data/raw/**: Contains the raw datasets used in the project (`application_record.csv`, `credit_record.csv`).
- **data/processed/**: Contains the processed datasets after data cleaning and feature engineering.
- **models/**: Contains the trained machine learning models (`credit_approval_rf_model.pkl`).
- **nProject2/**: Contains Jupyter notebook used for data exploration, preprocessing, feature engineering, and model training and data interpretation and business analysis.
  
## Key Features

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables using one-hot encoding.
   - Merging application and credit datasets.
   
2. **Feature Engineering**:
   - Created new feature `Income_Per_Family_Member` to represent the financial burden on the client.
   
3. **Model Training**:
   - **Random Forest Classifier**: Achieved high accuracy in predicting 'good' clients but struggled with identifying 'bad' clients due to class imbalance.
   - **Neural Network**: Also achieved high accuracy but faced similar challenges in predicting 'bad' clients.
   
4. **Model Evaluation**:
   - Both models were evaluated based on accuracy, precision, recall, and f1-score.
   - Insights were drawn to highlight the need for improving the detection of 'bad' clients.

## Installation

1. Clone the repository,
2. Navigate to the project directory,
3. Create a virtual environment,
4. Install the required dependencies,
    pip install -r requirements.txt
5. Launch jupyter notebook


## Team Members & Videos 
@huixincai   https://youtu.be/WgC0aezI-Jw?si=9zcU5WnvQLTMVFYV

@rafaelperez @khollah1 @whisperfool

