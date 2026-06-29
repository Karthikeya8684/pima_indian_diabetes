# 🩺 PIMA Indian Diabetes Prediction App

An interactive web application that predicts the probability of diabetes using a machine learning model trained on the PIMA Indian Diabetes dataset.

👉 **[Try the Live App Here](https://pimaindiandiabetes-xqqlpbwpa6wstua4czdisb.streamlit.app/)**  

![image](https://github.com/user-attachments/assets/f23188df-4494-426e-b62c-ad45e0838640)



## 🚀 Features

- Predicts diabetes probability using medical input data  
- Trained with scikit-learn classification model  
- Real-time prediction with a user-friendly interface  
- Input features are scaled using a trained StandardScaler

## 🧪 Technologies Used

- Python  
- Streamlit – web app framework  
- scikit-learn – ML model and preprocessing  
- pandas – data manipulation  
- joblib – model and scaler persistence

## 📂 Project Structure

pima_indian_diabetes/
├── app.py               # Streamlit app  
├── model.pkl            # Trained classification model  
├── scaler.pkl           # StandardScaler for preprocessing  
├── diabetes.csv         # Dataset used for training  
├── Untitled1.ipynb      # Model training notebook

## 📊 Input Features
  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age

## 💻 Run Locally

1. Clone the repository:

   git clone https://github.com/loknadh09/pima_indian_diabetes.git  
   cd pima_indian_diabetes

2. Install dependencies:

   pip install -r requirements.txt

3. Launch the app:

   streamlit run app.py

## 🧠 Example Inputs

| Feature                     | Non-Diabetic | Diabetic |
|----------------------------|--------------|----------|
| Pregnancies                | 1            | 6        |
| Glucose                    | 95           | 160      |
| Blood Pressure             | 70           | 90       |
| Skin Thickness             | 20           | 35       |
| Insulin                    | 85           | 180      |
| BMI                        | 24.5         | 36.0     |
| Diabetes Pedigree Function | 0.2          | 0.75     |
| Age                        | 25           | 50       |


