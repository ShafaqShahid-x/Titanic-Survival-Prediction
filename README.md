# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning techniques. It demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model comparison.

The project was developed using Python and Scikit-learn as part of my machine learning learning journey.

---

## Dataset

The project uses the Titanic dataset, which contains information about passengers such as:

- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Embarked Port

**Target Variable**

- Survived (0 = Did Not Survive, 1 = Survived)

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Train-Test Split
8. Logistic Regression
9. Decision Tree Classifier
10. Random Forest Classifier
11. Feature Importance Analysis
12. Model Comparison
13. Conclusion

---

## Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 79% |
| Decision Tree | 80% |
| Random Forest | 80% |

---

## Feature Engineering

A new feature named **FamilySize** was created using:

```python
FamilySize = SibSp + Parch + 1
```

This feature provides additional information about the number of family members traveling with each passenger.

---

## Key Findings

- Female passengers had a higher survival rate than male passengers.
- Passenger class was strongly associated with survival.
- Sex was the most important feature in the tree-based models.
- Decision Tree and Random Forest achieved the highest accuracy of 80%.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```
Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
└── README.md
```

---

## Future Improvements

- Perform systematic hyperparameter tuning using GridSearchCV.
- Evaluate models using cross-validation.
- Explore additional feature engineering techniques.
- Compare the performance of other machine learning algorithms.

---

## Author

**Shafaq Shahid**

BS Artificial Intelligence Student
Learning Machine Learning one project at a time.
