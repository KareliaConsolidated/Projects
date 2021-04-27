# Data Science Project: 💲💰💸Used Car Price Prediction🚗🚕🚙🚘

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.7-brightgreen.svg) 

🔎Live Project : <a href=https://used-car-price-pred-kc.herokuapp.com/>Used Car Price Prediction</a> 


<pre>
Domain             : Machine Learning, Data Science
Techniques         : Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, Xtreme Gradient Boosting Regressor, GridSearchCV
Application        : Used Car Price Prediction
</pre>

### Description
<pre>
A Machine Learning Model which is able to predict the price of used car. 

Before training our model, our main focus was cleaning and preprocessing of input data points.

As this is a Regression Problem, I have used different regressor algorithms to train model.
For Model Evaluation, I have used evaluation metrics such as Mean Absolute Error, Mean Squared Error, Mean Absolute Percentage Error and R2-Score.

We get a score of above 99% on train set and 92% on validation set. 
</pre>

### Dataset
<pre>

Dataset contains numerical as well as categorical data with two subset:
<b>train-data:</b> There are 6019 rows and 13 cols in the training set.
<b>test-data:</b> There are 1234 rows and 12 cols in the testing set.

<b>Name:</b> The brand and model of the car. 

<b>Location:</b> The location in which the car is being sold or is available for purchase.

<b>Year:</b> The year or edition of the model.

<b>Kilometers_Driven:</b> The total kilometers driven by the previous owner(s).

<b>Fuel_Type:</b> The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG).

<b>Transmission:</b> The type of transmission used by the car (Automatic, Manual).

<b>Owner_Type:</b> (First Owner, Second Owner).

<b>Mileage:</b> Standard mileage offered by the car company in km/lts or km/kg.

<b>Engine:</b> The displacement volume of engine in CC.

<b>Power:</b> The maximum power of the engine in bhp.

<b>Seats:</b> The number of seats in a car.

<b>New_Price:</b> The price of a new car of the same model in INR(lakhs).

<b>Price:</b> The price of the used car in INR(lakhs)
</pre>

### Dataset Links
<pre>
Name         : Used Car Price Prediction
Link         : <a href=https://www.kaggle.com/avikasliwal/used-cars-price-prediction?select=train-data.csv>Used Car Price Prediction (Kaggle)</a>
</pre>

### Tools / Libraries
<pre>
Languages               : Python, Flask, HTML, CSS
Tools/IDE               : Anaconda
Libraries               : sklearn, matplotlib, seaborn, numpy, pandas, joblib
</pre>

<b>Model Evaluation (Validation/Testing Set)</b>
| Algorithm | R2-Score | MSE | MAE | MAPE |
| --- | --- | --- | --- | --- | 
| Linear Regression | 0.754 | 29.357 | 2.945 | 0.658 |   
| Decision Tree Regressor| 0.835 | 19.637 | 2.036 | 0.217 |
| Random Forest Regressor| 0.895 | 12.528 | 1.618 | 0.179 | 
| Gradient Boosting Regressor | 0.901 | 11.871 | 1.749 | 0.215 | 
| Xtreme Gradient Boosting Regressor | 0.92 | 9.567 | 1.347 | 0.149 |

### Links to Project
<pre>
GitHub       : <a href=https://github.com/KareliaConsolidated/Projects/tree/master/Used_Car_Price_Prediction>Used Car Price Prediction</a>
Live Project : <a href=https://used-car-price-pred-kc.herokuapp.com/>Used Car Price Prediction</a> 
Kaggle       : <a href=https://www.kaggle.com/kareliaconsolidated/>Used Car Price Prediction</a>

If you like the project, then please give a ⭐.
</pre>