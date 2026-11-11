# Smart Wine Identifier 🍷

## Project Overview
This project focuses on classifying wine varieties using Machine Learning techniques. The objective is to predict the wine variety based on its chemical characteristics.

## Dataset
The dataset contains:
- 178 observations
- 13 numerical input features
- 1 target variable: `WineVariety`
- 3 wine classes: 0, 1, and 2
- No missing values

## Methodology
1. Data loading and exploration
2. Feature and target separation
3. Training and testing data split (80% / 20%)
4. Feature scaling using StandardScaler
5. Model training using Support Vector Machine (SVM)
6. Model evaluation
7. Prediction of new wine samples

## Results

| Metric | Score |
|---|---:|
| Accuracy | 97.22% |
| Precision | 97.78% |
| Recall | 96.67% |

The model achieved a Recall score above the challenge requirement of 95%.

## Predictions
The model predicted the following wine varieties for the two new samples:

- Sample 1: Class 0
- Sample 2: Class 1

## Files
- `TP4_Wine_Classification.ipynb`: Jupyter Notebook containing the complete implementation.
- `wine_classifier.pkl`: Trained SVM model.
- `wine_scaler.pkl`: Feature scaling object.

## Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Google Colab.

## Author
Ibtihel Marzouki Ines Jouini

