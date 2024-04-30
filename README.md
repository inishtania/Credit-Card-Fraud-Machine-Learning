# Credit-Card-Fraud-Machine-Learning

As a data scientist at a top bank in Indonesia, our team received reports from the credit card department regarding customer complaints about fraud. Customers question the absence of a fraud detection system to alert them before too many transactions become criminal, thus minimizing losses.

The dataset includes a feature called 'Class', where 0 indicates no fraudulent activity and 1 indicates detected fraud. Using the confusion matrix, we anticipate two outcomes: false positives and false negatives.

- **False positives** occur when the machine detects fraud despite no actual fraud in the data. If this persists, it could lead to credit card blocks, impacting customer trust. Estimated company losses from false positives may reach around 2 million IDR.

- **False negatives** occur when the machine fails to detect fraud despite its presence in the data. This undermines our safety reputation, as the system fails to comprehend criminal activity. The financial losses from these missed detections far exceed those from false positives.

To address this, our analysis prioritizes recall scoring to focus on reducing the number of false negatives.

**Steps to Follow:**

To address this problem, here are the steps I take:

1. Perform simple Exploratory Data Analysis (EDA) to explore the dataset.
2. Define the preprocessing steps that I should take before modeling.
3. Perform cross-validation to determine the best-fit model among logistic regression, K-Nearest Neighbors (KNN), and decision tree.
4. Select the best-fit model and then perform hyperparameter tuning.
5. Test the model on the test dataset to evaluate the results.

If you want  to get the dataset please go to this link https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
