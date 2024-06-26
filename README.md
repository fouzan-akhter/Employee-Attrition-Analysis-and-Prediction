<h1>Employee Attrition Analysis and Prediction</h1>
<h3>(Salifort Motors Project)</h3>

 ### [Google Advanced Data Analytics Certificate](https://github.com/fouzan-akhter/salifortmotors_project)

<h2>Project Description</h2>
The Google Advanced Data Analytics capstone project included the completion of the Salifort Motors project. For this project, a dataset was analyzed in order to build predictive models that would offer the Human Resources (HR) division of a sizable consulting firm insights. Model assessments, data visualizations, ethical concerns, and a list of resources used for troubleshooting and problem-solving were all included in the deliverables.
<br>
<br>
To improve satisfaction with work, Salifort Motors' HR staff looked for data-driven suggestions. Finding the elements that are most likely to cause employee attrition was the main investigation. Predicting employees' propensity to leave the organization was the main goal, since it may have revealed important elements for better retention.
<br>
<br>
Importing the necessary libraries and datasets was the first step in the project. Basic data manipulation, statistical summaries, duplicate value checks, outlier evaluations, and exploratory data analysis visualizations came next. Analysis of correlations between the variables and the target variable were done. Then, tree-based models (Decision Trees and Random Forest) and logistic regression were built, assessed, and optimized by tuning hyper-parameters.
<br>
<br>
The logistic regression model performed admirably on the test set, obtaining excellent precision, recall, f1-score, and accuracy metrics, according to a summary of the findings. After feature engineering, the decision tree model, which switched to tree-based machine learning, showed noteworthy results on the test set. Compared to the decision tree model, the random forest model showed some slight improvement.
<br>
<br>
Regarding findings and suggestions, the models' insights and feature importance highlighted how common it is for employees in the organization to be overworked. Proposed tactics to improve employee retention included setting project boundaries, assessing long-tenured employees' chances for advancement, and rewarding work done outside of regular working hours. To fully improve the organization's work culture, inclusive talks and clear communication of policies were recommended at both the team and corporate levels. Additionally, it was suggested that assessment results be allocated fairly in accordance with contributions and efforts, fostering a positive work atmosphere and improving general employee satisfaction and retention.
<br>
<br>
Note: The dataset and project discussed herein were not generated by me but were integral components of the Google Advanced Data Analytics course provided on Coursera. It's important to note that numerous variations of this project may exist on the internet, and my account of it is specific to my own interpretation and implementation. I want to emphasize that I do not claim ownership of the dataset; rather, it was curated by Google for educational purposes as part of the course. It's crucial to recognize that this dataset does not mirror the actual data from the New York City Taxi and Limousine Commission; instead, it serves as a pedagogical tool designed to facilitate learning within the context of the course.

<br />
 
<h2>Programming Language</h2>

- <b>Python</b> 

<h2>Environment Used </h2>

- <b>Jupyter Notebook</b>

<h2>Data Dictionary </h2>

| Column Name          | Description                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------|
| satisfaction_level   | The employee’s self-reported satisfaction level [0-1]                                           |
| last_evaluation      | Score of employee's last performance review [0–1]                                                |
| number_project       | Number of projects employee contributes to                                                       |
| average_monthly_hours| Average number of hours employee worked per month                                                |
| time_spend_company   | How long the employee has been with the company (years)                                          |
| work_accident        | Whether or not the employee experienced an accident while at work                                 |
| left                 | Whether or not the employee left the company                                                      |
| promotion_last_5years| Whether or not the employee was promoted in the last 5 years                                      |
| department           | The employee's department                                                                         |
| salary               | The employee's salary (low, medium, or high)                                                      |
