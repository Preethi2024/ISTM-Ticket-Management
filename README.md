# ISTM-Ticket-Management
Task 1: Predicting High Priority Tickets
 aimed to predict priority 1 & 2 tickets to enable preventive measures or faster resolution. 

Data Preprocessing: Handled null values, transformed categorical variables into numerical using label encoding, and prepared the dataset for modeling.
Model Selection and Evaluation: Evaluated multiple classifiers (Logistic Regression, Decision Tree, RandomForest, etc.) using train-test split and performance metrics (F1-score, recall, accuracy).
Model Selection Outcome: Chose Gradient Boosting Classifier for its superior performance in predicting high priority tickets.

Task 2: Forecasting Incident Volume
The goal was to forecast incident volumes quarterly and annually for better resource planning. Key steps include:

Time Series Data Preparation: Sorted and grouped data based on ticket opening time.
Forecasting Models Used: Employed ARIMA and SARIMAX models for forecasting.
Model Outcome: ARIMA model was found to perform better for forecasting incident volumes.

Task 3: Auto Tagging Tickets with Priorities and Departments
The objective was to automatically assign priorities and departments to tickets to reduce reassignments and delays. Here's what was done:

Data Preprocessing: Prepared data by dropping unnecessary columns and splitting into features and target variables (Priority and CI_Cat).
Model Selection and Evaluation: Employed various classifiers (GradientBoosting, RandomForest, etc.) to predict ticket priorities and departments.
Model Selection Outcome: GradientBoostingClassifier was chosen for predicting ticket priorities, while RandomForestClassifier was selected for department classification due to their superior performance.
Model Summary and Deployment
Model Summaries: Created and stored summaries of model performance including F1-score, recall, and accuracy for both training and test sets.
Model Deployment: Saved the selected models (high_priority_model, all_priority_model, department_classification_model) using pickle for future use in automating incident management processes.
Overall, your approach demonstrates a systematic use of machine learning to address specific pain points in incident management.
