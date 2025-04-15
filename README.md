# House-Price-Prediction
The project is aimed at predicting house prices using various regression and Ensemble techniques with hyperparameter tuning.

# 🔍 ML Model Selection & Visualization

This repository demonstrates a complete workflow for **machine learning model selection**, performance comparison, and result visualization using Python. The code is modularized into multiple Jupyter notebooks to ensure clarity and reusability.

---

## 📁 Notebooks Overview

### 📘 `index.ipynb`
The entry point of the project. This notebook provides:
- Dataset loading
- Basic exploration
- Data preprocessing
- Feature selection and engineering

### ⚙️ `Model_selection.ipynb`
This notebook handles:
- Splitting data into training and test sets
- Training various models (e.g., Linear regression, ridge regression, random forest regression, XGboost)
- Comparing models based on r2 score, mean squared error, root mean squared error
- hyperparameter tuning
- Selecting the best performing model

### 📊 `visualize.ipynb`
Used for:
- outlier detection
-univariate data analysis on price variable

---

## 🛠️ Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/shubhashish06/House-Price-Prediction.git
cd ml-model-selection
pip install -r requirements.txt

🔧 Requirements

Main dependencies:
	•	scikit-learn
	•	matplotlib
	•	seaborn
	•	pandas
	•	numpy
	•	jupyter


✅ Project Goals
	•	Provide a reproducible framework for model selection
	•	Visualize results effectively for better interpretability
	•	Serve as a template for future ML projects


📌 License

This project is licensed under the MIT License. See the LICENSE file for details.
