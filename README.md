#DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

# TASK-1

# DESCRIPTION:

# Car Classification using Decision Tree Classifier

This project implements a **Decision Tree Classifier** using **Scikit-learn** to classify cars as **Fast** or **Not Fast** based on various attributes. The model is built and evaluated using a structured **Jupyter Notebook**, including preprocessing, model training, visualization, and performance analysis.

# Dataset

- **File**: `carsdata.csv`
- **Features Include**:
  - `Model`: Encoded name/type of the car
  - `Engine`: Engine specification
  - `SC/Turbo`: Indicates presence of Supercharger or Turbo
  - `Weight`: Weight of the car
  - `Fuel Economy`: Fuel efficiency
  - `Fast`: **Target column** — binary classification (1 = Fast, 0 = Not Fast)

# Objective

- Build a machine learning model to **predict car performance** (Fast or Not)
- Visualize the **Decision Tree** structure
- Evaluate model using standard **classification metrics**

# Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**
- **Scikit-learn**

# Workflow

# 1.Data Exploration
- Loaded data with Pandas
- Inspected column types and sample rows

# 2.Data Preprocessing
- Label-encoded categorical features
- Defined `X` (features) and `y` (target: `Fast`)
- Performed a **Train-Test Split** (80/20)

# 3.Model Training
- Applied `DecisionTreeClassifier` from `sklearn.tree`
- Trained the model on the training set

# 4.Tree Visualization
- Used `plot_tree()` to visualize splits
- Displayed:
  - Colored, rounded nodes
  - Feature names
  - Class labels
  - Gini impurity & sample count

# 5.Evaluation
- Computed **Accuracy Score**
- Generated **Classification Report** (Precision, Recall, F1-Score)
- Interpreted how tree structure reflects feature importance

# Sample Decision Tree Output

The decision tree reveals how features like **Weight**, **Fuel Economy**, and **SC/Turbo** impact the prediction of whether a car is fast. Each split node explains the condition, sample size, and class breakdown.

# Results

- **Accuracy**: ~ (Varies with dataset)
- **Precision/Recall/F1**: Detailed in the classification report
- **Insights**: Visual tree aids in identifying the **most influential features**

# Future Scope

- Add **Hyperparameter Tuning** (e.g., `max_depth`, `min_samples_split`)
- Compare with other classifiers like **Random Forest** or **SVM**
- Deploy as a simple web demo using **Streamlit**

#OUTPUT:

![Image](https://github.com/user-attachments/assets/a51a2a2e-bd5c-4622-b729-576f6c45711b)
