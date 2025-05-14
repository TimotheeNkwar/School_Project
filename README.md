## Model Comparison: Logistic Regression, Random Forest, Naive Bayes

This repository contains a comparison of three classification models applied to a binary classification problem. The goal is to evaluate the performance of each model using various metrics such as **accuracy**, **precision**, **recall**, and **F1-score**. The models are trained on the same dataset, and their results are compared to determine the best performing model for this specific task.

### Models:

1. **Logistic Regression**
   A simple, interpretable linear model that estimates the probability of a binary outcome. It works well when the data is linearly separable and provides a solid baseline for comparison.

   * **Accuracy**: 83%

2. **Random Forest Classifier**
   An ensemble learning method that uses multiple decision trees to make predictions. It is robust to overfitting and can capture complex relationships in the data.

   * **Accuracy**: 93%
   * **Strengths**: Higher accuracy, better handling of complex feature interactions.
   * **Weaknesses**: Slower to train, risk of overfitting if not tuned.

3. **Naive Bayes**
   A probabilistic classifier that assumes feature independence, making it simple and fast. It performs well on datasets with relatively independent features.

   * **Accuracy**: 81%
   * **Strengths**: Fast, simple, effective for data with relatively independent features.
   * **Weaknesses**: Assumes feature independence, which may limit performance if violated.

### Evaluation Metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

### Results:

* The **Random Forest** model outperforms both **Logistic Regression** and **Naive Bayes**, providing the highest accuracy and best F1-scores for both classes.
* **Logistic Regression** provides a strong baseline with good accuracy, suitable for linearly separable data.
* **Naive Bayes** remains competitive for simpler, faster solutions.

---

