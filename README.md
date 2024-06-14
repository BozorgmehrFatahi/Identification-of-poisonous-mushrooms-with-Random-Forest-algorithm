# Identification-of-poisonous-mushrooms-with-Random-Forest-algorithm
# Mushroom Poisonousness Classification

This project focuses on distinguishing between poisonous and non-poisonous mushrooms using a Random Forest Classifier model.

## Data
The training data is stored in a CSV file named train.csv. It contains information about various characteristics of mushrooms, including whether they are poisonous or non-poisonous.

## Data Preprocessing
The training data is loaded and preprocessed using label encoding to transform non-numerical labels to numerical labels for model training.

## Model Training
The data is split into training and testing sets with a 90%-10% split ratio. A Random Forest Classifier model is created and trained on the training data.

## Model Evaluation
The trained model is used to predict the classes for the test data. Performance metrics, such as out-of-bag score and recall score, are calculated to assess the model's accuracy and ability to identify poisonous mushrooms.

The goal of this project is to build a reliable classifier that can accurately classify mushrooms as poisonous or non-poisonous based on their characteristics.