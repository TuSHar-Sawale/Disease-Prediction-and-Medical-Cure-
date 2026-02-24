# Disease-Prediction-and-Medical-Cure-
A Machine Learning based web application that predicts possible diseases from user-entered symptoms and provides structured medical guidance including precautions, medications, diet plans, and workout recommendations.

Built using Flask and a trained Support Vector Classifier (SVC) model.

🚀 Problem Statement

People often ignore early symptoms or self-diagnose using unreliable sources. This project demonstrates how machine learning can assist in preliminary disease prediction using symptom-based classification.

The goal is not to replace doctors, but to build an intelligent decision-support system using structured medical datasets.

🧠 How It Works


User enters symptoms (comma separated)

Symptoms are converted into a binary feature vector

Trained SVC model predicts the most probable disease

System retrieves:

Disease description

Precautions

Medications

Recommended diet

Workout suggestions

The backend logic is implemented in Flask and model inference is done using a serialized .pkl model.

Model loading reference: 

2f5e8150-cad0-4a2a-bd65-45b2105…

🛠 Tech Stack

Python

Flask

Scikit-learn (SVC Model)

Pandas / NumPy

HTML / CSS

Pickle (Model Serialization)

📊 Machine Learning Details

Algorithm: Support Vector Classifier (SVC)

Multi-class classification

Symptom-to-disease mapping using one-hot encoding

Trained on structured medical dataset

Model persisted using Pickle for production inference

🔥 Key Features

Symptom-based disease prediction

Clean feature vector encoding

Dynamic recommendation system (diet, workout, medication, precautions)

Modular helper functions

Server-side validation

Ready for API extension

📂 Project Structure
├── app.py
├── models/
│   └── svc.pkl
├── datasets/
│   ├── symptoms_df.csv
│   ├── precautions_df.csv
│   ├── medications.csv
│   ├── diets.csv
│   ├── workout_df.csv
│   └── description.csv
├── templates/
│   ├── index.html
│   └── about.html
⚠ Disclaimer

This system is for educational and demonstration purposes only. It is not a substitute for professional medical advice.
