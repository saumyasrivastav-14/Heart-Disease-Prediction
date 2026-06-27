# Heart Disease Prediction using Supervised Machine Learning

## Problem Statement
Heart disease is one of the leading causes of death worldwide. This project builds a supervised ML model to predict whether a patient has heart disease based on clinical attributes.

## Dataset
- Source: UCI Machine Learning Repository — Cleveland Heart Disease Dataset
- Link: https://archive.ics.uci.edu/dataset/45/heart+disease
- Samples: 500 | Features: 13 | Target: Binary (0=No Disease, 1=Disease)

## Project Structure
- data/ — Dataset (heart.csv)
- model/ — Trained model (.pkl files)
- notebook/ — Jupyter Notebook (.ipynb)
- results/ — EDA plots, confusion matrix, evaluation graphs

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest (Best Model)

## Results
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 75.00% | 77.78% | 62.22% | 69.14% |
| Decision Tree | 80.00% | 74.51% | 84.44% | 79.17% |
| Random Forest | 84.00% | 83.72% | 80.00% | 81.82% |

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Conclusion
Random Forest achieved best accuracy of 84%. Key features: thal, ca, cp, thalach, oldpeak.
