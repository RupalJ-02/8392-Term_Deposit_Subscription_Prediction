# Term_Deposit_Subscription_Prediction

Predicting Term Deposit Subscriptions Using Machine Learning

Overview

This project focuses on data-driven decision-making for bank telemarketing campaigns. Using machine learning techniques, the goal is to predict whether a customer will subscribe to a term deposit (Yes/No), optimizing telemarketing efforts and enhancing marketing efficiency.

Authors
	•	Rupal Jha
	•	Jyoti Bhardwaj

Objective

Predict if a customer will subscribe to a term deposit based on their demographic, contact, and campaign data.

Dataset
	•	Source: Direct marketing campaigns of a Portuguese bank.
	•	Training Data: 40,000 rows, 17 columns.
	•	Test Data: 5,211 rows, 16 columns.

Key Features:
	1.	Client Data: Age, job, marital status, education, loan status, balance.
	2.	Contact Details: Last contact type (cellular/telephone), day, month, duration.
	3.	Campaign Performance: Number of contacts, previous outcomes (poutcome).

Approach

Workflow
	1.	Define the Problem: Identify customers most likely to subscribe to optimize telemarketing.
	2.	Data Cleaning and Exploration: Handling missing values and analyzing trends using Python libraries.
	3.	Feature Engineering: Transforming categorical variables and scaling numerical data.
	4.	Model Selection and Tuning: Tested multiple models, with Random Forest selected as the final model.
	5.	Evaluation: Accuracy, F1-Score, and ROC-AUC were the primary metrics for evaluation.

Key Insights from EDA
	1.	Patterns:
	•	Most calls were made in May and July.
	•	Only 7.24% of customers subscribed (high class imbalance).
	2.	Customer Trends:
	•	Single customers had higher subscription rates (9.4%) compared to married ones (6.1%).
	•	Contact via cellular led to higher subscriptions (8.96%).

Model Performance
	•	Final Model: Random Forest
	•	Metrics:
	•	Accuracy: 93%
	•	Precision (Yes class): 64%
	•	Recall (Yes class): 6%
	•	F1-Score: 0.11 (Improved to 0.37 after tuning)
	•	ROC-AUC: 0.53

Business Impact
	1.	Improved targeting reduces marketing costs.
	2.	Enhanced conversion rates by focusing on likely subscribers.
	3.	Key recommendations:
	•	Prioritize customers with successful previous outcomes and high balances.
	•	Optimize call duration for better results.
	•	Minimize over-contacting unresponsive customers.

Future Scope
	•	Addressing Class Imbalance: Techniques like oversampling or undersampling can improve recall.
	•	Model Optimization: Experiment with advanced models (e.g., Gradient Boosting).
	•	Enhanced Feature Engineering: Explore new or transformed features for better classification.

Usage

Requirements
	•	Python (3.8+)
	•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Steps to Run:
	1.	Clone this repository.

git clone <repository-url>
cd <repository-folder>


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Run the notebook/script for data preprocessing, modeling, and evaluation.

Acknowledgments

This project was inspired by bank marketing datasets available in the public domain. Special thanks to all contributors for their insights and support.
