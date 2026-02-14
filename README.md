🚀 Customer Churn Prediction using Machine Learning
📌 Project Overview

Customer churn is a major challenge in telecom and subscription-based businesses. This project aims to analyze customer behavior and build a machine learning model to predict whether a customer will churn or not.

By identifying high-risk customers in advance, businesses can take proactive steps to improve retention and reduce revenue loss.

🎯 Objective

Identify customers likely to churn

Analyze key factors influencing churn

Build a predictive machine learning model

Generate business insights for retention strategies

📊 Dataset Description

The dataset contains telecom customer information including:

Demographic details (Gender, Senior Citizen, Partner, Dependents)

Account information (Tenure, Contract Type, Monthly Charges, Total Charges)

Services (Internet Service, Online Security, Tech Support, Streaming)

Payment Method

Target Variable: Churn (Yes/No)

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Random Forest Classifier

Jupyter Notebook

⚙️ Data Preprocessing

Checked and handled missing values

Applied Label Encoding to categorical variables

Split dataset into training (75%) and testing (25%)

🤖 Model Used
Random Forest Classifier

n_estimators = 50

max_depth = 3

Random Forest was chosen because it reduces overfitting and provides stable predictions for structured data.

📈 Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

F1-Score

The model successfully identifies high-risk customers with good prediction performance.

🔍 Key Insights

Month-to-month contract customers have higher churn risk

Customers with short tenure are more likely to churn

High monthly charges increase churn probability

Long-term contract customers show lower churn rates

💡 Business Recommendations

Promote long-term contracts

Offer loyalty rewards to new customers

Provide special offers to high-risk customers

Bundle additional services like security & support

📁 Project Structure
Customer_Churn/
│
├── customer_churn.ipynb
├── Report_Customer churn.pdf
└── README.md

📌 Conclusion

This project demonstrates how machine learning can be applied to solve real-world business problems. By predicting churn in advance, companies can improve customer retention and increase profitability.

👨‍💻 Author

Anup
Machine Learning Enthusiast
