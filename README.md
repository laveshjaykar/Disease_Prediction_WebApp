This repository contains a Streamlit web application designed to predict various diseases such as heart disease, diabetes, and Parkinson's disease. The predictions are based on user-provided health parameters. The application uses machine learning models for predictions.

Features

Heart Disease Prediction: Predicts the likelihood of heart disease based on factors like age, sex, blood pressure, cholesterol levels, and more.
Diabetes Prediction: Determines the possibility of diabetes considering parameters such as glucose levels, blood pressure, skin thickness, insulin levels, BMI, and more.
Parkinson's Disease Prediction: Assesses the risk of Parkinson's disease using various speech signal measurements.

How to Use

Start the Application: Run the Streamlit application. The interface will guide you through the process.
Select the Disease Prediction: Choose the disease you want to get predictions for (Heart Disease, Diabetes, Parkinson's).
Enter Required Information: Input the necessary health parameters for the chosen disease.
Get Prediction: Click the prediction button to see the results.

Models

The models used for prediction are pre-trained and saved as .sav files.
Models are loaded at the beginning of the script using Python's pickle module.

Disclaimer

The predictions made by this system are based on machine learning models and should not be considered as a substitute for professional medical advice, diagnosis, or treatment.
