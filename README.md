This was made as a part of the project- 'Disease prediction using ML and Deep Learning'.
Thorough EDA was done for heart disease patterns in the data.
Collaborated with @Suyashthakur08 who contributed to 
https://github.com/Suyashthakur08/Brain-tumor-classification-using-Deep-Learning


# Heart Disease Prediction

This project is a machine learning application designed to predict the likelihood of heart disease in patients based on various medical attributes. It leverages popular machine learning algorithms and data preprocessing techniques to achieve reliable predictions.

## 🧠 Project Overview

Heart disease is one of the leading causes of death globally. Early detection and accurate diagnosis can significantly improve patient outcomes. This project utilizes supervised learning methods to analyze patient data and predict the presence of heart disease.

## 📊 Dataset

The dataset used contains several features relevant to cardiovascular health, such as:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- Oldpeak (ST depression induced by exercise)
- Slope of the peak exercise ST segment
- Number of major vessels (ca)
- Thalassemia (thal)
- Target (0: No disease, 1: Disease)

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest

## 🔍 Model Evaluation

Models are evaluated using:

- Accuracy score
- Confusion matrix
- Classification report
- Cross-validation

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

Run the Project
	1.	Clone the repository:

git clone https://github.com/your-username/heart_disease_prediction.git


	2.	Navigate to the project folder.
	3.	Open the Jupyter Notebook file and run each cell.

📈 Results

The Random Forest model provided the highest accuracy among all tested algorithms, indicating its strong performance for this classification task.

Thanks!
```



# Medical Recommendation System

This project presents a **Medical Recommendation System** designed to suggest treatments or precautions based on user-reported symptoms. The system leverages machine learning classification models to map symptoms to diseases and recommend appropriate medical actions.

## 🩺 Project Objective

To build an intelligent system capable of analyzing patient symptoms and predicting the most likely disease, followed by recommending basic precautions.

## 📚 Dataset

The dataset includes:

- A set of symptoms per patient
- Diagnosed disease
- Suggested precautions

It is designed to train the system on mappings between symptoms and diseases, and provide relevant medical advice.

## 🧪 Models Used

- Decision Tree Classifier
- Random Forest Classifier
- Naive Bayes Classifier

### Techniques:

- Label Encoding for categorical symptoms
- Train-test split
- Accuracy measurement

## ⚙️ Features

- Input: List of user symptoms
- Output:
  - Predicted disease
  - Recommended precautions
- Model comparison via accuracy and performance metrics

## 📊 Evaluation

Models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The Random Forest classifier generally produced the highest accuracy and better generalization on test data.

## 🚀 How to Use

### Prerequisites

Install required packages:

```bash
pip install pandas numpy scikit-learn

Running the Notebook
	1.	Clone the repository:

git clone https://github.com/your-username/medical-recommendation-system.git


	2.	Open med-recc.ipynb in Jupyter Notebook or any compatible environment.
	3.	Run all cells to train models and interact with the system.

🔒 Disclaimer

This system is a prototype and is not intended to replace professional medical diagnosis. Always consult a certified healthcare provider for medical advice.

