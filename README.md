# ⚙️ Predictive Maintenance Using Machine Learning

## 📌 Project Overview

This project is a Machine Learning application designed to predict machine failures using industrial sensor data. The system analyzes machine operating parameters, performs data preprocessing and feature engineering, and trains multiple machine learning models to identify potential equipment failures before they occur.

The project compares different classification algorithms and evaluates their performance using standard machine learning metrics. The final model helps industries perform predictive maintenance, reduce unexpected downtime, and improve operational efficiency.

---

## ✨ Features

- Predicts machine failures using sensor data
- Data preprocessing and cleaning
- Feature engineering
- Feature importance analysis
- Multiple Machine Learning models
- Hyperparameter tuning using GridSearchCV
- Model performance evaluation
- High prediction accuracy
- Data visualization using Matplotlib

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebook

---

## 🤖 Machine Learning Models

The project implements and compares multiple Machine Learning algorithms, including:

- Random Forest Classifier
- XGBoost Classifier
- Multi-Layer Perceptron (MLPClassifier)

The best-performing model was selected based on evaluation metrics after hyperparameter tuning.

---

## ⚙️ How It Works

The application follows these steps:

1. Load the industrial sensor dataset.
2. Perform data preprocessing and cleaning.
3. Handle missing values and encode categorical features.
4. Split the dataset into training and testing sets.
5. Train multiple Machine Learning models.
6. Optimize model parameters using GridSearchCV.
7. Evaluate the trained models using classification metrics.
8. Predict machine failures on unseen data.

---

## 📂 Project Structure

```
Predictive-Maintenance/
│
├── Predictive_Maintenance.ipynb
├── requirements.txt
├── README.md
├── dataset.csv
├── images/
│   ├── dataset.png
│   ├── feature_importance.png
│   ├── mlp_classifier.png
│   ├── confusion_matrix.png
│   └── gridsearchcv.png
```

---

## 📷 Screenshots

### 📊 Dataset Preview

<img width="1351" height="225" alt="image" src="https://github.com/user-attachments/assets/5cc1b684-fe72-4d19-9160-3d7d2f266730" />

---
### 📈 Feature Importance (XGBoost)

<img width="891" height="504" alt="image" src="https://github.com/user-attachments/assets/030de898-5456-4029-ab4a-2912b2e90c3f" />

---

### 🧠 Multi-Layer Perceptron (MLP Classifier)

<img width="590" height="84" alt="image" src="https://github.com/user-attachments/assets/2fb7a921-bcac-4b2f-9431-4d79740d9044" />

---

### 📉 Confusion Matrix

<img width="723" height="475" alt="image" src="https://github.com/user-attachments/assets/4e3d33bb-6fec-417a-9ee6-ff473712b18e" />

---

### ⚙️ Hyperparameter Tuning (GridSearchCV)

<img width="403" height="173" alt="image" src="https://github.com/user-attachments/assets/1cbdcb7c-193f-447e-a567-add6c32d8698" />

---

## 📊 Results

- Successfully analyzed industrial machine sensor data.
- Built and compared multiple Machine Learning classification models.
- Identified the most influential features using XGBoost Feature Importance.
- Optimized model performance using GridSearchCV.
- Achieved **98.35% prediction accuracy** on the test dataset.

### Model Performance

| Metric | Value |
|---------|------:|
| Accuracy | **98.35%** |
| Precision (Failure) | **75%** |
| Recall (Failure) | **76%** |
| F1-Score (Failure) | **76%** |

### Confusion Matrix

| Actual Class | Predicted: No Failure | Predicted: Failure |
|---------------|----------------------:|-------------------:|
| No Failure | 1915 | 17 |
| Failure | 16 | 52 |

The model accurately identifies machine failures while maintaining a low false positive rate, making it suitable for predictive maintenance applications.

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/truptip2005/TRUPTI-predictive-maintenance.git
```

Move to the project folder

```bash
cd TRUPTI-predictive-maintenance
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
Predictive_Maintenance.ipynb
```

Run all notebook cells sequentially to reproduce the results.

---

## 🚀 Future Improvements

- Deploy the model as a web application using Flask or FastAPI.
- Integrate real-time IoT sensor data.
- Support live machine health monitoring.
- Implement Explainable AI (SHAP/LIME) for prediction interpretation.
- Train Deep Learning models on larger industrial datasets.
- Deploy the application on cloud platforms such as AWS or Azure.

---

## 👩‍💻 Author

**Trupti Shashikant Panchwatkar**

GitHub: https://github.com/truptip2005
