# 🧠 Thyroid Cancer Reoccurrence Prediction

## 📘 Overview

This project focuses on detecting the **reoccurrence of thyroid cancer** in patients who have previously undergone treatment. By analyzing historical medical data and patient profiles, a machine learning model is trained to predict whether a thyroid cancer survivor is at risk of relapse.

The notebook `thyroid_project.ipynb` includes the complete workflow — from preprocessing to model training and evaluation using a **Random Forest Classifier**.

---

## 🎯 Objective

To build a predictive system that determines whether thyroid cancer will **recur** in a patient based on past medical history and treatment responses.

---

## 📂 Dataset

The dataset (`dataset.csv`) includes comprehensive information on thyroid cancer patients, particularly focusing on those with a history of cancer. Each row represents a patient’s medical profile and outcomes.

### 🔑 Feature Descriptions:

- **Age**: Patient’s age at diagnosis or treatment time.
- **Gender**: Biological sex of the patient.
- **Smoking**: Indicates if the patient is currently a smoker.
- **Hx Smoking**: Historical record of smoking (whether the patient has ever smoked).
- **Hx Radiotherapy**: Indicates prior radiotherapy treatment.
- **Thyroid Function**: Current status of thyroid function (e.g., normal, abnormal).
- **Physical Examination**: Results from clinical physical exams.
- **Adenopathy**: Presence of enlarged lymph nodes.
- **Pathology**: Type of thyroid cancer diagnosed through biopsy.
- **Focality**: Unifocal (one tumor site) or multifocal (multiple tumor sites).
- **Risk**: Cancer risk category (low, intermediate, high).
- **T**: Tumor size and local spread (TNM classification).
- **N**: Lymph node involvement (TNM classification).
- **M**: Distant metastasis presence (TNM classification).
- **Stage**: Overall cancer stage combining T, N, and M.
- **Response**: Outcome of treatment (e.g., complete, partial, or no response).
- **Recurred**: Whether the cancer came back after treatment (target variable).

---

## 🚀 Workflow

1. Load and explore the dataset
2. Preprocess the data (handle categorical variables, missing values)
3. Split into training and testing sets
4. Train a **Random Forest Classifier**
5. Evaluate performance using accuracy, confusion matrix, and classification report
6. (Optional) Save model for reuse

---

## 🛠️ Requirements

Install the following Python packages:

```bash
pip install pandas scikit-learn
