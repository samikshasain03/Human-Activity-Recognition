# Human Activity Recognition (HAR) Using Smartphones

## 📌 Overview
This project predicts human activities (Walking, Sitting, Standing, etc.) from smartphone accelerometer and gyroscope data using machine learning. Multiple algorithms are implemented and compared to find the most accurate approach.

## 🎯 Objectives
- Build a predictive HAR model from smartphone sensor data.
- Compare performances of multiple ML/DL algorithms.
- Explore applications in health monitoring and activity tracking.

## 📂 Dataset
- **Source:** Smartphone accelerometer & gyroscope readings.
- **Features:** 561 extracted from raw signals.
- **Labels:** Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying.
- **Files:** `train.csv`, `test.csv`

## 🤖 Models & Results
| Algorithm              | Accuracy |
|------------------------|----------|
| Logistic Regression    | **95.45%** |
| Support Vector Machine | 95.18%   |
| Gradient Boosting      | 93.96%   |
| Neural Network         | 93.32%   |
| Random Forest          | 92.67%   |
| KNN                    | 88.36%   |

**Top performers:** Logistic Regression, SVM.

## ✨ Features
- Automated preprocessing (missing values, scaling, encoding)
- Confusion matrix & accuracy visualizations
- Result export for reporting

## 🛠 Requirements
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
