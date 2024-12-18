# Classification Models Performance Comparison

This project demonstrates the implementation and comparison of five classification algorithms on a processed dataset. The goal is to evaluate their performance and determine which algorithm performs best for the given dataset.

---

## Dataset
The dataset underwent preprocessing, including:
- **Scaling:** To standardize features.
- **Outlier Removal:** Ensuring cleaner data for better model performance.

The target variable is binary, with two classes (0 and 1).

---

## Algorithms Implemented
1. **Logistic Regression**
   - A linear model that predicts probabilities for binary classification.
   - Performed the best with the highest accuracy and balanced performance across both classes.

2. **Decision Tree Classifier**
   - A tree-based model that splits data based on feature values to classify.
   - Performed well but slightly prone to overfitting.

3. **Random Forest Classifier**
   - An ensemble method using multiple decision trees for robust predictions.
   - Achieved high accuracy with strong precision and recall values.

4. **Support Vector Machine (SVM)**
   - A model that finds the optimal hyperplane to separate classes.
   - Delivered high accuracy and balanced performance.

5. **k-Nearest Neighbors (k-NN)**
   - A simple model that predicts based on the closest data points.
   - Performed the worst among all models but still achieved decent accuracy.

---



## Model Evaluation Metrics
Each model was evaluated using the following metrics:
- **Accuracy:** Overall correctness of the model.
- **Precision:** The proportion of true positive predictions.
- **Recall:** The ability to identify true positives.
- **F1-Score:** The harmonic mean of precision and recall.
- **Confusion Matrix:** Provides insights into classification errors.

---

## Results Summary
### Best Performing Algorithm
- **Logistic Regression**
  - Accuracy: 98.2%
  - Strong performance in both precision and recall, making it the most suitable algorithm for this dataset.

### Worst Performing Algorithm
- **k-Nearest Neighbors (k-NN)**
  - Accuracy: 94.7%
  - Struggled compared to other models, particularly in F1-scores.

---

## Conclusion
Logistic Regression emerged as the most robust and reliable model for this dataset. Random Forest and SVM also showed excellent performance, making them strong alternatives. Decision Tree and k-NN, while decent, were outperformed by the other models.

This project provides insights into the strengths and weaknesses of different classification algorithms and serves as a baseline for choosing the right model for similar datasets.

---


---

## Requirements
- Python 3.8+
- Scikit-learn
- NumPy
- Pandas

---

## Acknowledgments
This project was created as part of a classification task to evaluate machine learning models for binary classification. Special thanks to the tools and libraries used for implementation.

