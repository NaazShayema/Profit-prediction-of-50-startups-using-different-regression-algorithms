# Profit-prediction-of-50-startups-using-different-regression-algorithms 


Abstract: A company should always set a goal that should be achievable, otherwise, employees will not be able to work to their best potential if they find that the goal set by the company is unachievable. The task of profit prediction for a particular period is the same as setting goals. If we know how much profit we can make with the amount of R&D and marketing we do, then a business can make more than the predicted profit provided the predicted value is achievable. So, in this project, the task of profit prediction with machine learning using Python will be done. The profit earned by a company for a particular period depends on several factors like how much time and money a company spends on R&D, marketing and many more. So, for predicting the profit of a company for a particular period we need to train a machine learning model with a dataset that contains historical data about the profit generated by the company.


Objective: Developed a machine learning model to accurately predict the future profit of start-up businesses based on historical data, including research and development spend, administration costs, marketing spend, and state of operation, to aid in setting realistic goals and optimizing development strategies for improved decision-making by both administration and stakeholders.


Dataset: exposys_50_Startups.csv 


File: Exposys Data Labs.ipynb contains the code for data importing, data preprocessing, data splitting, model training and model evaluation.


Methodology: The methodology for predicting start-up profits involved several steps. Initially, we imported the necessary libraries (pandas, matplotlib, seaborn, numpy) and loaded the dataset for initial exploration, including examining the first few rows, checking data types, and summarizing statistics. We addressed missing values and visualized data relationships using a pair plot. Next, we selected 'R&D Spend', 'Administration', and 'Marketing Spend' as features and scaled them using `StandardScaler`, with 'Profit' as the target variable. The dataset was then split into training and test sets using `train_test_split`. We constructed and trained three regression models: Linear Regression, Decision Tree Regression, and Random Forest Regression. To evaluate these models, we defined a function to calculate and print regression metrics such as Mean Squared Error and R-squared for both the training and test sets. Additional metrics, including Mean Absolute Error, Mean Absolute Percentage Error, and model scores, were also calculated to assess model performance comprehensively. This methodology provided a structured approach to predicting start-up profits by preparing data, constructing models, and evaluating their performance.


Experimental results and analysis:

-Linear Regression performed well, with high R-squared values indicating a good fit on both training and test sets. The test set R-squared of 0.96 suggests strong predictive capability

-Decision Tree Regression showed overfitting, with perfect performance on the training set (R-squared: 1.0) but lower performance on the test set (R-squared: 0.87)

-Random Forest Regression achieved high R-squared values for both training (0.99) and test sets (0.96), indicating excellent predictive performance with minimal overfitting

-Overall, Random Forest Regression provided the best balance of fit and generalization, followed closely by Linear Regression. Decision Tree Regression overfitted the training data, resulting in lower predictive accuracy on the test set




