## Loan Approval Prediction: Case Study

In this project, I developed a machine learning model using Python to predict the approval status of loan applications. Using a dataset from Kaggle, the process involved data exploration, cleaning, visualization, handling outliers, and building a linear model with scikit-learn. The model's performance was evaluated using metrics like accuracy and F1 score, providing insights into its effectiveness in predicting loan approvals.

## Dataset Variables

- Gender: Applicant's gender.
- Married: Marital status of the applicant.
- Dependents: Number of dependents.
- Education: Level of education.
- Self_Employed: Whether the applicant is self-employed.
- ApplicantIncome: Applicant's income.
- CoapplicantIncome: Income of the coapplicant.
- LoanAmount: Amount of loan requested.
- Loan_Amount_Term: Term of the loan in months.
- Credit_History: Credit history status.
- Property_Area: Location of the property.
- Loan_Status: Outcome of the loan application.


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


[Imgur](https://i.imgur.com/7QemEDd.png?1)
[Imgur](https://i.imgur.com/QuKifYq.png?1)


