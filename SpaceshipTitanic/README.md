# Spaceship Titanic – Kaggle

Machine learning project for the **Kaggle Spaceship Titanic competition**.
The objective is to predict whether a passenger was **transported to another dimension** after the spaceship encountered a spacetime anomaly.

Competition:
https://www.kaggle.com/competitions/spaceship-titanic

---

## Repository Overview

This repository contains the **data, preprocessing pipeline, model training notebooks, and generated submission files** used for the competition.

Workflow covered in the notebooks:

* Data preprocessing and feature engineering
* Exploratory analysis
* Training multiple models
* Generating Kaggle submission files

---

## Kaggle Submission Scores

| Model                       | Accuracy |
| --------------------------- | -------- |
| Histogram Gradient Boosting | 0.80757  |
| XGBoost                     | 0.80360  |
| Claude Notebook Experiment  | 0.79985  |

---

## Repository Structure

```
SpaceshipTitanic/
│
├── data/
│   ├── raw/                 # Original Kaggle dataset
│   └── processed/           # Cleaned / feature engineered data
│
├── notebooks/
│   ├── preprocess.ipynb     # Data cleaning and feature engineering
│   ├── train.ipynb          # Model training and evaluation
│   └── claude.ipynb         # Alternative modeling experiments
│
├── claude_submission.csv    # Submission generated from claude.ipynb
├── hgb_submission.csv       # Submission from Histogram Gradient Boosting model
├── xg_submission.csv        # Submission from XGBoost model
│
└── README.md
```

---

## Links

Kaggle Competition
https://www.kaggle.com/competitions/spaceship-titanic

Dataset
https://www.kaggle.com/competitions/spaceship-titanic/data
