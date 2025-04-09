# Diabetes Prediction using Logistic Regression

## Project Overview

The primary objective of this project is to build a **predictive model** for diabetes using logistic regression. The model is trained on a dataset containing various health metrics and is used to predict whether a person has diabetes or not. The project involves data preprocessing, model training, evaluation, and visualization of results.

## Design Overview

### Data Preprocessing
- **Handling Missing Values**: Columns with zero values (which are likely missing data) are replaced with the median value of the respective columns.
- **Feature Scaling**: The features are scaled using **StandardScaler** to normalize the data, ensuring that all features contribute equally to the model's performance.

### Model
- **Logistic Regression**: The model is trained using **Logistic Regression** with the preprocessed data.
- **Evaluation**: The model's performance is evaluated using the confusion matrix, which provides insights into the accuracy of predictions.

## Key Components

### Libraries Used:
- **Pandas**: For data handling and manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization, including the confusion matrix heatmap.
- **Scikit-learn**: For model training, evaluation, and data preprocessing.

### Process:
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Data Cleaning**: Missing values are handled, and scaling is applied.
3. **Model Training**: A logistic regression model is trained on the data.
4. **Model Evaluation**: The model’s accuracy is evaluated using a confusion matrix.
5. **Visualization**: The confusion matrix is visualized using a heatmap for easy interpretation.

## Algorithms Used
1. **Logistic Regression**: A machine learning algorithm used for binary classification tasks. In this project, it predicts whether a person has diabetes based on the given features.
2. **Confusion Matrix**: Used to evaluate the model's performance, showing the number of true positives, true negatives, false positives, and false negatives.

## Results:
- The confusion matrix visualizes the **accuracy** of the model's predictions, which can be interpreted to assess how well the model performs on the test data.
