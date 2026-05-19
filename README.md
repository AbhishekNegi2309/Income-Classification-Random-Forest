# Income Classification using Random Forest  
Machine learning project predicting whether an individual earns more than 50K per year using Classification Analysis

## Project Overview  
This project predicts whether a person’s annual income exceeds 50K based on demographic, education, and employment attributes using machine learning models (Random Forest Classifier).  
It also compares model performance using different numbers of decision trees and performs feature selection using feature importance.

## Dataset  
- Source: UCI Machine Learning Repository - Adult Income Dataset  
- Dataset type: Census Income Classification Dataset  
- Target variable: Income (>50K or <=50K)  

## Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## Models Used  
- Random Forest (10 Decision Trees)  
- Random Forest (100 Decision Trees)  

## Results  
- Best Model Accuracy: *To be updated after training*  
- Key Insights:
  - Feature importance helps identify key predictors of income
  - Capital gain and education level are expected strong predictors
  - Increasing number of trees improves model stability and accuracy


```text
Project Structure
Income-Classification-Random-Forest/
├── data/ # Dataset storage (optional)
├── notebooks/
│   └── income_classification.ipynb # Main analysis notebook
│
├── Data Preprocessing/
│   ├── missing value handling
│   ├── encoding categorical variables
│   └── feature scaling
│
├── Exploratory Data Analysis (EDA)
│   ├── Univariate Analysis
│   ├── Bivariate Analysis
│   └── Correlation Analysis
│
├── Machine Learning Models
│   ├── Random Forest (10 estimators)
│   ├── Random Forest (100 estimators)
│   └── Feature Selection using importance scores
│
├── Evaluation
│   ├── Accuracy Score
│   ├── Confusion Matrix
│   └── Classification Report
│
├──Pipeline-Income-Classifier
│
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```

License

CC0: Public Domain

## Initialize Git (local)


## How to Run
1. Clone the repo
2. Open notebook in Jupyter
3. Run all cells

## 👤 Author
Abhishek Negi
