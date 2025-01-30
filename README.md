# Titanic Survival Prediction

This project predicts passenger survival on the Titanic using Machine Learning models: Logistic Regression, Random Forest, and a Neural Network. The dataset used is the Titanic dataset.

## Dataset

The dataset is taken from Kaggle: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset).

It includes the following features:

- **Survived**: Target variable (0 = No, 1 = Yes)  
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Sex**: Gender of the passenger  
- **Age**: Age in years  
- **SibSp**: Number of siblings/spouses aboard  
- **Parch**: Number of parents/children aboard  
- **Ticket**: Ticket number  
- **Fare**: Passenger fare  
- **Cabin**: Cabin number (dropped due to missing values)  
- **Embarked**: Port of embarkation (C, Q, S)  

## Dependencies

Ensure you have the following libraries installed before running the code:

- Python3  
- numpy  
- pandas  
- scikit-learn  
- tensorflow  
- matplotlib  
- seaborn  

## How to Run the Code

1. Clone the repository or download the script.  
2. Place the `Titanic-Dataset.csv` file in the same directory as the script.  
3. Run the script using Python:

   ```bash
   python Titanic_ML_Model.py

## Model Performance

The script trains three models and evaluates their performance using Accuracy, Precision, Recall, and F1-Score. The final comparison is displayed in a DataFrame.

## Conclusion

In conclusion, Logistic Regression emerges as the best model for Titanic survival prediction due to its strong balance across all metrics
