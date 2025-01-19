# Term_Deposit_Subscription_Prediction
# DA-Group 22-8392

## 📊 Predicting Term Deposit Subscriptions Using Machine Learning

A data-driven project to optimize bank telemarketing campaigns.

Authors:
• Rupal Jha • Jyoti Bhardwaj
Date: January 18, 2025

### 🔍 Objective

Predict if a customer will subscribe to a term deposit (Yes/No) based on their demographic, contact, and past campaign performance data. This helps optimize telemarketing efforts, improve conversion rates, and reduce costs.

### 📂 Dataset Overview
- Source: Marketing campaigns of a Portuguese bank.
- Train Data: 40,000 rows, 17 columns.
- Test Data: 5,211 rows, 16 columns.

### Key Features
- Client Information:
Age, job, marital status, education, loan status, and account balance.
- Contact Details:
Last contact type (cellular/telephone), day, month, and duration.
- Campaign Metrics:
Number of contacts, previous outcomes (poutcome).

### 🚀 Project Workflow

1. Problem Definition

Identify customers most likely to subscribe (Yes) to reduce inefficiencies in telemarketing campaigns.

2. Data Preprocessing
   
- Handled missing values.
- Performed feature engineering (e.g., one-hot encoding for categorical variables).
- Scaled numerical features for uniformity.

4. Exploratory Data Analysis (EDA)
- Subscription Trends:
- 7.24% of customers subscribed (Yes).
- Single customers had higher subscription rates (9.4%) compared to married ones (6.1%).
- Cellular contact method had a higher success rate (8.96%).
- Outlier Insights:
- Balance: Significant outliers above ₹3,216.
- Call duration: Outliers exceeding 632 seconds.

5. Model Selection
- Tested Models:
- Logistic Regression
- Random Forest
- Gradient Boosting (XGBoost, LightGBM)
- Final Model Chosen: Random Forest
  Balanced accuracy, interpretability, and speed.

6. Evaluation Metrics
- Accuracy: 93%
- F1-Score (Tuned): 0.37
- Precision (Yes class): 64%
- Recall (Yes class): 6%

### 📊 Key Visualizations
- Distribution of the subscription variable (Yes/No).
- Subscription rates by job and education levels.
- Impact of previous outcomes (poutcome) on subscription likelihood.

### 💡 Business Impact
- Better Targeting: Focus on customers with higher balances and successful past campaign outcomes.
- Cost Reduction: Reduce repetitive, ineffective calls to unresponsive customers.
- Improved Efficiency: Optimize call durations to maximize engagement.

### 🔧 Future Scope
- Class Imbalance Handling:
Techniques like oversampling, undersampling, or cost-sensitive learning to improve recall.
- Enhanced Features:
Introduce or transform features to improve classification performance.
- Model Experimentation:
Explore advanced models and fine-tune hyperparameters.

### 📦 Installation
1.	Clone the repository:

git clone <repository-url>
cd <repository-folder>


2.	Install dependencies:

pip install -r requirements.txt

⚙️ Usage
- Run the Jupyter Notebook or Python script for:
- Data preprocessing
- Model training
- Evaluation and visualization
- Evaluate model outputs for actionable insights.

### 👥 Acknowledgments

This project uses publicly available data from Portuguese bank marketing campaigns. Special thanks to contributors and community members for their guidance.
