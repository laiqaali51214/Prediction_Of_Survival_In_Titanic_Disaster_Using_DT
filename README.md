# Prediction of Survival in Titanic Disaster Using Decision Trees

## Overview
This project aims to predict passenger survival in the Titanic disaster using a Decision Tree (DT) model. The dataset contains passenger details such as age, gender, class, and ticket fare. The objective is to train a classifier that can predict whether a passenger survived based on these features.

## Dataset
The dataset includes the following attributes:
- **PassengerId**
- **Pclass (Ticket Class: 1st, 2nd, 3rd)**
- **Name**
- **Sex**
- **Age**
- **SibSp (Number of Siblings/Spouses aboard)**
- **Parch (Number of Parents/Children aboard)**
- **Ticket Number**
- **Fare (Ticket Price)**
- **Cabin**
- **Embarked (Port of Embarkation: C, Q, S)**
- **Survived (Target Variable: 0 = No, 1 = Yes)**

## Implementation Details
The project is implemented in a Jupyter Notebook using Python. The key steps involved are:
1. **Data Preprocessing:**
   - Loading the dataset
   - Handling missing values
   - Encoding categorical variables
   - Splitting the dataset into training and testing sets
2. **Model Training:**
   - Initializing and training a Decision Tree classifier
   - Tuning hyperparameters for improved performance
3. **Model Evaluation:**
   - Measuring accuracy, precision, recall, and F1-score
   - Visualizing the Decision Tree
   - Generating a confusion matrix

## Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn (for machine learning model)
- Pandas & NumPy (for data manipulation)
- Matplotlib & Seaborn (for visualization)


## Results
The trained Decision Tree model provides insights into the factors influencing survival on the Titanic. The classification performance is evaluated using:
- Accuracy Score
- Precision, Recall, and F1-score
- Confusion Matrix Visualization


