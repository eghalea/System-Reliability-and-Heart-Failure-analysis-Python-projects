# Survival Analysis of Heart Failure patients 

Abstract

Objective: This Project is a study of the patient’s survival rate due to heart failure condition. One of the study’s premises is that it was based on other research on cardiovascular diseases of the heart, which has become quite common in the medical profession. This project will aim to investigate the most at risk features to help predict heart failure conditions.

Methods: The data used for this study was collected from Faisalabad Institute of Cardiology during the periods April to December 2015. It comprised of 13 features and 299 observations and was subjected under different distribution models through lifelines library in python programming software technology to determine reliability and failure conditions of the heart. Other concepts used were Kaplan Meier nonparametric estimator for censored data to model survival time outcomes on one or more predictors (features) and cox proportional hazards model to train the data for model accuracy.

Result: Among the different features, we observed the alpha (lambda_) of each feature, serum-creatinine with alpha value of 2.063559 and ejection-fraction with alpha value of 37.613387 which is exceptionally low compared with others. low alpha values indicate features are at risk because the alpha tells us about the characteristic life of the model and how long it will last before it fails. Also, the corresponding p-values for age (P=6.4e-07), creatinine phosphokinase (P=0.03), ejection fraction (P=3.0e-06) and serum creatinine (P=4.8e-06) were the features that were statistically significant below P<0.05

Conclusion: In conclusion, when comparing the significant features, Ejection fraction is the feature most associated with heart failure of the patients in this study, with the lowest survival rate of 0.01%. Anaemia and High blood pressure begins to worsen and reduce the survival rate of patients if they are not diagnosed and treated properly along the follow time for treatment. While Serum creatinine levels can be managed as critical diagnosis still have a 50% survival rate.

