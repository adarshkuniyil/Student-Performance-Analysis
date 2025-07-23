🎓 Student Performance Prediction

This project is a Machine Learning-based classification system that predicts whether a student will pass or fail based on personal and academic attributes such as gender, age, weekly study time, and past class failures.


📌 Project Overview

Educational institutions can greatly benefit from early prediction of student performance to provide timely support. This project uses the student-mat.csv dataset to train a Random Forest Classifier and build a user-friendly Streamlit app for real-time predictions.


🛠️ Technologies Used

Python
pandas, seaborn, matplotlib
scikit-learn
joblib
Streamlit


🧠 Features

Label encoding of categorical variables (sex)

Standard scaling of numerical features (age, studytime, failures)

Binary classification (Pass = 1, Fail = 0 based on final grade G3)

Model performance evaluation using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix Visualization

Model serialization using joblib

Streamlit UI for interactive predictions



📈 Dataset


Dataset: student-mat.csv

Source: UCI Machine Learning Repository

Attributes used:

sex – Student's gender

age – Student's age

studytime – Weekly study time

failures – Number of past class failures

G3 – Final grade (used to derive binary target)


⚙️ How It Works


Data is preprocessed (encoded & scaled)

G3 is converted to binary target (pass if G3 ≥ 10, else fail)

Random Forest Classifier is trained

Model and transformers are saved with joblib

Streamlit app takes user input and predicts pass/fail in real-time
