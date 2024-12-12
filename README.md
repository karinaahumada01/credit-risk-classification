# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis is to evaluate the credit risk of loans using a logistic regression model. The dataset contains financial information related to loans, and the goal is to predict whether a loan is healthy (0) or high-risk (1).

**Key Steps:**

1. **Data Preparation:**

- Features (X) include financial metrics such as loan size, interest rate, borrower income, and debt-to-income ratio.
- Labels (y) represent the loan status (0 for healthy, 1 for high-risk).
- Data was split into training and testing sets (80% training, 20% testing).

2. **Model Selection:**

- A logistic regression model was used for its efficiency and effectiveness in binary classification tasks.

3. **Evaluation Metrics:**

- Confusion matrix and classification report were used to evaluate the model's performance.

## Results

**Logistic Regression Model:**

- **Confusion Matrix:**
[[14924    77]
 [   31   476]]

**Classification Report:**

- **Healthy Loans (0):**
    - Precision: 1.00
    - Recall: 0.99
    - F1-Score: 1.00
      
- **High-Risk Loans (1):**
    - Precision: 0.86
    - Recall: 0.94
    - F1-Score: 0.90
      
- **Overall Accuracy: 99%**

## Summary

**Key Findings:**

- The logistic regression model achieved 99% accuracy, demonstrating strong overall performance.
- It predicts healthy loans (0) with near-perfect precision and recall.
- It also performs well in identifying high-risk loans (1), with strong recall (94%), though precision for high-risk loans is slightly lower (86%).

**Recommendation:**

This model is recommended for use, particularly when minimizing missed high-risk loans is critical. However, if reducing false positives for high-risk loans is important, further adjustments may be required.


## References 

ChatGPT and Xpert Learning Assistant were used for README outline and format, and troubleshooting errors for this project assignment.

- OpenAI. (December, 2024). ChatGPT (GPT-4) [Large language model]. https://chat.openai.com/ Xpert Learning Assistant was used for troubleshooting errors for this project assignment.

- Xpert Learning Assistant. (2024). Retrieved from https://bootcampspot.instructure.com/
