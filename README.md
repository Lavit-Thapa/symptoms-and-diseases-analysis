# Disease Prediction Using KNN Classifier

This project applies the K-Nearest Neighbors (KNN) classification algorithm to predict diseases based on patient-reported symptoms.

## 📂 Dataset Overview
- **Records**: 4,920
- **Features**: 17 symptom columns + 1 target (`Disease`)
- **Missing Values**: Present in later symptom columns; addressed using preprocessing.

## ⚙️ Technologies Used
- Python
- Scikit-learn
- Pandas, NumPy

## 📊 Workflow Summary
1. **Data Preprocessing**:
   - Handled missing values
   - Label-encoded categorical variables

2. **Model Development**:
   - KNN Classifier (with k-value =5)
   - Performance evaluation using accuracy

3. **Insights**:
   - Demonstrated that symptom-based diagnosis using simple models like KNN is feasible
   - Showcased the importance of feature selection and data cleaning in medical ML

## 📎 Dataset
The dataset (`dataset.csv`) contains:
- 17 Symptom columns (`Symptom_1` to `Symptom_17`)
- Target variable: `Disease`

## 🤝 Contributing
Contributions are welcome! Please fork the repo and submit a pull request.

## 📬 Contact
For collaboration or questions, feel free to connect via LinkedIn - https://www.linkedin.com/in/lavit-thapa/.

