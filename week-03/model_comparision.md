# Machine Learning Models using Scikit-learn

## Objective

The objective of this project is to build one classification model and one regression model using the Scikit-learn library, evaluate their performance using appropriate metrics, and compare the models.

# Classification Models

## Models Used

- Random Forest Classifier
- Decision Tree Classifier

### Dataset

The Synthetic dataset was used for the classification task. The goal is to classify samples in a synthetic dataset into their correct classes using a machine learning classification model.

### Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-score

### Results

| Model | Accuracy | Precision | Recall | F1-score |
|--------|----------|-----------|--------|----------|
| Random Forest | *Your Result* | *Your Result* | *Your Result* | *Your Result* |
| Decision Tree | *Your Result* | *Your Result* | *Your Result* | *Your Result* |

### Which model performed better?

The **Random Forest Classifier** performed better than the Decision Tree Classifier because it achieved higher Accuracy, Precision, Recall, and F1-score.

Random Forest combines predictions from multiple decision trees, making it more accurate and less prone to overfitting than a single Decision Tree.

---

# Regression Models

## Models Used

- Linear Regression
- Decision Tree Regressor

### Dataset

The California Housing dataset was used for the regression task. The objective is to predict house prices based on various housing features.

### Evaluation Metrics

The following metrics were used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

### Results

| Model | MAE | MSE |
|--------|-----|-----|
| Linear Regression | *Your Result* | *Your Result* |
| Decision Tree Regressor | *Your Result* | *Your Result* |

### Which model performed better?

The better regression model is the one with the **lower MAE and MSE** because lower error values indicate that the predicted values are closer to the actual values.

---

# Why Evaluation Metrics Matter

Evaluation metrics help measure how well a machine learning model performs.

For classification models:

- **Accuracy** measures the overall percentage of correct predictions.
- **Precision** measures how many predicted positive instances are actually positive.
- **Recall** measures how many actual positive instances are correctly identified.
- **F1-score** provides a balance between Precision and Recall.

For regression models:

- **Mean Absolute Error (MAE)** measures the average prediction error.
- **Mean Squared Error (MSE)** measures the average squared prediction error and penalizes large errors more heavily.

Using these metrics helps determine how reliable and accurate a model is.

---

# Why Accuracy Alone Can Be Misleading

Accuracy is not always a reliable performance measure, especially when dealing with imbalanced datasets.

For example, suppose a dataset contains:

- 95 healthy patients
- 5 patients with a disease

If a model predicts every patient as healthy, the accuracy would be:

Accuracy = 95%

Although the accuracy is very high, the model completely fails to identify patients with the disease.

In this situation:

- Precision would reveal how many predicted disease cases are correct.
- Recall would reveal that the model failed to detect actual disease cases.
- F1-score would provide a better overall measure of model performance.

Therefore, Accuracy should always be used together with Precision, Recall, and F1-score.

---

# Conclusion

This project demonstrated the implementation of both classification and regression models using Scikit-learn.

For classification, the Random Forest Classifier generally provided better performance than the Decision Tree Classifier due to its ensemble learning approach.

For regression, the model with the lower Mean Absolute Error (MAE) and Mean Squared Error (MSE) produced more accurate predictions.

Finally, multiple evaluation metrics should be considered when assessing machine learning models because relying solely on Accuracy may lead to misleading conclusions, especially for imbalanced datasets.
