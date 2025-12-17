# Titanic Survival Prediction – Decision Tree

This project builds a **Decision Tree Classifier** to predict passenger survival on the Titanic dataset using basic demographic and ticket information.

## Model Used
- **Algorithm:** Decision Tree Classifier (scikit-learn)
- **Type:** Supervised Classification

## Features Used
- `Pclass` – Passenger class  
- `Age` – Passenger age  
- `Fare` – Ticket fare  
- `Sex` – Encoded using LabelEncoder  
  - male → 1  
  - female → 0  

## Data Preprocessing
- Selected relevant columns from the dataset
- Converted categorical feature (`Sex`) into numerical form using `LabelEncoder`
- Dropped non-numeric and unnecessary columns
- Split data into training and testing sets

## Model Training
- Trained using `DecisionTreeClassifier`
- Fitted on training data and evaluated on test data

## Accuracy
- **Test Accuracy:** ~0.79 (≈ 79%)

## Model Saving
- Trained model is saved using `pickle` for later use:
  ```python
  titanic_datamodel

## Libraries Used
- pandas
  scikit-learn
  pickle

## Use Case

This project demonstrates a simple end-to-end ML workflow:
data preprocessing → model training → evaluation → model persistence.
