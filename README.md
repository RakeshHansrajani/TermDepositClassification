# Term Deposit Subscription Prediction
### Abstract
Marketing campaigns rely on understanding customer needs and satisfaction to be successful. However, several variables influence the effectiveness of a marketing campaign. This project aims to predict whether a customer will subscribe to a term deposit when contacted by a marketing agent using predictive analytics techniques.

### Problem Statement
The goal of this project is to analyze the provided dataset, which consists of data from the marketing campaigns of a Portuguese banking institution. The campaigns involved phone calls, and the objective was to determine whether a client would subscribe to a bank term deposit ("yes") or not ("no"). By examining the different features in the dataset, we will build a predictive model to determine the likelihood of a customer subscribing to a term deposit.

### Dataset Information

1. age: Age of the client
2. job: Type of job (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown')
3. marital: Marital status (categorical: 'divorced', 'married', 'single', 'unknown'; note: 'divorced' means divorced or widowed)
4. education: Education level (categorical: 'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', 'professional.course', 'university.degree', 'unknown')
5. default: Has credit in default? (categorical: 'no', 'yes', 'unknown')
6. housing: Has a housing loan? (categorical: 'no', 'yes', 'unknown')
7. loan: Has a personal loan? (categorical: 'no', 'yes', 'unknown')
8. contact: Contact communication type (categorical: 'cellular', 'telephone')
9. month: Last contact month of the year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10. day_of_week: Last contact day of the week (categorical: 'mon', 'tue', 'wed', 'thu', 'fri')
11. duration: Last contact duration in seconds
12. campaign: Number of contacts performed during this campaign and for this client (numeric, includes the last contact)
13. pdays: Number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means the client was not previously contacted)
14. previous: Number of contacts performed before this campaign and for this client
15. poutcome: Outcome of the previous marketing campaign (categorical: 'failure', 'nonexistent', 'success')
16. emp.var.rate: Employment variation rate - quarterly indicator (numeric)
17. cons.price.idx: Consumer price index - monthly indicator
18. cons.conf.idx: Consumer confidence index - monthly indicator
19. euribor3m: Euribor 3-month rate - daily indicator
20. nr.employed: Number of employees - quarterly indicator
21. y: Whether the client subscribed to a term deposit (binary: 'yes', 'no')

### Scope
This project will involve the following steps:<br>
**Data Pre-processing**: We will understand the basic structure and perform necessary data cleaning, handling missing values, handling duplicate values.<br>
**Exploratory Data Analysis (EDA)**: We will conduct an initial exploration of the dataset to perform Univariate, Bivariate, Multivariate Analysis and find patterns in the data. Also, we will treat outliers. <br>
**Training Models**: We have created user-defined functions which will ease our process of training dataset. We will train multiple Machine learning algorithms like Logistic Regression, Decision Tree, Random Forest, Bagging, AdaBoost, XGBoost, Naive Bayes, KNN, SVM with different tunning parameters to predict term deposit subscriptions for bank customers based on the provided features.<br>
**Model Evaluation**: We will tabulate and evaluate the performance of all trained models using appropriate evaluation metrics and assess their predictive capabilities.<br>
**Learning Outcome**: Through this project, you will gain a better understanding of exploratory data analysis, data preprocessing, and knowledge of various machine learning algorithms. You will also develop skills in model evaluation, and drawing insights from the results.<br>

### Conclusion
By completing this project, you will gain practical experience in applying various machine-learning techniques to predict whether a customer will subscribe to a term deposit. You will also improve your data analysis and modeling skills, enabling you to tackle similar predictive tasks in the future.
