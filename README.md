# 💳 Churn Prediction App

A Machine Learning-based web application that predicts whether a customer is likely to churn or not. Built using **Artificial Neural Networks (ANN)** and deployed with **Streamlit**.

---

## 🚀 Live Demo

👉 (https://churn-prediction-wrhxtoxg8aptpuec92idrc.streamlit.app/)

---

## 🧠 Model Used

* Artificial Neural Network (ANN)
* Built using TensorFlow / Keras
* Binary Classification Problem

---

## ⚙️ Hyperparameter Tuning 🚀

To improve model performance, hyperparameter tuning was performed using a dedicated notebook.

### 🔧 Tuned Parameters:

* Number of hidden layers
* Number of neurons
* Activation functions
* Optimizers
* Learning rate
* Batch size
* Epochs

### 📊 Outcome:

* Improved model generalization
* Better validation performance compared to baseline ANN

📓 Notebook: `hyperparametertuningann.ipynb`

---

## 📊 Dataset

* File: `Churn_Modelling.csv`
* Contains customer details like:

  * Credit Score
  * Geography
  * Gender
  * Age
  * Balance
  * Activity status

---

## 📁 Project Structure

```id="k9p2dj"
Churn-Prediction/
│
├── app.py                          # Streamlit app
├── model.h5                        # Trained ANN model
├── label_encoder_gender.pkl        # Gender encoder
├── onehot_encoder_geo.pkl          # Geography encoder
├── scaler.pkl                      # Feature scaler
├── Churn_Modelling.csv             # Dataset
├── hyperparametertuningann.ipynb   # Hyperparameter tuning (NEW)
├── experiments.ipynb               # Model training
├── prediction.ipynb                # Testing
├── requirements.txt
├── runtime.txt
```

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas / NumPy
* Streamlit

---

## 📈 How It Works

1. User inputs customer data
2. Data is encoded & scaled
3. ANN model predicts churn probability
4. Result displayed in UI

---

## 🎯 Key Highlights

* End-to-end ML pipeline
* Hyperparameter tuning for optimization
* Deployment using Streamlit
* Real-time prediction system

---

## ⚠️ Note

* ANN used for experimentation
* Tree-based models like XGBoost can also be explored for better performance on tabular data

---

## 📬 Contact

* GitHub: https://github.com/inamulmd

---

⭐ Star the repo if you found it useful!
