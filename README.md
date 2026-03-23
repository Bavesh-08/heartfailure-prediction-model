# heartfailure-prediction-model

##❤️ Heart Failure Prediction using Machine Learning
This repository contains a complete end-to-end Machine Learning pipeline to predict the presence of heart disease in patients based on clinical parameters. By leveraging the Random Forest Classifier, the model achieves high diagnostic accuracy, providing a data-driven tool for early medical intervention.

##📊 Dataset Overview
The dataset includes clinical records of patients, featuring 13 key physiological attributes:

Demographics: Age, Sex.

Clinical Measurements: Resting Blood Pressure (trestbps), Cholesterol (chol), Fasting Blood Sugar (fbs), Max Heart Rate (thalach).

Diagnostic Indicators: Chest Pain Type (cp), Resting ECG, Exercise-Induced Angina (exang), ST Depression (oldpeak), and ST Slope.

##🚀 Key Features
Data Preprocessing: Automated handling of missing values and categorical encoding for medical variables.

Comparative Analysis: Performance benchmarking across multiple algorithms (Logistic Regression, SVM, and Random Forest).

High Performance: The Random Forest model achieved a peak accuracy of 98.54%.

Interactive Predictor: A built-in CLI tool that allows users to input patient data and receive a real-time diagnosis with probability scores.

Model Persistence: Trained weights are exported using pickle for seamless deployment.

##🛠️ Technical Stack
Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

Model Storage: Pickle

##📈 Model Performance
We evaluated three primary classifiers on the test set (20% split):

#Model	Accuracy
Random Forest	98.54%
Logistic Regression	79.51%
SVM	68.30%
Confusion Matrix Insights

The Random Forest model demonstrates high sensitivity and specificity. The confusion matrix shows minimal False Negatives (FN), which is critical in a medical context where missing a diagnosis is more costly than a false alarm.

Prediction: HEART DISEASE DETECTED!
Probability: 59.0%
