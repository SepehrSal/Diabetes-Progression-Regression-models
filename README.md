# Diabetes-Progression-Regression-models
in this project our model predict the progression of diabetes in patients.

to reach the best model I used Linear, Lasso, SVR and Random Forest Regressors using GridsearchCV. 

#Code and Resources Used

This is one of avalable datasets in sklearn library. Ten baseline variables, age, sex, body mass index, average blood pressure, and six blood serum measurements were obtained for each of n =442 diabetes patients, as well as the response of interest, a quantitative measure of disease progression one year after baseline.

Source URL:
https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html

Each of these 10 feature variables have been mean centered and scaled by the standard deviation times n_samples

## Exploratory Data Analysis
plot of result

![image](https://user-images.githubusercontent.com/121250443/214771970-559bd2ab-c437-4e47-b21b-4ea8766df0d0.png)

correlation between features

![image](https://user-images.githubusercontent.com/121250443/214772017-086a8d10-c1ba-4920-a68c-9859538149c6.png)


## Training Models


I tried three different models and evaluated them using Root Mean Absolute Error. I chose RMAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model and calculating the residual sum of squares and the explained variance score (R^2)

![image](https://user-images.githubusercontent.com/121250443/214772840-a7e66466-c307-4f78-83ae-6dad67f2e852.png)


I tried three different models:

* Multiple Linear Regression 
*Lasso Regression
* SVR
* Grid Search SVR
* Random Forest


LM.RMSE: 53.276656855023894
Lasso.RMSE: 53.16497759165116
GridSVR.RMSE: 52.91201652337118
RF.RMSE: 50.27100063162166

Best Model performance
The Random Forest 


