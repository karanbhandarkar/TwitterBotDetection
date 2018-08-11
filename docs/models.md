### CSCI S-109a - Introduction To Data Science - Final Project
### Contributors: [Karan Bhandarkar](mailto:karanbhandarkar@gmail.com), [Vivek Mishra](mailto:iblpvivek@icloud.com)
<HR>
  
### [Welcome](README.md)&emsp;|&emsp;[Introduction and EDA](intro-and-eda.md)&emsp;|&ensp;[Literature Review](lit-review.md)&emsp;|&emsp;[**_Models_**](models.md)&emsp;|&emsp;[Results and Conclusion](results-and-concl.md)
<HR>

## Content:
Data Modelling
  * [Logistic Regression Model](#logistic-regression-model)
  * [Logistic Regression with Cross Validation](#logistic-regression-with-cross-validation)
  * [Logistic Regression with Polynomials of Degree 3](#logistic-regression-with-polynomials-of-degree-3)
  * [Decision Tree Classifier](#decision-tree-classifier)
  * [Random Forest Classifier](#random-forest-classifier)
  * [Boosting - AdaBoost Classifier](#boosting-adaboost-classifier)
  * [Ensemble Modelling](#ensemble-modelling)
  * [Neural Networks](#neural-networks)

<HR>
  
### Logistic Regression Model

~~~~
from sklearn.linear_model import LogisticRegression

model_collection = {}

logit_model = LogisticRegression().fit(X_train, y_train)

logistic_model_score = logit_model.score(X_test, y_test)

model_collection["simple_logistic"] = logit_model

print("Train set score: {0:4.4}%".format(logit_model.score(X_train, y_train)*100))
print("Test set score: {0:4.4}%".format(logit_model.score(X_test, y_test)*100))
~~~~
Train set score: 89.52%
Test set score: 89.62%

[Back to top](#content)

### Logistic Regression with Cross Validation

~~~~
~~~~

[Back to top](#content)

### Logistic Regression with Polynomials of Degree 3

~~~~
~~~~

[Back to top](#content)

### Decision Tree Classifier

~~~~
~~~~

[Back to top](#content)

### Random Forest Classifier

~~~~
~~~~

[Back to top](#content)

### Boosting - AdaBoost Classifier

~~~~
~~~~

[Back to top](#content)

### Ensemble Modelling

~~~~
~~~~

[Back to top](#content)

### Neural Networks

~~~~
~~~~

[Back to top](#content)
