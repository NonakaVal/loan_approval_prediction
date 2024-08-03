## Loan Approval Prediction: Case Study

In this project, I developed a machine learning model using Python to predict the approval status of loan applications. Using a [dataset](https://statso.io/loan-approval-prediction-case-study/) from [Kaggle](https://www.kaggle.com/), the process involved data exploration, cleaning, visualization, handling outliers, and building a linear model with scikit-learn. The model's performance was evaluated using metrics like accuracy and F1 score, providing insights into its effectiveness in predicting loan approvals.

## General informations

| Column        | Value         | Normalized Count |
|---------------|---------------|------------------|
| **Gender**    | Male          | 82%              |
|               | Female        | 18%              |
| **Married**   | Yes           | 65%              |
|               | No            | 35%              |
| **Education** | Graduate      | 78%              |
|               | Not Graduate  | 22%              |
| **Self_Employed** | No       | 87%              |
|               | Yes           | 13%              |
| **Loan_Status** | Y         | 69%              |
|               | N             | 31%              |



### Loan_Status vs Gender

| Loan_Status | Female | Male  |
|-------------|--------|-------|
| Rejected    | 19.27% | 80.73%|
| Approved    | 17.77% | 82.23%|

---

### Loan_Status vs Education

| Loan_Status | Graduate | Not Graduate |
|-------------|----------|--------------|
| Rejected    | 72.92%   | 27.08%       |
| Approved    | 80.57%   | 19.43%       |

---

### charts

Applicant Income Distribution
![Imgur](https://i.imgur.com/QuKifYq.png?1)


Proportion of Loan Status by Property Area
![Imgur](https://i.imgur.com/7QemEDd.png?1)

Correlation Heatmap
![Imgur](https://i.imgur.com/hMshXSr.png?1)


### Classification Report

|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| **Class 0**  | 0.90      | 0.47   | 0.62     | 55      |
| **Class 1**  | 0.79      | 0.97   | 0.87     | 110     |
| **Accuracy** |           |        | 0.81     | 165     |
| **Macro avg**| 0.84      | 0.72   | 0.74     | 165     |
| **Weighted avg** | 0.82   | 0.81   | 0.79     | 165     |

