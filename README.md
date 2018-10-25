# Bank Marketing Prediction

# Goal
Use Alteryx to build a model which predicts whether a bank's marketing campaign will be successful or not.

# Project Summary

Marketing selling campaigns constitute a typical strategy to enhance business in the banking world. Banks use direct marketing when targeting segments of customers by contacting them to meet a specific goal. The objective of this project is to predict whether a client will subscribe as a result of marketing efforts. The data is related to direct marketing campaigns of a Portuguese banking institution. The data contains information like age of the client, job status – whether the client is employed or not, marital status, level of education, whether the client has ever defaulted on his loans, account balance, whether the client currently holds a loan or not, preferred method of contact and information related to previous marketing outreaches to the client.

To predict the client’s decision, I intend to create a model using Alteryx. We are data rich, meaning that we can historical data to build a model and since the model output is expected to be ‘yes’ or ‘no’ we need to build a binary model. I intend to explore classification algorithms like logistic regression, decision trees, random forest model and boosted model to predict the outcome. After building four binary classification models, I will evaluate them based on their characteristics and choose the best fit. By the end of the project, I expect to have a binary classification model which can be used on the test data set to predict whether a client will subscribe.

# Project Methodology
The entire project will be implemented in a tool called Alteryx. The data set will be loaded in the tool and explored for missing values, low variability, and association analysis will be done with respect to the target and amongst the variables themselves. If need be data will be appropriately formatted or cleansed before going forward. The next step will be to partition data into sample data (70% of total data) and validation data (30%). The sample data will be then used to build classification models (logistic regression, decision trees, random forest and boosted). Models will be compared considering accuracy of the entire models, accuracy of ‘yes’ prediction, accuracy of ‘no’ prediction and the ROC curve.

