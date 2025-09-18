# Wine-Dataset-ML-Analysis

This project applies **K-Nearest Neighbors (KNN)** to classify wines into 3 categories 
using the classic UCI Wine Dataset.

## 🔑 Key Steps
- Data loading and preprocessing
- Exploratory Data Analysis (pairplot visualization)
- Splitting into training and testing sets
- Training a KNN model (before and after scaling)
- Comparing model performance with and without StandardScaler
- Accuracy improvement from ~64% → ~90%

## 📊 Results
- Without scaling: ~64% accuracy
- With scaling: ~98% accuracy
- Scaling is crucial for distance-based models like KNN.

## 🚀 Tools & Libraries
- Python, NumPy, Pandas
- Seaborn, Matplotlib
- Scikit-learn (datasets, KNN, StandardScaler, train_test_split, metrics)

## 📌 Future Work
- Tune K values (hyperparameter tuning)
- Compare with other models (Logistic Regression, SVM, Random Forest)
- Deploy a simple web app using Streamlit

---
