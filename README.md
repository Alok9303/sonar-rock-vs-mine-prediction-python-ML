# Sonar Rock vs Mine Prediction

Predict whether an underwater object detected by SONAR signals is a **rock** or a **mine** using Machine Learning.

## 🧠 About

This project uses the classic **Sonar dataset** to build a **binary classification model** that determines whether an object is a rock or a mine based on sonar return signal measurements. The model is trained using **Logistic Regression**, a simple yet effective algorithm for binary classification problems. :contentReference[oaicite:0]{index=0}

## 📁 Project Structure

- `Sonar-Rock-vs-mine-prediction.ipynb` – Main Jupyter notebook with the full implementation  
- `sonar_data.csv` – Dataset containing 60 numerical sonar features and class labels  
- `sonar_rock_vs_mine_predictor.pickle` – Trained model file saved for reuse

## 🛠️ Technologies Used

- **Python**  
- **Jupyter Notebook**  
- **pandas, NumPy** – Data processing  
- **scikit-learn** – Machine learning model (Logistic Regression)  
- **pickle** – Saving the model
- - **pmml** – Saving the model

## 🚀 How It Works

1. Load and explore the SONAR dataset  
2. Preprocess and split data into training and testing sets  
3. Train a Logistic Regression classifier  
4. Evaluate model performance on unseen data  
5. Save the trained model for future prediction

## 📊 Dataset Overview

The Sonar dataset is a widely used dataset for binary classification. It includes sonar signal returns from rock and metal cylinder (mine) objects. Each sample has **60 numeric features** representing frequency responses. :contentReference[oaicite:1]{index=1}

## 📌 Usage

1. Clone this repository  
2. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn jupyter
