# Data Preprocessing, Cleaning, & Feature Engineering for ML

## 📌 Project Overview
This repository focuses on the essential **Data Engineering** phase of the machine learning pipeline. Using the **Medical Insurance Cost dataset**, this project demonstrates how to transform raw, messy data into a high-quality format optimized for predictive modeling.

The goal is to move beyond basic analysis and implement robust **feature extraction** and **engineering** techniques that directly improve model performance.

---

## 🛠️ Key Features

### 1. Data Cleaning
* **Outlier Detection:** Identifying and handling extreme values in `charges` and `bmi` using IQR and Z-score methods.
* **Integrity Checks:** Handling duplicate values and ensuring data type consistency across all features.

### 2. Feature Preprocessing
* **Encoding:** Converting categorical variables (`sex`, `region`, `smoker`) using **One-Hot Encoding** and **Label Encoding**.
* **Scaling:** Normalizing numerical features like `age` and `bmi` using **StandardScaler** to ensure uniform weight distribution during model training.

### 3. Feature Engineering & Extraction
* **Domain-Specific Features:** Creating an `is_obese` flag (BMI > 30).
* **Interaction Features:** Extracting high-impact features like `obese_smoker` to capture non-linear relationships.
* **Binning:** Transforming `age` into life-stage categories (e.g., Youth, Middle-Aged, Senior).
