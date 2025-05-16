# Customer_Churn_ANN
Customer Churn Prediction
This project is focused on predicting customer churn using a dataset from a bank. It includes data preprocessing, exploratory data analysis (EDA), and the development of a neural network classifier using TensorFlow/Keras.
 Table of Contents
About

Dataset

EDA & Visualization

Modeling

Evaluation

Requirements

Usage

License

 About
Customer churn refers to when a customer stops using a company's services. Understanding and predicting churn is critical for business strategies. In this project, we build a neural network to predict whether a customer will churn or not based on features like age, credit score, balance, etc.

 Dataset
File: Churn_Modelling.csv

Source: Kaggle or similar customer churn dataset

Attributes include:

CreditScore

Geography

Gender

Age

Tenure

Balance

NumOfProducts

HasCrCard

IsActiveMember

EstimatedSalary

Exited (Target variable)

 EDA & Visualization
We conducted thorough Exploratory Data Analysis to understand patterns in the data:

Histograms and boxplots for numerical variables

Boxplots grouped by churn (Exited)

Count plots for categorical features

Correlation heatmap

 Modeling
We used a neural network classifier with the following architecture:

Input layer: 11 neurons

Hidden layers: 2 hidden layers with 11 neurons each, using sigmoid activation

Output layer: 1 neuron with sigmoid activation

Training settings:

Optimizer: Adam

Loss function: Binary Crossentropy

Epochs: 100

Batch size: 50

Validation split: 20%

 Evaluation
Evaluation metrics include accuracy.

The model is evaluated on the test set using accuracy_score.

Additional metrics like confusion matrix, precision, recall, and F1-score can be added.

🛠 Requirements
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

tensorflow (Keras)

Install dependencies using:


pip install -r requirements.txt
