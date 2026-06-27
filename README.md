A Machine Learning-based healthcare prediction system developed using Python, Scikit-learn, and Streamlit. This application predicts the likelihood of Diabetes, Heart Disease, and Parkinson's Disease based on user-provided medical parameters.
The project consists of individual machine learning models trained on different medical datasets and integrated into a single interactive web application.

🩺 Overview
Early disease detection helps patients receive timely treatment and improve healthcare outcomes.
This project combines three predictive machine learning models into a single web application:
🩸 Diabetes Prediction
❤️ Heart Disease Prediction
🧠 Parkinson's Disease Prediction
Users simply enter the required medical values, and the application instantly predicts whether the disease is likely to be present.

✨ Features
Predicts Diabetes
Predicts Heart Disease
Predicts Parkinson's Disease
Clean and interactive Streamlit UI
Multiple disease prediction in one application
Fast prediction using pre-trained machine learning models
Easy navigation using Streamlit Sidebar
Simple deployment on Streamlit Cloud

🛠 Technologies Used
Python
Streamlit
Scikit-learn
NumPy
Pandas
Pickle
Streamlit Option Menu
Jupyter Notebook

Multiple-Disease-Prediction-System
│
├── Models/
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   └── parkinsons_model.sav
│
├── Notebooks/
│   ├── Diabetes Prediction.ipynb
│   ├── heart disease prediction.ipynb
│   └── Parksinson's predictor.ipynb
│
├── Dataset/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
└── Images/
    ├── diabetes.png
    ├── heart.png
    └── parkinsons.png

📊 Datasets
The project uses publicly available healthcare datasets for training.

Diabetes Dataset
Features include:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age

Heart Disease Dataset
Features include:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Maximum Heart Rate
Exercise-Induced Angina
ST Depression
Slope
Major Vessels
Thalassemia

Parkinson's Dataset
Voice measurement features:
MDVP Fo
MDVP Fhi
MDVP Flo
Jitter
Shimmer
NHR
HNR
RPDE
DFA
Spread1
Spread2
D2
PPE
Additional voice frequency parameters

🤖 Machine Learning Models
The following algorithms were trained and saved as .sav files using Pickle.
Disease	Model
Diabetes	Support Vector Machine (SVM)
Heart Disease	Logistic Regression
Parkinson's Disease	Support Vector Machine (SVM)

📚 Model Training

The repository also contains Jupyter notebooks used for model development.

Diabetes Prediction.ipynb
Data Loading
Data Preprocessing
Feature Selection
Model Training
Model Evaluation
Model Saving

heart disease prediction.ipynb
Data Cleaning
Data Visualization
Train-Test Split
Logistic Regression
Accuracy Evaluation
Model Serialization

Parksinson's predictor.ipynb
Voice Dataset Processing
Feature Engineering
SVM Model Training
Prediction
Saving Trained Model

##Model Preview

Diabaetes Prediction -- ![Diabaetes Prediction](https://github.com/garvits-001/Multiple-Disease-Prediction-System-using-Machine-Learning/blob/main/Diabetes.jpg)
Heart Disease Prediction -- ![Heart Disease Prediction](https://github.com/garvits-001/Multiple-Disease-Prediction-System-using-Machine-Learning/blob/main/Heart%20Disease.jpg)
Parkinsons Prediction -- ![Parkinsons Prediction](https://github.com/garvits-001/Multiple-Disease-Prediction-System-using-Machine-Learning/blob/main/Parkinsons.jpg)


