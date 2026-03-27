# Loan-Default-Risk-with-Business-Cost-Optimization

## Task Objective

The objective of this project is to predict the likelihood of loan default and optimize decision-making using cost-based analysis. Instead of relying solely on accuracy, the model is evaluated based on business impact by assigning costs to incorrect predictions and selecting an optimal classification threshold.

## Approach

The project follows a structured machine learning workflow:

## Data Understanding & Exploration

Loaded and explored the Home Credit Default Risk dataset.
Analyzed feature distributions and relationships with the target variable.
Identified key patterns in customer financial behavior.

## Data Preprocessing

Handled missing values using appropriate strategies.
Encoded categorical variables using Label Encoding or One-Hot Encoding.
Scaled numerical features where necessary.
Split data into training and testing sets.

## Model Development

Trained classification models such as Logistic Regression and CatBoost.
Generated prediction probabilities instead of only class labels.

## Cost-Based Optimization

Defined business costs:
False Positive (FP): Approving a risky customer
False Negative (FN): Rejecting a good customer
Evaluated different probability thresholds.
Selected the threshold that minimizes total business cost.

## Model Evaluation

Evaluated performance using accuracy, confusion matrix, and F1-score.
Incorporated cost-based evaluation to improve business decisions.
Compared model performance under different thresholds.

## Results & Insights

The model successfully identified high-risk customers based on financial and behavioral features.
Default prediction improved when using probability thresholds instead of fixed classification.
Cost-based optimization reduced financial risk compared to standard accuracy-based models.
CatBoost captured complex feature interactions better than Logistic Regression.

## Model Insights

Probability-based predictions allow flexible decision-making.
Lower thresholds increase recall but may increase false positives.
Higher thresholds reduce risk but may reject good customers.
Cost-sensitive evaluation provides a more realistic assessment than accuracy alone.

## Business Insights
False negatives (approving risky customers) are more costly than false positives.
Optimizing thresholds can significantly reduce financial losses.
Data-driven risk scoring enables better loan approval strategies.
Financial institutions can balance risk and opportunity using cost-based models.

## Conclusion

This project demonstrates the importance of cost-sensitive modeling in financial decision-making. By integrating business cost considerations into model evaluation ,more effective and practical loan approval strategies can be developed. The results highlight the limitations of traditional metrics and the value of threshold optimization.

## Future Improvements

Apply advanced models such as XGBoost or LightGBM.
Perform hyperparameter tuning for improved performance.
Use SHAP for deeper feature importance analysis.
Incorporate real-time decision systems for deployment.

## Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

CatBoost

Matplotlib

Seaborn
Jupyter Notebookion,
