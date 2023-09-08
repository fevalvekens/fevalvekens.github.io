## Shinkansen Travel Experience Prediction

### Problem Summary 

The goal of the problem is to predict whether a passenger was satisfied or not considering his/her overall experience of traveling on the Shinkansen Bullet Train. The problem consists of 2 separate datasets: Travel data & Survey data. Travel data has information related to passengers and attributes related to the Shinkansen train, in which they traveled. The survey data is aggregated data of surveys indicating the post-service experience.

### Models Explored

After performing Exploratory Data Analysis on the two datasets, we imputed the missing values using the median and mode. We then prepared the data for modeling.
We explored various classification models for prediction, and tuned them to improve the accuracy score, the chosen model evaluation criterion:
- Decision Tree
- Random Forest
- Logistic Regression
- Artificial Neural Network
- Convolutional Neural Network
- Support Vector Classifier (SVC)
- Light Gradient Boosting Machine (LightGBM)

We also tried feature engineering, and it slightly improved the accuracy.  

### Leaderboard

Our best accuracy score, 95,44689%, was obtained with the LightGBM model. We made it to the top ten leadersboard!
<img src="images/leaderboard.png?raw=true"/>

### Jupyter Notebook 
https://github.com/fevalvekens/shinkansen


