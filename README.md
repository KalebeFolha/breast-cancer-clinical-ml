# breast-cancer-clinical-ml
# 🧬 Clinical Decision Support System for Breast Cancer Diagnosis

Machine Learning project for predicting tumor malignancy based on morphological features extracted from cell nuclei images.

This project simulates a clinical decision-support system using classical ML algorithms and rigorous evaluation methods.

---

## 📊 Dataset

Breast Cancer Wisconsin Dataset (UCI Machine Learning Repository)

The dataset contains numerical features describing characteristics of cell nuclei obtained from digitized images of breast tumor biopsies.

Target variable:

- **Malignant (1)**
- **Benign (0)**

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA)
- Identify relevant tumor features
- Compare machine learning models
- Evaluate predictive performance using clinical metrics
- Provide interpretable results

---

## 🧠 Methods

### Data Processing

- Removal of non-informative features
- Encoding of diagnostic labels
- Train/test split with stratification
- Feature scaling when required

### Machine Learning Models

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

### Model Evaluation

- Cross-validation
- Accuracy
- Precision
- Recall (Sensitivity)
- F1-score
- ROC AUC
- Confusion Matrix

---

## 📈 Results

The models demonstrated high performance in distinguishing malignant from benign tumors.

Random Forest achieved the best balance between sensitivity and specificity.

---

## 🧬 Feature Importance

Analysis revealed that tumor size and shape irregularity features contribute most to malignancy prediction.

These findings are consistent with clinical knowledge about cancer progression.

---

## 🏥 Clinical Relevance

Early and accurate detection of malignant tumors is critical for improving patient outcomes.

This project demonstrates how machine learning can assist diagnostic decision-making.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure
