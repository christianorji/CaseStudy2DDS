# CaseStudy2DDS
# Employee Attrition Prediction
This project uses a dataset containing information about employees to predict employee attrition. The dataset includes variables such as age, department, job role, job satisfaction, and monthly income. The analysis involves splitting the dataset into training and testing sets, building logistic regression and naive Bayes models, and using up-sampling to adjust the sensitivity of the models. Additionally, linear regression is used to predict monthly income, and LASSO regression is used to identify important predictors of attrition.

Files
Employee_Attrition_Prediction.Rmd: R Markdown file containing the code and analysis for the project.
Employee_Attrition_Prediction.html: HTML file containing a knitted version of the R Markdown file.
CaseStudy2-data.txt: txt file containing the dataset used in the analysis.
No_Attrition.txt: txt file containing a subset of the original dataset with no attrition.
No_MonthlyIncome.csv: CSV file containing a subset of the original dataset with no monthly income.
Analysis
The analysis involves the following steps:

Exploratory Data Analysis (EDA): This step involves analyzing the dataset and checking for missing values, data types, and distribution of variables.

Model Building: The dataset is split into training and testing sets. Logistic regression and naive Bayes models are created using the training set. The sensitivity of the models is adjusted using up-sampling. Linear regression is used to predict monthly income, and LASSO regression is used to identify important predictors of attrition.

Model Evaluation: The performance of the logistic regression and naive Bayes models is evaluated using appropriate metrics such as accuracy, sensitivity, specificity, and area under the ROC curve. The performance of the linear regression model is evaluated using the Mean Squared Prediction Error (MSPE) and Root Mean Squared Error (RMSE). The performance of the LASSO regression model is evaluated by identifying the important predictors of attrition.

Conclusion
The logistic regression and naive Bayes models perform moderately well in predicting employee attrition based on the given dataset. The up-sampling technique improves the sensitivity of the models. Linear regression is used to predict monthly income, and LASSO regression is used to identify important predictors of attrition. These results can be used to inform decision-making processes related to employee retention strategies.
