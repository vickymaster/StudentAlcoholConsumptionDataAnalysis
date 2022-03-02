# StudentAlcoholConsumptionDataAnalysis
Data Analysis of Student Alcohol Consumption Data collected from Kaggle. This data is collected as a result of a survey of students studying Mathematics and Portuguese languages.

For the current scope of project, analysis of students studying Mathematics is considered. The data contains several attributes such as amount of alcohol consumption of students, academic details and grades of students, their family background information, extra curricular activities details and so on.

On this data, I have initially performed data analysis task such as giving meaningful names to columns, converting categorical variables to factored variables. Then on this cleaned and structured data, I carried out data analysis task and data visualization to obtain statistical and graphical summary of data. Also I identified some trends in the data.

I have explored "caret" (Classification And REgression Training) package in R and used it to predict Final Grades of students from a few predictor variables from the data using Linear Regression. To cross validate the model, I used techniques such as bootstrap resampling and cross-validation. I also trained Random Forest algorithm and finally compared the results of random forest with those of linear regression.
