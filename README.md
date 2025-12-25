# Medical Insurance Cost Prediction 🏥

This project analyzes a health insurance dataset to identify key factors influencing medical charges and builds a machine learning pipeline to predict future costs.

## 📋 Project Overview
- **Objective:** Predict individual medical costs billed by health insurance.
- **Key Findings:** Smoking status and BMI are the highest correlated features with insurance charges.
- **Tools Used:** Python, Pandas, Matplotlib, Seaborn, Scikit-Learn, SciPy.

## 🛠️ Data Pipeline
1. **Data Cleaning:** Standardized inconsistent categorical tags (e.g., 'M', 'male' -> 'Male').
2. **Exploratory Data Analysis (EDA):** Performed correlation analysis using Pearson's $r$ and Chi-Square tests for categorical significance.
3. **Feature Engineering:** Binned BMI into health categories (Underweight, Normal, Overweight, Obese).
4. **Preprocessing:** - One-Hot Encoding for categorical features.
   - Standard Scaling for numerical features (`age`, `bmi`, `children`) to ensure model stability.

## 📈 Key Visualizations
> *Tip: You can save one of your Seaborn heatmaps as a .png and upload it here!*

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/yourusername/Medical-Insurance-Cost-Predictor.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn scipy`
3. Run the notebook: `jupyter notebook Untitled.ipynb`

## 📊 Statistical Analysis Results
- **Numerical Features:** Pearson correlation identified `isSmoker` as a dominant predictor.
- **Categorical Features:** Chi-Square testing confirmed that `bmi_category` and `isSmoker` have a statistically significant relationship with the cost bins ($p < 0.05$).
