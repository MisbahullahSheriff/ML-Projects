# Diabetes - Prediction

* The aim of this project was to train a Machine Learning classifier to be able to accurately predict if an individual has diabetes or not.
* The classifier was trained on a dataset comprising of 2000 observations with 9 variables (including the target).

### Links:
* [*Dataset*](https://www.kaggle.com/johndasilva/diabetes)
* [*Web-App*](https://ml-diabetes-predictor.herokuapp.com)
* [*Web-App Repo*](https://github.com/MisbahullahSheriff/Diabetes-Predictor-Deployment)

**---------- IMPORTANT NOTE ----------**
* If the web-app throws an **error** message as shown below, it's probably due to the monthly limitation provided by Heroku being exceeded.
* Please try opening the web-app again at the start of the new month.
<img src="readme_resources/heroku-app-error.png">


### Algorithms Used:
* Initially various classification algorithms were tested.
* Depending on performance, a couple of classifiers were selected for further optimization:
  * _**Random Forest Classifier**_
  * _**Gradient Boosting Classifier**_
* Finally even an ensemble of the two classifier was evaluated.
* Model evaluation method: **cross-validation**.
* Model evaluation criteria: **accuracy**.

### Libraries Used:
* Pandas, Numpy, Sci-kit Learn, Matplotlib, Seaborn

<br />

**Give this repo a :star: if you liked my work.**

### Thank You!:smiley:









