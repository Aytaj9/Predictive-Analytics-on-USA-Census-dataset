# Predictive-Analytics-on-USA-Census-dataset

**Objective:**
The objective of this analysis is to predict income inequality among US citizens using various classification models. The study employs logistic regression, random forest, decision tree, gradient boosting, and k-nearest classification models to classify individuals into income categories based on provided demographic and socioeconomic variables.

**Summary:**
This analysis focuses on predicting income levels using a dataset obtained from the census. The study begins with data cleaning, where missing values and abnormal entries such as '?' marks are addressed. After data preparation, exploratory data analysis is conducted to understand the distributions of variables. Following this, different classification models are implemented, starting with logistic regression. The analysis compares the performance of logistic regression, random forest, decision tree, and gradient boosting models in terms of accuracy and feature importance.

Logistic regression revealed that variables such as age, education level, marital status, occupation, and gender significantly influence income levels. However, its accuracy was found to be moderate at 71%. Random forest classification yielded higher accuracy (87%) and identified similar important variables affecting income. Decision tree analysis provided acceptable accuracy (79%) and highlighted the importance of family status in predicting income levels. Gradient boosting achieved an accuracy rate of 85%, with variables like age, education, occupation, and family status being significant predictors.

Finally, the analysis implemented a k-nearest classification model, achieving an accuracy level of 83%. The study concludes that decision tree and gradient boosting models consistently identify family status as a key predictor of income levels. Overall, the project successfully predicts income inequality using various classification techniques in Python.
