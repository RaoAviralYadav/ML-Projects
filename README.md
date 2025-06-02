# 🧠 Machine Learning Projects Repository

Welcome to my Machine Learning Projects Repository! This repository includes my end-to-end machine learning projects focused on solving real-world problems using data science and predictive modeling techniques. Each project includes problem statements, data exploration, model building, evaluation, and insights.

---

## 📁 Projects Overview

### 🔬 Project 1: Lung Cancer Prediction

**Type:** Minor Project  
**Objective:**  
Develop a predictive model to determine the likelihood of lung cancer in individuals based on features related to lifestyle, symptoms, and medical history.

#### 🔍 Problem Statement
Lung cancer is one of the leading causes of cancer-related deaths globally. Early detection is critical for improving treatment success rates. This project aims to leverage machine learning to assist in the early diagnosis of lung cancer and potentially improve patient outcomes.

#### 🎯 Goal
Predict whether an individual has lung cancer using a dataset containing various health and lifestyle attributes.

#### 📊 Dataset Information
- **Total Records:** 309
- **Features:** 16 columns
- Each row corresponds to an individual's attributes and lung cancer status.

#### 🧬 Features Used
- GENDER (M/F)
- AGE
- SMOKING (1 = NO, 2 = YES)
- YELLOW_FINGERS (1 = NO, 2 = YES)
- ANXIETY (1 = NO, 2 = YES)
- PEER_PRESSURE (1 = NO, 2 = YES)
- CHRONIC_DISEASE (1 = NO, 2 = YES)
- FATIGUE (1 = NO, 2 = YES)
- ALLERGY (1 = NO, 2 = YES)
- WHEEZING (1 = NO, 2 = YES)
- ALCOHOL_CONSUMING (1 = NO, 2 = YES)
- COUGHING (1 = NO, 2 = YES)
- SHORTNESS_OF_BREATH (1 = NO, 2 = YES)
- SWALLOWING_DIFFICULTY (1 = NO, 2 = YES)
- CHEST_PAIN (1 = NO, 2 = YES)
- LUNG_CANCER (Target Variable: YES / NO)

#### 📈 Model Comparison Report
Multiple machine learning models were trained and evaluated to determine the most accurate and generalizable one for production use.

#### ⚠️ Challenges Faced
A detailed report includes:
- Class imbalance handling
- Feature encoding
- Dealing with noisy or correlated features
- Model performance analysis

---

### 💻 Project 2: Laptop Price Prediction

**Type:** Major Project  
**Objective:**  
Build a regression model to predict laptop prices based on various product attributes, helping companies analyze pricing dynamics in a competitive market.

#### 🔍 Problem Statement
A consumer electronics company is aiming to understand key factors influencing laptop prices to optimize their product design and pricing strategy. The goal is to derive insights into how different specifications affect pricing.

#### 🎯 Goal
Identify significant features affecting laptop prices and build a regression model that can accurately predict the price based on those features.

#### 📊 Dataset Information
- **Target Variable:** `price` (in USD)
- **Features:** Specifications of laptops such as brand, processor, RAM, display, etc.

#### 🧬 Features Used (Example)
- Brand & Model
- Processor Type
- RAM (in GB)
- Storage Type & Size (HDD/SSD)
- GPU Type
- Screen Size & Resolution
- Operating System
- Weight
- Battery Life
- ...and more.

#### 📈 Model Comparison Report
Several models including Linear Regression, Ridge, Lasso, Decision Trees, and Random Forest were evaluated using cross-validation, RMSE, and R² scores.

#### ⚠️ Challenges Faced
The project discusses:
- Handling categorical data with high cardinality
- Normalizing skewed distributions
- Multicollinearity between numeric features
- Feature selection strategies

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn
- Regression & Classification Algorithms

---

### ❤️ Project 3: Heart Attack Risk Prediction

**Type:** Classification Project  
**Objective:**  
Build a classification model to predict the risk of heart attack in individuals based on their medical attributes and vitals.

#### 🔍 Problem Statement
Cardiovascular diseases are a leading cause of mortality worldwide. Early identification of individuals at risk of heart attacks can save lives and reduce the burden on healthcare systems. This project focuses on creating a machine learning model that analyzes patient data to predict whether a person is likely to suffer from a heart attack.

#### 🎯 Goal
Predict the probability of a heart attack occurrence using clinical and personal health data of patients.

#### 📊 Dataset Information
The dataset contains anonymized medical records for individuals, with both categorical and continuous features.

- **Target Variable:** `output` (1 = likely heart attack, 0 = unlikely)
- **Sample Size:** ~300 rows (standard UCI-style dataset)
- **Format:** `.csv`

#### 🧬 Features Used
Common features typically include:
- `age`: Age of the person
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol level
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0–3) colored by fluoroscopy
- `thal`: Type of defect (3 = normal, 6 = fixed defect, 7 = reversible defect)

> *Note: Feature names may vary depending on the dataset version used. Proper EDA was performed to clean and validate data types and distributions.*

#### 📈 Model Comparison Report
The following models were trained and evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine

Evaluation metrics:
- Accuracy
- Precision, Recall, F1 Score
- ROC-AUC
- Confusion Matrix

#### ⚠️ Challenges Faced
- Class imbalance handling
- Feature scaling (especially for distance-based models like KNN)
- Interpretation of ST segment-related features
- Optimizing model thresholds to balance sensitivity and specificity

---

## 🔬 Outcome
The final selected model achieved high accuracy and robustness across multiple metrics, and a feature importance analysis revealed which vitals and symptoms were most indicative of risk.

---

📌 *This project is especially useful for demonstrating practical classification workflows and handling of biomedical datasets.*

---


## 🚀 How to Run the Projects
1. Clone this repository.
2. Navigate to the project folder.
3. Open the Jupyter Notebook (`.ipynb`) file.
4. Run all cells in sequence.

```bash
git clone https://github.com/your-username/ml-projects-repo.git
cd ml-projects-repo
jupyter notebook
