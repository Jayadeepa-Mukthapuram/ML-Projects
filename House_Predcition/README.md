# Buys House Prediction

This project predicts whether a person will **buy a house** based on two features:

* 'age'
* 'income'

The output is a binary value:

* '1' → Buys house
* '0' → Does not buy house

---

## Dataset

The dataset contains:

* 'age' – Age of the person
* 'income' – Annual income
* 'buys_house' – Target variable (0 or 1)

---

## Model

* Model Used: Logistic Regression
* Saved Using: 'pickle'
* Accuracy: ~0.67 (67%)

The trained model is saved as 'House_prediction.pkl' for future predictions.

---

## How to Run

1. Install dependencies

 -->bash
       pip install -r requirements.txt

2. Load and use the saved model in Python:

import pickle

# Load model
with open('House_prediction', 'rb') as f:
    model = pickle.load(f)

# Example prediction
prediction = model.predict([[35, 75000]])
print(prediction)  # 0 or 1


3. Or run 'House_prediciton(logistic_regression).ipynb' to see full workflow.



## Files


House_Prediciton/
├── House_prediciton(logistic_regression).ipynb
├── buys_house_dataset.csv
├── House_prediciton.pkl
├── README.md
├── requirements.txt


---

Simple project to understand "binary classification using Logistic Regression" with a saved model for predictions.
