# Cardiovascular-Risk-Prediction
Cardiovascular risk prediction of patients
INTRODUCTION
Cardiovascular disease (CVD) is a general term for conditions affecting the heart or blood vessels. It is usually associated with a build-up of fatty deposits inside the arteries (atherosclerosis) and an increased risk of blood clots. So here we are going to build some models to predict the risk of ten years of coronary heart disease.

PROBLEM STATEMENT:
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,Massachusetts. The classification goal is to predict whether the patient has a 10year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

FEATURES:

Sex: male or female ("M" or "F")
Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
Cigs Per Day: the number of cigarettes that the person smoked on average in one day.
BP Meds: whether or not the patient was on blood pressure medication (Nominal)
Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
Diabetes: whether or not the patient had diabetes (Nominal)
Tot Chol: total cholesterol level (Continuous)
Sys BP: systolic blood pressure (Continuous)
Dia BP: diastolic blood pressure (Continuous)
BMI: Body Mass Index (Continuous)
Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
Glucose: glucose level (Continuous)
TenYearCHD: 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)

STEPS:

We did EDA, Feature engineering, Balanced our data set using SMOTE, and then ran various classification models to get good Accuracy.

ACCURACY SCORES:

Logistic Regression – 64.87%
KNN – 85.79%
Decision Tree classifier – 79.98%
Randomforest Classifier – 88.14%
XGB Classifier – 94.74%
Naïve Bayes Classifier – 62.86%
Support Vector Machines – 87.58%

CONCLUSION:

In this Cardiovascular Risk Prediction Project We tried to fit various models to our dataset to predict the risk of Coronary Heart Disease for next ten years.
This was a class imbalanced dataset so we used SMOTE(Synthetic minority oversampling technique) which is a class imbalance handling technique before running our algorithms.
Age, Total Cholesterol level, Heartrate were the important features in the case of XGBoost Classifier Model.
