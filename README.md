# KickstarterNLP
Predict the success of Kickstarter Campaigns based on campaign descriptions

### Project Description

Data: https://www.kaggle.com/oscarvilla/kickstarter-nlp

Text classification has mostly been used for sentiment analysis, such as on predicting whether a movie review is positive or not.
Although this is a useful application, many of us are manually capable of perform such sentiment analysis, although at a much
slower pace. 

In this project, Text Classification is used to predict whether a Kickstarter campaign will succeed, given it's campaign
description. Here, humans can't intuitively make the right predictions compared to usual sentiment analysis on movie reviews,
since it is not human emotion that we are trying to detect in these descriptions. 

By using Machine Learning, we can hope that model would be able to make better predictions than us. 

In this project, an accuracy of 70% was achieved based on a Logistic Regression model. I adjusted the output from the model 
such that it would predict that a campaign would succeed only if there was a more than 90% predicted probability that it would
do so. This gave a Precision of 92%. 

### Acknowledgements 

Machine Learning A-Z course (Udemy)


