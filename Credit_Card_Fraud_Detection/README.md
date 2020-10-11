# Machine Learning Project: Credit Card Fraud Detection

<pre>
Domain             : Computer Vision, Machine Learning
Techniques         : Random Forest Classifier, Logistic Regression, GridSearchCV
Application        : Fraud Detection
</pre>

### Description
<pre>
A Machine Learning Model which is able to detect Fraudulent Credit Card transactions. 
Before training our model, the biggest problem encountered is of class imbalance in our dataset.
I have used different techniques such as SMOTE to oversample our dataset to overcome this problem.
Later, I have used different algorithm to train model.
In a problem like Credit Card Fraud, it is equally important to distinguish between fraud and non-fraud transactions, 
therefore good score for precision and recall is necessary, keeping that in consideration we moved forward.
We get an accuracy of above 99%, recall of 84%, precision of 82% and f1-score of 83% which seems pretty 
well due to the balance between precision and recall score. 
</pre>

### Dataset
<pre>
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, 
due to confidentiality issues, they did not provided the original features and more background information about the data. 

Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been 
transformed with PCA are 'Time' and 'Amount'.

There are 284807 number of transactions(rows) and 31 features in this dataset.

Time: It contains the seconds elapsed between each transaction and the first transaction in the dataset. 

Amount: It is the transaction Amount.

Class: It is the response variable and it takes value 1 in case of fraud and 0 otherwise.
</pre>

### Dataset Links
<pre>
Name         : Credit Card Fraud Detection
Link         : <a href=https://www.kaggle.com/mlg-ulb/creditcardfraud>Credit Card Fraud Detection (Kaggle)</a>
</pre>

### Tools / Libraries
<pre>
Languages               : Python, Flask, HTML, CSS
Tools/IDE               : Anaconda
Libraries               : sklearn, matplotlib, seaborn
</pre>

<b>Model Evaluation (Testing Set)</b>
| Algorithm | Accuracy (%) | Recall (%) | Precision (%) | F1 Score (%) | ROC-AUC Score (%) |
| --- | --- | --- | --- | --- | --- |
| Logistic Regression | 100 | 63 | 84 | 72 | 81 |  
| Logistic Regression with SMOTE| 97 | 91 | 5 | 10 | 94 |
| Logistic Regression with Borderline SMOTE| 99 | 84 | 16 | 27 | 92 |
| RandomForest Classifier | 100 | 78 | 93 | 85 | 89 |
| RandomForest with balanced_subsample | 100 | 78 | 95 | 86 | 89 |
| RandomForest with class_weights | 100 | 84 | 82 | 83 | 92 |
| RandomForest with GridSearchCV | 100 | 84 | 82 | 83 | 92 |

### Links to Project
<pre>
GitHub       : <a href=https://github.com/KareliaConsolidated/Projects/tree/master/Credit_Card_Fraud_Detection>Pneumonia Detection</a>
Live Project : <a href=https://credit-card-fraud-det-kc.herokuapp.com/>Pneumonia Detection</a> 
Kaggle       : <a href=https://www.kaggle.com/kareliaconsolidated/credit-card-fraud-detection>Pneumonia Detection</a>
</pre>