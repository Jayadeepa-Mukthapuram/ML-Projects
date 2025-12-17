# Handwritten Digits Classification – SVM

This project uses a **Support Vector Machine (SVM)** to classify handwritten digits (0–9) from the digits dataset.

## Model Used
- **Algorithm:** Support Vector Machine (SVM)
- **Kernel:** RBF (default)
- **Type:** Multi-class Classification

## Dataset
- **Dataset:** sklearn Digits Dataset
- **Classes:** Digits from 0 to 9
- **Features:** 8×8 pixel image values (64 features per sample)

## Data Preprocessing
- Loaded digits dataset from `sklearn.datasets`
- Flattened image data into feature vectors
- Split data into training and testing sets

## Model Training
- Trained using `SVC`
- Evaluated on unseen test data

## Accuracy
- **Test Accuracy:** **0.983 (98.3%)**

## Model Saving
- Trained model saved using `pickle` for reuse:
  ```python
  digits_model.pkl

## Libraries Used
- scikit-learn
  pickle
  pandas

## Use Case

This project demonstrates how SVM can effectively classify image-based data and how trained models can be saved and reused in real-world applications.
