Credit Score Prediction Using Stacking Regressor
This project involves building a machine learning model to predict credit scores using a variety of techniques, including stacking regressors. The code leverages multiple algorithms, performs hyperparameter tuning, and evaluates the model's performance using various metrics and plots.

Introduction
The goal of this project is to create a robust model that can predict the credit score of individuals based on various financial and demographic features. The dataset used includes both categorical and numerical variables, which are preprocessed and fed into a stacking regressor that combines the strengths of multiple models.

Usage
Ensure that the credit_score.csv file is in the root directory of the project.
Run the model_training.py script:
```python
python model_training.py
```
The script will:
Load and preprocess the data.
Perform feature encoding and scaling.
Train a stacking regressor with hyperparameter tuning.
Output the best parameters, model performance metrics, and various plots.

Model Evaluation
Mean Squared Error (MSE): A metric to measure the average squared difference between the predicted and actual values.
R² Score: Represents the proportion of the variance in the dependent variable that is predictable from the independent variables.
Cross-Validation: Ensures the model's generalization by training and validating on different subsets of the data.

Plots and Visualization
Learning Curves: Shows the model’s performance on the training set and validation set over various training set sizes.
Error Distribution: Visualizes the distribution of prediction errors.
PCA Plot: Displays the data in a 2D space using Principal Component Analysis, color-coded by credit score.
Partial Dependence Plots: Illustrates the relationship between specific features and the predicted outcome.

