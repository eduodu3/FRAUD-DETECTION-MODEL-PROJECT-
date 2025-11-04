##  Credit Card Fraud Detection Model

This project focuses on detecting fraudulent transactions in credit card data using **machine learning**. The goal is to build, evaluate, and interpret classification models that can accurately distinguish between genuine and fraudulent transactions.

---

###  Project Overview

Credit card fraud poses a major financial risk to institutions and consumers. This project applies **data preprocessing, feature engineering, and supervised learning algorithms** to build a model capable of predicting fraudulent activities based on transaction features.

Key steps include:

1. **Data Cleaning and Exploration**
2. **Feature Scaling and Sampling**
3. **Model Training and Evaluation**
4. **Performance Visualization and Insights**

---

###  Techniques and Algorithms

The notebook experiments with multiple **classification models**:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier
* Bagging and Ensemble Methods

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Curve

---

###  Dataset

The dataset used for this project is the **Credit Card Fraud Detection dataset**, originally sourced from Kaggle.
It contains transactions made by European cardholders in September 2013, featuring **284,807 transactions**, of which only **492 are fraudulent (0.172%)** — making it a highly **imbalanced dataset**.

>  Note: The original CSV file (`creditcard.csv`) is not included in this repository due to GitHub’s 100MB file size limit.
> You can manually download it from [Kaggle’s Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) and place it in your project folder before running the notebook.



### Results

The model achieves **high precision and recall**, balancing sensitivity to fraudulent transactions with minimizing false positives.
The notebook includes:

* Confusion matrices
* ROC curves
* Feature importance visualizations
* Insights into model performance

---

### Future Improvements

* Implement deep learning models (e.g., LSTM or Autoencoders).
* Deploy model via a Flask or FastAPI web service.
* Automate retraining and monitoring pipelines.

