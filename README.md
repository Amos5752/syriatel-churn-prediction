📊 Predicting Customer Churn at SyriaTel
🔹 Overview

Customer churn is a major challenge for telecom companies like SyriaTel. Acquiring new customers is costly, while retaining existing ones is more profitable. The goal of this project is to predict which customers are likely to stop doing business with SyriaTel, enabling the company to take proactive retention measures.

🔹 Business and Data Understanding

Stakeholders: SyriaTel’s business leadership, customer success teams, and marketing/retention departments.

Business Need: Reduce customer churn, increase loyalty, and save revenue lost to competitors.

Dataset:

Contains 3,300+ customer records

Key features include: call usage (day/evening/night/international), service plan subscriptions, customer service interactions, and churn status (True/False).

Target Variable: churn (whether a customer has left).

🔹 Modeling

We applied classification models to predict churn:

Logistic Regression (baseline)

Random Forest

XGBoost

Methodology:

Preprocessed data (cleaning, encoding categorical variables, handling imbalance with SMOTE).

Split dataset into training and testing sets.

Trained and tuned multiple models.

Compared performance using Accuracy, Precision, Recall, and F1-score.

🔹 Evaluation

Logistic Regression: 76% accuracy, weaker recall (missed many churners).

Random Forest: 94% accuracy, strong balance of precision and recall.

XGBoost: 94% accuracy, best recall for churn cases (found more at-risk customers).

Key Findings:

Customers with international plans and those making frequent service calls are much more likely to churn.

Models successfully identified about 70% of customers who left, allowing for early intervention.

🔹 Conclusion

Machine learning can effectively predict churn at SyriaTel, enabling proactive retention strategies.

The best-performing models (Random Forest & XGBoost) provide reliable early warnings.

Acting on these insights can help SyriaTel reduce churn, cut acquisition costs, and boost customer satisfaction.
