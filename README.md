# 🧠 Lead Conversion Prediction Project

This project uses both static and dynamic customer interaction data to predict lead conversion using Machine Learning and Deep Learning models.

## 📂 Project Structure

- `logistic_regression_model.ipynb`: Baseline model using static features
- `random_forest_model.ipynb`: Traditional ML model with tuned parameters
- `lstm_model.ipynb`: Time-series model using dynamic lead interaction sequences
- `data/`: Contains cleaned and preprocessed datasets
- `models/`: Saved trained models (`.pkl`, `.keras`)

## 🛠️ Features Used

### Static Features:
- Lead Origin, Lead Source, Total Visits, Time Spent, etc.

### Dynamic Features:
- Type of Interaction, Timestamp, Time Between Interactions, Outcome, etc.

## ⚙️ Technologies

- Python, NumPy, Pandas, Scikit-learn, Keras, TensorFlow, Matplotlib
- Jupyter Notebooks

## 📊 Goal

To compare traditional models and LSTM-based models for improving the accuracy of predicting lead conversions.

## 🔗 Results Summary

- Logistic Regression: ~84% Accuracy
- Random Forest: ~87% Accuracy
- LSTM Model: ~91% Accuracy on dynamic data

## 📁 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
