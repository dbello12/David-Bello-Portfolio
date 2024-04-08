## [Candidate Selection Process - Machine Learning Project](https://github.com/dbello12/Assessment_Process-ML_Project)

This project develops a ML classification model trained on the results of the in-person interview as target labels to predict whether a candidate is likely to be given the “ready” score based on the results of the pre-interview survey. The ML model will be deployed in a web application using Flask. 

The model evaluates the effectiveness of the current pre-interview survey in determinig the likelihood of a candidate being selected for endorsement and funding. It applies statistical analysis and ML methods, particularly of classification.
 
The datasets will be evaluated using Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, and KNN as classification models. Nested vs. Non-Nested cross validation will be used to determine the best approach and Random Forest Feature Importance to select the most important features.


## GenSend Survey Analysis
GenSend is a Summer missions experience for college students in which they are connected with a church plant in a major city in the United States and Canada with the purpose of supporting the mission of the church plant and the work of the church planter.

A survey was sent to 1536 students who were part of the GenSend experience between 2013 and 2023. The survey attempted to measure how influential GenSend has been in helping develop a church planting culture among these students. 64 responses were received (4.2%).

This project looks at the survey results to determine if there is statistical significance in the responses (data features) and to evaluate any correlation between them.

K-Means clustering is used since this is un unsupervised task (no target labels). The indices that the clustering algorithm throws serve as target variables to use Random Forest Regressor to find the most significant features in the dataset.
