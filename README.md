# Flight cost prediction

# Overview
Hello all, this regression project is build using Random Forest Regressor. </br>
Model is train using HyperParameter Tuning</br>
The reason behind selecting Random Forest is it works well with all kind of data(automatically handle missing values,imbalanced data etc). and with Hyperparameter Tuning it gives better performance</br>
No feature scaling required: No feature scaling (standardization and normalization) required in case of Random Forest as it uses rule based approach instead of distance calculation</br>
Random Forest is usually robust to outliers and can handle them automatically.It is very stable. Even if a new data point is introduced in the dataset, the overall algorithm is not affected much since the new data may impact one tree, but it is very hard for it to impact all the trees.</br>
Random Forest is comparatively less impacted by noise.


<h3>Part-1</h3>
<h4>EDA & OneHot Endcoding</h4></br>
First we perform EDA on given data. Handling all missing values, Performing OneHot encoding and extracting only required features.</br>
Here all date and time columns are converted into numerical values
<img src="OneHot.PNG" alt="">

<h3>Part-2</h3>
<h4>Date Time Conversion</h4> 
<img src="DateTime.PNG" alt="">

<h3>Part-3</h3>
<h4>Model Building</h4>
<img src="Model.PNG" alt="">

<h3>Part-4</h3>
<h4>Hyperparameter Tuning</h4>
<img src="Hyperparameter.PNG" alt="">
<img src="BestParameter.PNG" alt="">

<h3>Part-5</h3>
<h4>Deployment & Hosting</h4></br>
The model is deployed using Flask web framework and hosted in Heroku server.
<img src="Flask.PNG" alt="">

# Screens
<img src="Screen1.png" alt="">
<img src="Screen2.png" alt="">

<h3>Demo-https://flightcostprediction.herokuapp.com/</h3>
