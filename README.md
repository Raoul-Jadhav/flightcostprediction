# Flight cost prediction

# Overview
Hello all, this regression project is build using Random Forest Regressor. </br>
Model is train using HyperParameter Tuning</br>
The reason behind selecting Random Forest is it works well with all kind of data(imbalanced data etc). and with Hyperparameter Tuning it gives better performance

<h3>Part-1</h3>
# EDA & OneHot Endcoding
First we perform EDA on given data. Handling all missing values, Performing OneHot encoding and extracting only required features.</br>
Here all date and time columns are converted into numerical values
<img src="OneHot.PNG" alt="">

<h3>Part-2</h3>
Feature scaling 
<img src="DateTime.PNG" alt="">

<h3>Part-3</h3>
Model Building
<img src="Model.PNG" alt="">

<h3>Part-4</h3>
Hyperparameter Tuning
<img src="Hyperparameter.PNG" alt="">
<img src="BestParameter.PNG" alt="">

<h3>Part-5</h3>
Deployment & Hosting</br>
The model is deployed using Flask web framework and hosted in Heroku server.
<img src="Flask.PNG" alt="">

# Screens
<img src="Screen1.png" alt="">
<img src="Screen2.png" alt="">

<h3>Demo-https://flightcostprediction.herokuapp.com/</h3>
