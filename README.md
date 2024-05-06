# Cardiovascular_Disease_Prediction

## Problem Definition:

1. Heart diseases have unfortunately become very common. It may be due to various reasons such as lifestyle, work pressure, lack of exercise, etc.
2. We are given a set of variables that impact heart diseases. These variables are related to demographic, past, and current medical history. Each attribute is a potential risk factor
3. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). 

## Data Dictionary:

The dataset is taken from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.

### Demographic:

• Sex: male or female ("M" or "F")

• Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

### Education :

1 - Higher Secorndary, 2- Graduate, 3 - Post Graduate 4- Doctarte or PHD

### Behavioural:

• is_smoking: whether or not the patient is a current smoker ("YES" or "NO") 

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day .(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

### Medical (history):

• BP Meds: whether or not the patient was on blood pressure medication (Nominal)

• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

• Diabetes: whether or not the patient had diabetes (Nominal)

### Medical(current):

• Tot Chol: total cholesterol level (Continuous)

• Sys BP: systolic blood pressure (Continuous) • Dia BP: diastolic blood pressure (Continuous)

• BMI: Body Mass Index (Continuous)

• Heart Rate: heart rate(Continuous - In medical research, variables such as heart rate thought discrete, are considered continuous because of a large number of possible values.)

• Glucose: glucose level (Continuous)

### Predict variable (desired target):

• 10-year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”) – DV
