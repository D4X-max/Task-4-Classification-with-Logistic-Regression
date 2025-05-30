# Task-4---Classification-with-Logistic-Regression.

# 1. Chose a binary classification dataset
I selected a dataset where the target has two possible classes (for example, the breast cancer dataset, which classifies tumors as malignant or benign).

# 2. Performed a train/test split and standardized the features
I divided the data into training and testing sets to evaluate performance on unseen data. I also standardized the features so they all have similar scales, which helps the model learn more effectively.

# 3. Fit a Logistic Regression model
I trained a logistic regression model using the training data to learn how to predict the target class from the input features.

# 4. Evaluated the model with a confusion matrix, precision, recall, and ROC-AUC
I assessed the model’s performance by looking at the confusion matrix and metrics like precision, recall, and ROC-AUC to understand its accuracy and how well it balances correct positive and negative predictions.

# 5. Tuned the threshold and explained the sigmoid function
I adjusted the probability threshold to optimize the model for my needs. The sigmoid function takes any number and turns it into a value between 0 and 1, making it easy to interpret model outputs as probabilities.