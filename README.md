# Predictive Modeling Of MBTI Personality Type Based On Social Media Posts

While many existing research focuses on training machine learning models to predict MBTI using text-based input, only a few research is dedicated to improving the performance of a given machine learning model with parameter tuning. In this paper, we used an existing dataset to predict users’ personality types based on Twitter posts. Using the random forest as our prediction model, we concluded that there are a few parameters that have a significant impact on the performance:   
1) the splitting ratio of the training and testing set,     
2) the decision tree’s maximum depth,   
3) the number of estimators   
4) the Minimum sample leaf.   
  
Our analysis indicates that the best ratio of the training and test sets is 60%: 40%. In our case, the optimal minimum sample leaf is 13; The decision tree's maximum depth is 15, and the number of estimators is 1500. While this result is obviously not applicable to any other studies, as all dataset and machine learning model differs, we hope this paper provides some insights into how hyperparameters can impact the performance of a machine learning model.  
  
**KEYWORDS  **
Machine Learning, MBTI, Social Media, KNN, Random Forest, SVM
