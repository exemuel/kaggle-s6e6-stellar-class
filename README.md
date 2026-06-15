# Kaggle Playground S6E6: Predicting Stellar Class 🌌

This repository contains my code and approach for the [Kaggle Playground Series - Season 6, Episode 6](https://www.kaggle.com/competitions/playground-series-s6e6). 

## 🎯 Objective
The goal of this competition is to predict the stellar class (`GALAXY`, `STAR`, or `QSO`) based on synthetically generated tabular data. 

## 📏 Evaluation Metric
Submissions are evaluated based on **Balanced Accuracy** between the predicted class and the observed target.

## 🗂️ Project Structure
```text
├── data/                   # Raw and processed data (ignored in Git)
├── models/                 # Saved model weights (ignored in Git)
├── notebooks/              # Jupyter notebooks for EDA and Modeling
│   ├── 01-eda.ipynb        # Exploratory Data Analysis
│   └── 02-modeling.ipynb   # Baseline models and tuning
├── src/                    # Custom Python scripts
├── README.md               # Project overview
└── requirements.txt        # Python dependencies

```

## 🚀 How to Run

1. Clone this repository: `git clone https://github.com/exemuel/kaggle-s6e6-stellar-class.git`
2. Download the competition dataset from [Kaggle](https://www.kaggle.com/competitions/playground-series-s6e6/data) and place `train.csv` and `test.csv` in the `data/` folder.
3. Install dependencies: `pip install -r requirements.txt`
4. Run the notebooks in the `notebooks/` directory.

## 🏆 Current Progress

* [x] Explored data and handled missing values.
* [ ] Trained baseline LightGBM/XGBoost models.
* [ ] Hyperparameter tuning.
* [ ] Final submission.