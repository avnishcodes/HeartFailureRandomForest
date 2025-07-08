
# Heart Failure Prediction using Random Forest

This project implements a machine learning classification model using the **Random Forest algorithm** to predict the risk of heart failure based on clinical features.

## 📊 Dataset

- **Source:** [Kaggle - Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **File used:** `heart.csv`
- **Target Variable:** `HeartDisease` (0 = No, 1 = Yes)

## 🧠 Features Used

| Feature          | Description                                |
|------------------|--------------------------------------------|
| Age              | Age of the patient                         |
| Sex              | 1 = Male, 0 = Female                       |
| ChestPainType    | Type of chest pain                         |
| RestingBP        | Resting blood pressure                     |
| Cholesterol      | Serum cholesterol (mg/dl)                  |
| FastingBS        | Fasting blood sugar > 120 mg/dl (1 = true) |
| RestingECG       | Resting electrocardiographic results       |
| MaxHR            | Maximum heart rate achieved                |
| ExerciseAngina   | Exercise-induced angina (1 = Yes, 0 = No)  |
| Oldpeak          | ST depression induced by exercise          |
| ST_Slope         | Slope of the peak exercise ST segment      |

---

## 🛠️ What This Project Includes

- ✅ Dataset loading from GitHub  
- ✅ Data preprocessing (handling categoricals, missing values, scaling)  
- ✅ Random Forest training  
- ✅ Evaluation (accuracy, precision, recall, specificity, confusion matrix)  
- ✅ Feature importance visualization  
- ✅ Model tuning using GridSearchCV

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/avnishcodes/HeartFailureRandomForest.git
Open the notebook in Google Colab:

Upload or open HeartFailure_RandomForest.ipynb

Run each cell step-by-step

Make sure all dependencies are installed (Colab has them pre-installed):

pandas, numpy, matplotlib, seaborn, sklearn

📊 Outputs
Model evaluation metrics printed directly

Confusion matrix and classification metrics

Feature importance bar chart

🙌 Credits
Dataset by Fedesoriano on Kaggle

Project built by: Avnish Singh
