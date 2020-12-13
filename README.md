# Wildfire-prediction
Predicting the severity of wildfire in US (Final Project of DSGA-1001)

*The full report is listed as **DS_GA_1001_Project_Report.pdf***.

**_Abstract_**:

> Wildfire has become a big issue in the United States,
causing casualties and substantial economic losses every year. In
this project, we aim to predict the fire size of wildfires using
machine learning algorithms. The dataset we used contains about
190,000 cases of wildfires in California, Alaska, New Mexico,
Nevada, and Texas from 1992 to 2009. We select important
features such as the coordinate of wildfire, elevation, land’s
owner, cause, and fire month by calculating multicollinearity,
mutual information, and learning performance curve. We then
choose Random Forest as the baseline model and compare
performances among other model candidates, including XGBoost,
KNN, Multilayer Perceptron, and stacking ensemble model with
XGBoost as the meta-model. The stacking ensemble model yields
the highest accuracy of 64.51%. Such model can be deployed
by fire departments as reference for more efficient allocation of
wildfire prevention resources once a wildfire took place.
