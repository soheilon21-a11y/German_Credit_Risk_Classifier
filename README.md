# 🏦 Agent-Driven Binary Classification for Financial Credit Risk

This project presents an Agent-Driven Machine Learning workflow to predict credit risk using the German Credit Data. The model is built to classify loan applicants as either 'Good Risk' or 'Bad Risk,' a crucial task in FinTech.

## 🎯 Project Goal
To develop a robust binary classification model that maximizes the identification of high-risk customers, prioritizing metrics like *Recall* and *F1-Score* for the minority class ('Bad Risk').

## 🛠 Technology Stack
- *Agent Framework:* AI Agent-Driven Development
- *Languages:* Python
- *Libraries:* Pandas, NumPy, Scikit-learn
- *Modeling:* Logistic Regression, Random Forest

## 📈 Key Results & Model Performance

The data was found to be highly imbalanced (70% Good Risk / 30% Bad Risk). After training Logistic Regression and Random Forest models, the following results were obtained for the critical 'Bad Risk' class (Class 1):

| Model | Accuracy (Overall) | F1-Score (Bad Risk) | Recall (Bad Risk) |
| :--- | :--- | :--- | :--- |
| *Logistic Regression* | 78.50% | *0.60* | 0.53 |
| *Random Forest* | 77.00% | 0.50 | 0.38 |

### Conclusion
*The Logistic Regression model was selected as superior* due to its higher F1-Score (0.60) in identifying the minority class ('Bad Risk'). This indicates a better balance between precision and recall, which is paramount for financial risk assessment. Future work should focus on data augmentation techniques like SMOTE or cost-sensitive learning to improve the model's ability to capture all instances of bad risk.
