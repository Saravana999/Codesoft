Iris Dataset Classification
This repository contains code for analyzing the Iris dataset and training three different machine learning models: K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Decision Tree. The goal is to classify iris flowers into one of three species based on four features.

Table of Contents
Introduction
Dataset
Visualizations
Modeling
Evaluation
Installation
Usage
Contributing
License
Introduction
The Iris dataset is a classic dataset in machine learning and statistics. It contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. Each sample is labeled as one of three species: setosa, versicolor, or virginica.

Dataset
The dataset is sourced from the following URL:
IRIS Dataset

Visualizations
The code includes several visualizations to understand the dataset better:

Pairplot: Displays the relationships between pairs of features, colored by species.
Heatmap: Shows the correlation matrix of the features.
Boxplot: Visualizes the distribution of each feature.

Modeling
The dataset is split into training and test sets. The features are standardized using StandardScaler. Three machine learning models are trained and evaluated:

K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
Evaluation
Each model is evaluated using a classification report and a confusion matrix. The classification report includes precision, recall, f1-score, and support. The confusion matrix shows the actual vs. predicted classifications.

Installation
To run this code, you need to have Python installed along with the following libraries:

pandas
matplotlib
seaborn
scikit-learn

You can install the required libraries using pip:
  pip install pandas matplotlib seaborn scikit-learn

Usage
  1.Clone this repository:
     git clone https://github.com/Saravana999/iris-classification.git
     cd iris-classification
  2.Run the Jupyter Notebook or Python script containing the code.

  3.The visualizations and model evaluations will be displayed as output.
