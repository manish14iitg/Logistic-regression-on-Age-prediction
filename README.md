# ❤️ HeartCare-ML

HeartCare-ML is a machine learning project designed to predict the likelihood of heart disease based on a set of health indicators. This model utilizes a Random Forest Classifier to make predictions and includes comprehensive performance metrics to evaluate the model's effectiveness.

## 📋 Project Overview

This project uses a dataset with multiple features related to cardiovascular health. The features include age, sex, chest pain type, resting blood pressure, cholesterol levels, and others, which are used to predict the presence or absence of heart disease.

### 📝 Features Used:
- **age**: Age in years
- **sex**: 1 = male; 0 = female
- **cp**: Chest pain type (four types)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results (three categories)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (three categories)
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalium stress result (three categories)
- **target**: 1 = presence of heart disease, 0 = absence of heart disease

### 📦 Dependencies
All the dependencies required to run the model are listed in the `requirements.txt` file. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## 🚀 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/maheera421/HeartCare-ML.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the `HeartCare-ML.ipynb` notebook to train and test the model.

## 📊 Model Evaluation

The project includes various evaluation metrics such as:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC Score
- Confusion Matrix

These metrics help in understanding the performance and reliability of the model.


