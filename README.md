# Sonar Rock vs Mine Classification

This is a Machine Learning classification project that predicts whether an object detected by sonar signals is a Rock or a Mine.

The project uses Logistic Regression and the Sonar dataset.

## Project Overview

Sonar signals are used to detect objects underwater. In this project, Machine Learning is used to classify the detected object into two classes:

* R = Rock
* M = Mine

The dataset contains 208 samples and 60 numerical features for each sample.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook
* Logistic Regression

## Dataset

The dataset contains:

* 208 samples
* 60 input features
* 1 target column

The target column contains two classes:

```text
R = Rock
M = Mine
```

There are 111 Mine samples and 97 Rock samples in the dataset.

## Machine Learning Model

The project uses Logistic Regression for classification.

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
model.fit(X_train, Y_train)
```

## Train-Test Split

The dataset was divided into training and testing data.

* Training data: 187 samples
* Testing data: 21 samples

A 90:10 train-test split was used.

## Model Accuracy

Training Accuracy: 82.35%

Testing Accuracy: 85.71%

## Prediction

After training the model, new sonar data can be given to the model to make a prediction.

The model predicts either:

```text
R = Rock
M = Mine
```

For the sample input used in this project, the model predicted:

```text
The object is a Rock
```

## Project Workflow

```text
Load Dataset
     ↓
Explore Data
     ↓
Separate Features and Target
     ↓
Split Training and Testing Data
     ↓
Train Logistic Regression Model
     ↓
Evaluate Model
     ↓
Make Prediction
```

## What I Learned

Through this project, I learned:

* How to load a dataset using Pandas
* How to separate features and target
* How to split data into training and testing sets
* How Logistic Regression works for classification
* How to train a Machine Learning model
* How to make predictions
* How to calculate model accuracy
* How to build a simple predictive system


## Author

Pappu Ghosh

B.Tech CSE | Machine Learning Learner
