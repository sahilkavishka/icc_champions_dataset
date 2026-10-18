# 🏏 ICC Champions Trophy — Historical Match Analytics & Machine Learning Intelligence

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)](https://scikit-learn.org/)
[![SHAP](https://img.shields.io/badge/Explainability-SHAP-red)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-success)](#)

An exploratory data science and machine learning research project analyzing historical **ICC Champions Trophy** tournaments from 1998 to 2017. Features unsupervised team clustering (K-Means & PCA), match outcome prediction with ensemble trees, and model interpretability using **SHAP** values.

---

## 📌 Project Overview

The ICC Champions Trophy is one of world cricket's premier One Day International (ODI) competitions. This project uncovers deep statistical narratives, head-to-head dominance patterns, venue impact, and match-winning factors across decades of tournament history:
* **Multi-Tournament Dataset:** Historical records detailing match results, innings scores, toss decisions, day/night conditions, winning margins, player of the match awards, and player performance lists.
* **Unsupervised Clustering:** Segmenting team performance profiles across eras using Principal Component Analysis (PCA) and K-Means clustering.
* **Match Winner Classification:** Training ensemble models (Random Forest, Gradient Boosting) to predict match outcomes based on toss decisions, venue conditions, and team momentum.
* **Model Explainability with SHAP:** Utilizing SHAP (SHapley Additive exPlanations) summary and force plots to quantify feature contributions behind each prediction.

---

## 🚀 Key Data Science & ML Components (`icc_champions.ipynb`)

### 1. 🧹 Data Cleaning & Preprocessing
* Cleans and merges match result records (`all_champions_trophy_matches_results.csv`) and player roster data (`all_champions_trophy_players_list.csv`).
* Standardizes ground names, winning margins, day/night conditions, and toss winner correlations.
* Features categorical label encoding (`LabelEncoder`) and feature scaling (`StandardScaler`).

### 2. 🔍 Unsupervised Analysis (PCA & K-Means)
* Reduces multi-dimensional tournament statistics into 2D principal components.
* Identifies distinct performance clusters that group teams by historical dominance and tournament resilience.

### 3. 🤖 Supervised Match Prediction (Random Forest & Gradient Boosting)
* Trains classifiers to predict match winners evaluated via:
  * Accuracy score & Classification Report
  * Confusion Matrix & ROC-AUC curves
  * Precision-Recall curves

### 4. 🧠 SHAP Interpretability
* Demystifies the machine learning model by explaining the exact weight of toss decisions, venue bias, and historical head-to-head records on match outcomes.

---

## 📂 Repository Structure

```text
icc_champions_dataset/
│
├── all_champions_trophy_matches_results.csv   # Historical match records (1998–2017)
├── all_champions_trophy_players_list.csv      # Player rosters & participant data
│
├── icc_champions.ipynb                        # Comprehensive EDA, PCA, ML & SHAP analysis
└── README.md
```

---

## ⚡ How to Run

### 1. Clone this repository
```bash
git clone https://github.com/sahilkavishka/icc_champions_dataset.git
cd icc_champions_dataset
```

### 2. Set up virtual environment
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
```

### 3. Install required packages
```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap jupyter
```

### 4. Run the Jupyter Notebook
```bash
jupyter notebook icc_champions.ipynb
```

---

## 👨‍💻 Author

**Sahil Kavishka**  
*Data Science Undergraduate @ Sabaragamuwa University of Sri Lanka*  
* [LinkedIn](https://www.linkedin.com/in/sahilkavishka/)
* [GitHub](https://github.com/sahilkavishka)
* [Portfolio](https://sahilkavishka.github.io/portfolio/)
