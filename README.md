#DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

*DESCRIPTION*:

->This project implements a Decision Tree Classifier using Scikit-learn to predict outcomes based on car-related attributes. It includes data preprocessing, model training, tree visualization, and performance evaluation—all presented in a clear and structured Jupyter Notebook.

->Dataset: carsdata.csv

->The dataset contains various features about cars, such as:

Model: The name or type of the car (encoded)

Engine: Engine specification

SC/Turbo: Indicates presence of supercharger or turbo

Weight: Weight of the car

Fuel Economy: Fuel efficiency of the car

Fast: A target column that likely classifies the car as fast or not (binary classification)

Note: Categorical columns were label-encoded for machine learning compatibility.

->Objective

The goal is to:

Build a Decision Tree model to classify cars based on the features.

Visualize the decision tree structure.

Analyze model performance using evaluation metrics.

->Tools & Libraries
Python
Pandas
NumPy
Matplotlib

Scikit-learn
->ML Workflow
Data Loading & Exploration
Loaded carsdata.csv using Pandas
Displayed structure, types, and sample rows

->Data Preprocessing
Label encoding for categorical features (like model names, etc.)
Split data into X (features) and y (target: Fast)
Train-Test split with test_size = 0.2

->Model Building:
Used DecisionTreeClassifier from sklearn
Trained model on training data

->Visualization:
Visualized tree using plot_tree() with:
Colored, rounded nodes
Feature and class labels
Title for clarity

->Evaluation:
Measured Accuracy
Displayed Classification Report (Precision, Recall, F1)
Interpreted results based on how well the tree splits the data

->Tree Visualization Sample:
The decision tree plot reveals how the model splits on features like Weight, Fuel Economy, or SC/Turbo to classify cars as Fast or not. Each node shows the split condition, number of samples, Gini impurity, and class distribution.

->Results:
Accuracy Score: ~(value varies based on your data)
Precision/Recall: Provided in the classification report
Visual tree helps interpret which features drive the classification the most.

#OUTPUT:

![Image](https://github.com/user-attachments/assets/c1fee760-91d2-47d1-b7ca-8ca9356c786e)
