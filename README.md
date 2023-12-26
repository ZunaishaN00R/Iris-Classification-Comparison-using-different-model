# Iris Classification Comparison using Different Models

The provided code uses the Iris flower dataset from the scikit-learn library to compare the performance of four different machine learning models: Logistic Regression, Support Vector Machine (SVM), Decision Tree, and Random Forest. The evaluation is done using cross-validation scores, and the model with the highest mean accuracy is identified as the best-performing model. The code then generates a bar chart to visually compare the mean accuracy scores of each model, highlighting the best-performing model. Finally, the chart is displayed using Matplotlib.
Use iris flower dataset from sklearn library and use cross_val_score against following models to measure the performance of each. In the end figure out the model with best performance:
- Logistic Regression
- SVM(Support Vector Machine)
- Decision Tree
- Random Forest

  
## Importing Libraries

- Import necessary libraries, including scikit-learn modules for dataset loading, model creation, and cross-validation.
- Also, import NumPy for numerical operations.

## Loading the Iris Dataset

- Load the Iris dataset using the `load_iris` function from scikit-learn.
- Separate the features (X) and target variable (y).

## Defining Models

- Create instances of four different models: Logistic Regression, SVM, Decision Tree, and Random Forest.

## Cross-Validation and Model Comparison

- Use a loop to iterate through each model and calculate the mean accuracy using 5-fold cross-validation.
- Print the mean accuracy for each model.

## Identifying the Best Model

- Determine the best-performing model based on the maximum mean accuracy.
- Print the name of the best model.

## Plotting Model Comparison

- Create a bar chart to visualize and compare mean accuracy scores of each model.
- Highlight the bar corresponding to the best-performing model.
- Annotate the chart with mean accuracy scores and label the best-performing model.

## Displaying the Chart

- Show the generated bar chart using Matplotlib.
