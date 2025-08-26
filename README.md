## Project Overview
# Fraud-detection-knime
A predictive model for fraud detection analysis for a Bank, built with KNIME. This project is based on Supervised learning classification. Tried with CNNs as well during the development phase but due to small number of fraud cases in data sets the appropriate method selected was Decision trees, Logistic Regression and Random Forest.

*   **Goal:** To predict a fraud using historical data from a bank.
*   **Algorithms Used:** Logistic Regression, Random Forest, Gradient Boosting (XGBoost), Neural Neworks.
*   **Tools:** KNIME Analytics Platform.

## Workflow Architecture
Briefly describe the key steps in your KNIME workflow:
1.  **Data link:** (https://www.kaggle.com/datasets/kartik2112/fraud-detection).
2.  **Data Preprocessing:** Handling missing values, encoding categorical variables, feature engineering.
3.  **Modeling:** Use nodes such as GroupBy, Math formula, Row and column filter, Row splitter, Row sampling, concatenate, partitioning, Logistic regression learner, Logistic regression predictor, Scorer, ROC curves, Lift charts, for KPIs tracking, OpenAI LLMs and APIs connectors, and many others.
4.  **Evaluation:** It's done using differnet nodes and results.
5.  **Deployment/Output:** How are the results presented? (Predictions written to a file, interactive view, etc.)

## How to Open This Workflow
1.  Download the `.knwf` file from the `workflows/` directory.
2.  In KNIME Explorer, go to **File → Import KNIME Workflow...**
3.  Select "Archive File" and browse to the downloaded `.knwf` file.
4.  Click **Finish** to import. The workflow will appear in your local workspace.

Workflows and results:
<img width="3000" height="888" alt="image" src="https://github.com/user-attachments/assets/93c1ae16-bbb8-4141-b2c3-645e59a49da4" />
<img width="2589" height="1154" alt="image" src="https://github.com/user-attachments/assets/e2de4d4e-f2e5-422f-8a1b-9297f368b9e0" />
<img width="2402" height="1006" alt="image" src="https://github.com/user-attachments/assets/476a0682-9358-447a-b3a6-519eea5259c6" />
<img width="2987" height="1696" alt="image" src="https://github.com/user-attachments/assets/a5432a8f-209a-478e-b325-835a41da45b6" />
<img width="2987" height="1696" alt="image" src="https://github.com/user-attachments/assets/cb7d67f7-4fbd-4986-9f47-689f9c692d55" />
<img width="2882" height="1787" alt="image" src="https://github.com/user-attachments/assets/e2ea5240-91c7-4e16-bc08-232af3ce9e89" />
<img width="1488" height="988" alt="image" src="https://github.com/user-attachments/assets/4c141ae3-d9c7-49bd-a7be-160b1e28f26d" />


*   KNIME Analytics Platform (Version 4.7+)
*   KNIME Extension: KNIME Python Integration
*   KNIME Extension: KNIME Ensemble Learning (Weka)
