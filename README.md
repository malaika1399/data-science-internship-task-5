# data-science-internship-task-5
Task 5 added loan acceptance prediction


## Task 5: Personal Loan Acceptance Prediction

### Objective
Predict which bank customers are likely to accept a personal loan offer using classification modeling.

### Approach
1. Loaded Bank Marketing Dataset (bank-additional-full.csv) — 41,188 rows, 21 columns
2. Checked missing values — dataset was clean
3. Encoded all categorical columns using Label Encoding
4. Performed EDA — analyzed age, job type, call duration, and marital status
5. Trained Decision Tree Classifier (max_depth=5, 80/20 split)
6. Evaluated using accuracy score, confusion matrix, and classification report
7. Extracted feature importance to identify key drivers

### Results and Insights
- Model Accuracy: ~85%
- Call duration is the strongest predictor of loan acceptance
- Only 11.27% customers accepted — dataset is heavily imbalanced
- Longer phone calls strongly correlate with higher acceptance rates
- Retired and student job types show higher acceptance rates

### Tools Used
Python, pandas, matplotlib, seaborn, scikit-learn, Jupyter Notebook
