# 🧬 Clinical Decision Support System for Breast Cancer Diagnosis

Machine Learning project for predicting tumor malignancy based on morphological features extracted from cell nuclei images.

This project simulates a clinical decision-support system using classical machine learning algorithms, rigorous validation methods, and interpretable results — aligned with real-world biomedical data analysis workflows.

---

## 📊 Dataset

Breast Cancer Wisconsin Dataset (UCI Machine Learning Repository)

The dataset contains numerical features describing characteristics of cell nuclei obtained from digitized images of breast tumor biopsies.

**Target variable:**

* Malignant tumor → `1`
* Benign tumor → `0`

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA)
* Clean and preprocess biomedical data
* Identify relevant tumor features
* Compare machine learning models
* Evaluate predictive performance using clinically meaningful metrics
* Provide interpretable results for decision support

---

## 🧠 Methods

### 🔬 Data Processing

* Removal of non-informative features (`id`)
* Encoding of diagnostic labels (M → 1, B → 0)
* Train/test split with stratification
* Feature scaling for appropriate models

### 🤖 Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

### 📈 Model Evaluation

* Cross-validation
* Accuracy
* Precision
* Recall (Sensitivity)
* F1-score
* ROC AUC
* Confusion Matrix
* Feature Importance Analysis

---

## 📈 Results

The models demonstrated high performance in distinguishing malignant from benign tumors.

Random Forest achieved the best balance between sensitivity and specificity, making it particularly suitable for clinical decision-support scenarios.

---

## 🧬 Feature Importance

Analysis revealed that tumor size and shape irregularity features contribute most to malignancy prediction.

These findings are consistent with established clinical knowledge about cancer progression and tumor morphology.

---

## 🏥 Clinical Relevance

Early detection of malignant tumors is critical for improving patient outcomes.

This project illustrates how machine learning can assist clinicians by providing quantitative support for diagnostic decisions based on morphological data.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure

```
breast-cancer-clinical-ml/
│
├── data/
│   └── breast_cancer.csv
│
├── notebooks/
│   └── breast_cancer_classification.ipynb
│
├── results/
│   └── figures/
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```
git clone https://github.com/KalebeFolha/breast-cancer-clinical-ml.git
cd breast-cancer-clinical-ml
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the notebook

```
jupyter notebook
```

Open the notebook inside the `notebooks/` folder and execute the cells sequentially.

---

## 📚 Skills Demonstrated

* Data analysis of biomedical datasets
* Exploratory data analysis (EDA)
* Machine learning pipeline development
* Model comparison and validation
* Clinical metrics interpretation
* Scientific programming in Python
* Reproducible research practices

---

## 👨‍🔬 Author

**Kalebe Derek Folha**
Undergraduate in Biotechnology — UFSCar
Interested in Bioinformatics, Data Science, and Genomic Analysis

---

## 📄 License

This project is intended for educational and research purposes.
