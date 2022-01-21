# Project-Capstone-Political-Campaign-Persuasion
Prepared a detail report for the political campaign for a candidate to choose in general election using python and implementing following models,
Decision Tree/Segmentation/Logistic Regression/Linear Regression/KNN/Random Forest/Ensemble Models/Uplift Models 

•	Built two uplift models predicting how likely it is that a voter will become more likely to support the Democratic candidate based on the test mailings.
•	combined the two partisanship models (log. Regression and decision tree) to create an ensemble model predicting partisanship for democrats with prediction accuracy of 90% and AUC 0.9 that predicts how likely democrat candidate be chosen by voters. Based on Voter Id model score with training and validation data, prediction probability is 0.95 and most of the voters who voted in past as democrats remains democrats.
•	Built (log. Regression and decision tree) models for predicting candidate support, rather than partisanship. wave 1 strong democrat, wave 2 strong democrat, wave 1 strong republican, wave 2 strong democrat. We got prediction accuracy of 85% and AUC 0.8.
•	Built model predicting the overall persuadability of voters in FX if voter changed their mind in some way between the first and second waves of IDs.Prediction accuracy of 85% and AUC 0.85 achieved. Based on Voter Id model score with training and validation data, prediction probability is 0.9 and most of the voters persuade same party during wave 1 to wave 2 except few voters (5 %) changed their partisanship in wave 2 from democrat to republican.

