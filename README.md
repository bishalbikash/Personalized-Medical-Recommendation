# Personalized-Medical-Recommendation
Project Overview

This project is a machine learning-based web application that predicts diseases based on user-input symptoms and provides personalized recommendations such as precautions, medications, diet plans, and workouts.

The system is built using Python, machine learning algorithms, and Flask for deployment as a web application.

Features
Predicts disease based on symptoms
Provides detailed disease description
Suggests precautions
Recommends medications
Suggests diet plans
Recommends workouts
User-friendly web interface using Flask and Bootstrap
Technologies Used
Python
Pandas, NumPy
Scikit-learn
Flask
HTML,  Bootstrap
Machine Learning Model
Model Used: Support Vector Classifier (SVC)
Trained on symptom-based dataset
Evaluated using accuracy score
How It Works
User enters symptoms in the web application
Symptoms are converted into a numerical format
The trained ML model predicts the disease
Based on the prediction, the system provides:
Description
Precautions
Medications
Diet
Workout recommendations
Project Structure
├── models/
│   └── svc.pkl
├── datasets/
│   ├── symptoms_df.csv
│   ├── precautions_df.csv
│   ├── diets.csv
│   ├── medications.csv
│   └── description.csv
├── templates/
│   ├── index.html
│   ├── contact.html
│   ├── blog.html
├── static/
│   ├── css/
│   └── images/
├── app.py
└── README.md



Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical advice.
