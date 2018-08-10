### CSCI S-109a - Introduction To Data Science - Final Project
### Contributors: [Karan Bhandarkar](mailto:karanbhandarkar@gmail.com), [Vivek Mishra](mailto:iblpvivek@icloud.com)
<HR>
  
### [Welcome](README.md)&emsp;|&emsp;[Introduction and EDA](intro-and-eda.md)&emsp;|&ensp;[**_Literature Review_**](lit-review.md)&emsp;|&emsp;[Models](models.md)&emsp;|&emsp;[Results and Conclusion](results-and-concl.md)
<HR>


## Content:
1. [Literature Review](#literature-review)

1. [Related Work](#related-work)

<HR>
  
### Literature Review


[Back to top](#content)

### Related Work

#### [Twitter Bot Detection](https://github.com/RohanBhirangi/Twitter-Bot-Detection)

Observations from this project:<BR>
1.Decision Tree classifier provides the highest accuracy<BR>
1.High precision (>97%) values for all the classifiers<BR>
1.High precision denotes low false-positives (the probability of a user being identified as bot when it is a non-bot is low)<BR>
1.Thus, the models efficiently identify a non-bot account<BR>
1.But we get low recall score for the classifiers<BR>
1.Which means there are a lot of false-negatives in our prediction<BR>
1.These are twitter accounts which are bots but are identified as non-bots<BR>

#### [Detecting Twitter Bots using Machine Learning](https://github.com/jubins/MachineLearning-Detecting-Twitter-Bots)

Twitter bot is a program used to produce automated posts, follow Twitter users or serve as spam to entice clicks on the Twitter microblogging service. In this project, they use Machine Learning techniques to predict weather an account on Twitter is a Bot or a real user. They have performed significant amount of feature engineering, along with feature extraction - selected features out of 20 helped us to identify whether an account is bot or non bot. They implemented various algorithm but finally implemented their own which gave AUC>95%.

[Back to top](#content)
