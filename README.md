# Multiple Disease Prediction System

## 📌 Description

Multiple Disease Prediction System is a machine learning-based web application developed using Python and Streamlit. The application allows users to enter relevant medical parameters and obtain predictions for three different diseases: Diabetes, Heart Disease, and Parkinson's Disease. Separate machine learning models are used for each disease, and the trained models are integrated into the Streamlit application to provide quick and easy predictions through an interactive user interface. The project demonstrates how machine learning can be applied to healthcare-related datasets and how trained models can be deployed as a web application.

## 🩺 Diseases Predicted

- Diabetes
- Heart Disease
- Parkinson's Disease

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Pickle

## 📂 Project Structure

```text
Multiple-Disease-Prediction-System/
│
├── dataset/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── saved model/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
├── disease.py
├── requirements.txt
├── .gitignore
└── README.md

## ⚠️ Disclaimer

This project is developed for educational purposes only. The predictions provided by this application should not be considered medical advice or a professional medical diagnosis. Please consult a qualified healthcare professional for medical advice, diagnosis, or treatment.

⚙️ Installation
Clone the repository:
git clone https://github.com/ChakshitGaur/Multiple-Disease-Prediction-System.git
cd Multiple-Disease-Prediction-System
Install the required libraries:
pip install -r requirements.txt

▶️ How to Run
Run the Streamlit application:
streamlit run disease.py
The application will open in your web browser. You can select a disease prediction module and enter the required medical information to receive a prediction.

📌 Features
- Simple and user-friendly interface
- Prediction for multiple diseases
- Separate machine learning models for each disease
- Pre-trained models included in the project
- Interactive web application using Streamlit
- Easy to run locally and deploy online

## 👨‍💻 Author
**Chakshit Gaur**