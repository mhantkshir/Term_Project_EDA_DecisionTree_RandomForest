## Term_Project_EDA_DecisionTree_RandomForest
### This is my academics project post completion of modules on Data Visualization, EDA & Term 1 of Machine Learning 

- In this project I have used the basic Panda coding for EDA. 
- Have used Visualization Liabararies like Matplotlib & Seaborn.
- Have done the Univariate, Bivariate & Multivariate Analysis.
- Have used Pie Chart, Bar Graaphs, Stacked bar chart, Area & Line chart, Heaxbin, Box Plot, Pair plot & Heat map for the plotting and visualization.

- Scores achieved using Logistic Regresssion 

>train accuracy score is: 0.8892494356659142
test accuracy score is: 0.889108259295821
precision score is: 0.9106083086053413
recall score is: 0.9623676989415916
f1 score is: 0.9357728225652754
auc train score is: 0.734257619962599
auc test score is: 0.734257619962599

- **Performed feature engineering to enhance model accuracy**

>train accuracy score is: 0.8857223476297968
test accuracy score is: 0.889108259295821
precision score is: 0.9149175412293853
recall score is: 0.9568796550372403
f1 score is: 0.9354282429584211
auc train score is: 0.7430965371298413
auc test score is: 0.7458578603055054

- Scores achieved using Decision Tree
>train accuracy score is: 1.0
test accuracy score is: 0.9397828232971372
precision score is: 0.9149175412293853
recall score is: 0.9568796550372403
f1 score is: 0.9354282429584211
auc train score is: 0.7430965371298413
auc test score is: 0.7458578603055054


- Model was overfitting hence done the Hyper Tunning with RandmoizedSearchCV & GridSearchCV

- Used various hyerparameteres to improve the score in different models and managed to achieve better accuracy as compared to earlier models which were overfitting.

- **Best score achieved by using Decision Tree Classifier**
>{'min_samples_split': 3,
 'min_samples_leaf': 5,
 'max_depth': None,
 'criterion': 'gini'}
 Train Accuracy score- 0.9764390519187359
 Test Accuracy score- 0.9355051003619612
