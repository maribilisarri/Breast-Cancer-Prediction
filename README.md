# Breast Cancer Prediction using Logistic Regression

This Google Colab notebook demonstrates the use of logistic regression for breast cancer prediction. The notebook utilizes the scikit-learn library for machine learning tasks and matplotlib for data visualization.

**Data:**

* The notebook uses the Breast Cancer Wisconsin (Diagnostic) Dataset, which is readily available in scikit-learn.
* This dataset contains 30 features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
* The target variable indicates whether the diagnosis is malignant or benign.

**Methodology:**

1. **Data Inspection and EDA:**
    * The notebook starts with loading the dataset and examining its structure and features.
    * Exploratory data analysis (EDA) is performed to visualize relationships between features and the target variable. This involves using scatter plots and correlation matrices.

2. **Logistic Regression Model:**
    * A logistic regression model is trained using the features and target variable.
    * Initially, the model is trained using a single feature (mean radius) to demonstrate the concept of logistic regression.
    * Later, the model is trained using all 30 features to improve prediction accuracy.

3. **Model Evaluation:**
    * The model is evaluated using a train-test split to assess its performance on unseen data.
    * The notebook uses metrics such as accuracy, precision, recall, and F1-score to evaluate the model's effectiveness.
    * A confusion matrix is generated to visualize the model's predictions.

**Results:**

* The logistic regression model achieves high accuracy in predicting whether a tumor is malignant or benign.
* The notebook provides insights into the significance of different features in the prediction process.

**Conclusion:**

This notebook demonstrates the successful application of logistic regression for breast cancer prediction. The results highlight the potential of using machine learning to assist in medical diagnosis.
