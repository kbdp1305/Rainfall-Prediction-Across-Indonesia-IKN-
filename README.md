# 🧠 Machine Learning Regression Project

## 📘 Overview
This repository contains a comprehensive machine learning regression workflow developed in Jupyter Notebook.  
The project covers **end-to-end data acquisition, preprocessing, feature engineering, model training, hyperparameter optimization, and evaluation**.  
It leverages various regression models (Linear Regression, Random Forest, XGBoost, LightGBM, CatBoost, AutoGluon) to compare performance and achieve optimal predictive accuracy.

---

## 🧩 Features
- **Data Acquisition & Cleaning** – Loads raw data, handles missing values using `KNNImputer`, and converts categorical columns with `LabelEncoder`.
- **Exploratory Data Analysis (EDA)** – Visualizes distributions, correlations, and relationships between features.
- **Feature Engineering** – Implements dimensionality reduction using `PCA` and creates derived features for improved model performance.
- **Model Development** – Builds multiple regression models:
  - `LinearRegression`
  - `RandomForestRegressor`
  - `XGBRegressor`
  - `LGBMRegressor`
  - `CatBoostRegressor`
  - `KNeighborsRegressor`
- **Ensemble Learning** – Combines models using `VotingRegressor` for enhanced generalization.
- **Hyperparameter Optimization** – Applies `Hyperopt` with Tree-structured Parzen Estimator (TPE) for automated tuning.
- **AutoML** – Uses `AutoGluon.TabularPredictor` to automate model selection and training.
- **Evaluation Metrics** – Compares models based on Mean Squared Error (MSE) and visualizes feature importance.

---

## 🧠 Libraries Used
```python
numpy
pandas
matplotlib
scikit-learn
xgboost
lightgbm
catboost
hyperopt
autogluon
datetime
```

---

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
```

Example `requirements.txt`:
```
numpy
pandas
matplotlib
scikit-learn
xgboost
lightgbm
catboost
hyperopt
autogluon
```

---

## 🚀 How to Run
Run the notebook in Jupyter:
```bash
jupyter notebook "Salinan_dari_Kopie_van_dataquest (1).ipynb"
```

Or execute all cells programmatically:
```python
jupyter nbconvert --to notebook --execute "Salinan_dari_Kopie_van_dataquest (1).ipynb" --output "output.ipynb"
```

---

## 📊 Results
The notebook evaluates several regression algorithms and selects the best-performing model based on:
- Lowest **Mean Squared Error (MSE)**
- Visualization of **Feature Importance**
- AutoML leaderboard (AutoGluon)

Results are visualized with `matplotlib` plots and summary tables.

---

## 🏁 Conclusion
This project demonstrates a complete regression pipeline, including:
- Data preparation and feature engineering
- Comparison of multiple ML algorithms
- Optimization with Hyperopt
- Automated model selection with AutoGluon  
It serves as a template for scalable and automated regression modeling in Python.

---

## 📜 Author
**Krisna Bayu Dharma Putra**  
📧 [linkedin.com/in/dharma-putra1305](https://linkedin.com/in/dharma-putra1305)
