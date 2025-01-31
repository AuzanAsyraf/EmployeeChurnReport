# Employee Retention Program
Project workflow
1. Build Database in Big Query
2. Connect to Database with Phyton (Colab to big Query)
3. Build a Churn Model (Pycaret)
4. EExport Data to Big Query
5. Build the report

Problem Statement:
We are having issues with keeping employees so we would like a help to proactively find employees that are at risk of leaving the company.

Approach:
-Select pilot program with new employees
-Build Auto ML model trained on previous data that can predict new employees leaving.

Deliverable:
Report/Dashboard

Analysis Questions:
1. What is Causing Employees to Leaves?
2. Who is Predicted to leave? (Highest probability to leave)
3. Are Employees Satisfied?
4. What Departments have the most churn?

Project Questions:
1. What does success look like? Highly aaccurate predictions model
2. What does failure look like? inaccurate model
3. What Trends are Important? Features that are causing Churn
4. What Actions Affect the trend? Recommendations

Machine Learning Workflow:
1. Train machine learning(ML) model on 70% of our 15000 employees
3. Test abd tune the ML model for accuracy on the remaining 30%
4. Use the optimized ML Model to predict which employees in our pilot will Churn
