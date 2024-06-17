# Credit Card Fraud Detection


## Project Overview
Credit card fraud detection is a critical aspect of financial security. This project aims to develop a machine learning model capable of detecting fraudulent transactions from a dataset of credit card transactions. By leveraging advanced data analysis and machine learning techniques, the project seeks to minimize false positives and accurately identify fraudulent activities.


## Research Question
How can machine learning models be effectively used to detect fraudulent credit card transactions in a dataset, while minimizing false positives and maximizing detection accuracy?


## Dataset
The dataset used in this project is sourced from Kaggle and contains anonymized credit card transactions made by European cardholders in September 2013. It includes a total of 284,807 transactions, of which 492 are fraudulent. The dataset is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.


## Dataset Information
Source: Kaggle Credit Card Fraud Detection Dataset
Number of Transactions: 284,807
Number of Fraudulent Transactions: 492
Features: 30 features including Time, V1 to V28 (anonymized), Amount, and Class (target variable)


### Project Structure

...
credit-card-fraud-detection/

│
├── data/
│   ├── creditcard.csv             
│   └── processed/                  
│
├── notebooks/
│   ├── 01_data_exploration.ipynb   
│   ├── 02_preprocessing.ipynb      
│   ├── 03_model_training.ipynb     
│   ├── 04_model_evaluation.ipynb   
│   └── 05_real_time_implementation.ipynb  
│
├── src/
│   ├── data_preprocessing.py       
│   ├── feature_engineering.py      
│   ├── model_training.py           
│   ├── model_evaluation.py         
│   └── real_time_detection.py      
│
├── tests/
│   └── test_models.py              
│
├── images/
│   └── project_gantt_chart.png     
│
├── README.md                       
├── requirements.txt                
├── LICENSE                         
└── .gitignore                      


## Methodology
1.Data Collection and Exploration: Understanding the dataset, checking for imbalances, and visualizing transaction patterns.

2.Data Preprocessing: Handling missing values, scaling features, and splitting the dataset.

3.Exploratory Data Analysis (EDA): Identifying patterns and correlations within the data.

4.Feature Engineering: Creating new features to improve model performance.

5.Model Development and Training: Implementing machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.

6.Hyperparameter Tuning: Optimizing model parameters using techniques like Grid Search and Random Search.

7.Model Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

8.Real-Time Implementation: Integrating the model into a real-time system for detecting fraudulent transactions.

9.Testing: Ensuring the robustness and reliability of the model through rigorous testing.


## Prerequisites
To run this project, you will need the following software installed on your machine:


Python 3.7 or higher
Git
Python Libraries
Google Colab


## The project requires the following Python libraries:


pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
jupyter


## Installation
To run this project, you will need Python and the necessary packages listed in requirements.txt.


sh
pip install -r requirements.txt


Usage
1. Clone the repository:
sh
git clone https://github.com/Shefanasalim/credit-card-fraud-detection.git
cd credit-card-fraud-detection


2. Run the data preprocessing script:
sh
python src/data_preprocessing.py


3. Train the model:
sh
python src/model_training.py


4. Evaluate the model:
sh
python src/model_evaluation.py


5. For real-time fraud detection, run:
sh
python src/real_time_detection.py


## Results
The project aims to achieve a high detection rate for fraudulent transactions while maintaining a low false positive rate. The evaluation metrics and performance results will be detailed in the project documentation.


## License
This project is licensed under the Database Contents License (DbCL) v1.0


## Acknowledgements
The dataset used in this project is provided by Kaggle.
