# Iris Flower Classification using K-Nearest Neighbors

This repository contains a Python script that demonstrates the use of the K-Nearest Neighbors (KNN) algorithm for classifying Iris flowers based on their sepal and petal measurements.

## Dataset

The Iris dataset is a classic dataset in machine learning and statistics. It contains measurements of 150 Iris flowers, with 50 flowers from each of three species:

* Iris setosa
* Iris versicolor
* Iris virginica

For each flower, the dataset includes the following features:

* Sepal length (cm)
* Sepal width (cm)
* Petal length (cm)
* Petal width (cm)

## K-Nearest Neighbors (KNN)

KNN is a simple and effective algorithm for classification. It works by finding the k nearest data points to a new data point and assigning the new data point to the class that is most common among its neighbors.

In this script, we use KNN to classify Iris flowers based on their sepal and petal measurements. We first split the dataset into a training set and a testing set. We then use the training set to train the KNN model. Finally, we use the testing set to evaluate the performance of the model.

## Usage

To run the script, you will need to have Python 3 installed along with the following libraries:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

You can install these libraries using pip:

This will train the KNN model and evaluate its performance on the testing set. The script will also generate a plot of the accuracy of the model for different values of k.

## Results

The script achieves an accuracy of 97.78% on the testing set. This indicates that the KNN model is able to effectively classify Iris flowers based on their sepal and petal measurements.

## Conclusion

This repository demonstrates the use of the KNN algorithm for classifying Iris flowers. The results show that KNN is an effective algorithm for this task. This repository can be used as a starting point for further exploration of KNN and other machine learning algorithms.
