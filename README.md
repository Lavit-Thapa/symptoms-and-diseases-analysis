# 🧠 K-Nearest Neighbors for Disease Classification

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify diseases based on a wide range of symptoms. The goal is to build an interpretable and scalable model that can assist in early-stage clinical diagnosis.

## 🔍 Problem Statement
Given a dataset with 349 features (symptoms) and 41 distinct disease classes, the objective is to accurately predict the disease category based on observed patient symptoms.

## 📊 Dataset
- **File**: `dataset.csv`
- **Features**: 349 symptom-based binary or categorical indicators
- **Target**: Disease label (multi-class classification with 41 unique classes)

## ⚙️ Workflow
1. **Data Preprocessing**
   - Handled missing values and inconsistent data
   - Label-encoded categorical variables

2. **Model Development**
   - Used `KNeighborsClassifier` from Scikit-learn
   - Trained with 80-20 train-test split

3. **Evaluation**
   - Generated and visualized the **confusion matrix**
   - Assessed the model’s performance class-wise

## 📈 Results
- The model successfully classifies a diverse range of diseases.
- Visual outputs (confusion matrix) help in understanding the strengths and weaknesses of the model across various classes.

## 📌 Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib & Seaborn

## 🤝 Contributing
Contributions are welcome! Please fork the repo and submit a pull request.

## 📬 Contact
For collaboration or questions, feel free to connect via LinkedIn - https://www.linkedin.com/in/lavit-thapa/
