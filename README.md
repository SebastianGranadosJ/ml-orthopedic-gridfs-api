# 🩺 Orthopedic Anomaly Prediction API

This project provides a REST API for running machine learning predictions to identify whether a patient presents an orthopedic anomaly based on six biomechanical attributes.  
The API supports **single and batch predictions**, lists available models, and allows selecting which model is active for inference.

A key feature of this service is that ML models are **stored and retrieved using MongoDB GridFS**, enabling efficient management of multiple models and versions.

Two models are currently available:
- **XGBoost classifier**
- **Linear Regression classifier**

The full training pipelines, preprocessing steps, evaluation, and dataset exploration can be found in a separate project:  
🔗 **https://github.com/SebastianGranadosJ/Orthopedic-Anomaly-Detection-MlModel**

---

## 🚀 Features

- Predict orthopedic anomalies from biomechanical data  
- Single prediction and batch prediction support  
- Models stored in MongoDB GridFS  
- List all available models  
- Activate specific models  
- Works with both XGBoost and scikit-learn models  

---

###  📊 Dataset Source
📂 [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Vertebral+Column)  
(Dua, D. & Graff, C., 2019)

