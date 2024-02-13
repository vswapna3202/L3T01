## L3T01 - Supervised Learning - Logistic Regression

## Iris Logistic Regression Analysis

### Overview

This task involves building a logistic regression classifier to predict whether an iris belongs to the 'Iris-setosa' class or not using the Iris dataset (`Iris.csv`). The dataset consists of three classes of irises: 'Iris-setosa', 'Iris-versicolor', and 'Iris-virginica'. The objective is to create a binary classifier that distinguishes between 'Iris-setosa' and not-'Iris-setosa' classes.

### Datasets
+ Iris.csv: Contains data on various iris and Sepal details and Petal details and Species. [Source](<Iris.csv>)

### Instructions

#### Setup and Installation

1. **Clone the Repository**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/vswapna3202/L3T01.git
     ```

2. **Navigate to the Project's Folder**
   - Navigate to the folder containing the project:
     ```
     cd L3T01 or cd <your-task-folder>
     ```

### Project Workflow

1. **Reading and Preparing the Data**
   - Read the `Iris.csv` file into the Jupyter notebook `iris_logistic_regression.ipynb`.
   - Identify the independent variables `x`.
   - Encode the dependent variable `y` such that 'Iris-setosa' is encoded as 0, and 'Iris-versicolor' and 'Iris-virginica' are both encoded as 1.

2. **Splitting the Data**
   - Split the data into a training and test set.

3. **Logistic Regression Model**
   - Use sklearn's logistic regression function to fit a model and make predictions on the test set.

4. **Confusion Matrix**
   - Use sklearn to generate a confusion matrix, which compares the predicted labels to the actual labels (gold labels).
   - Analyse the confusion matrix and provide a prediction on whether the model is likely to have higher precision, higher recall, or similar precision and recall.

5. **Model Evaluation**
   - Write your own code to calculate the accuracy, precision, and recall, and check whether your prediction was correct.

### Optional Task

- Repeat the above task, but change it so that all three categories 'Iris-setosa', 'Iris-versicolor', and 'Iris-virginica' correspond to the numeric values 0, 1, and 2, respectively. This will now be a three-class problem. Observe how this changes the confusion matrix.

## Running the Notebook

- Start Jupyter Notebook:
`jupyter notebook`  
- Open the Jupyter notebook `iris_logistic_regression.ipynb`

