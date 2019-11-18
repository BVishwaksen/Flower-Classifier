# Iris-Flower-Classifier
A machine learning based system that can be used to classify the flowers based on their petal and sepal features.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
The iris flower dataset contains the different classes of iris flowers. Iris flowers are classified into three types based on their petal widht / height and their sepal widht / height. The main objective of this project is to demonstrate the application of classification algorithm KNN on this multivariate dataset.
### Requirements
Python 3.5 or above version with numpy,pandas,matplotlib,scikit-learn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `flower_predictor.ipynb` file. In that file change the values of `flower_features` variable.
The order of the values are `'sepal-length','sepal-width','petal-length','petal-width'` and then run all the cells.The flower class is displayed as the output of the last cell.

### Dataset
The dataset used in this project is iris dataset from scikit learn dataset library.
It can be downloaded at <https://archive.ics.uci.edu/ml/datasets/Iris>
### Technical-Details
##### Dataset Details
The dataset contains 5 attributes and 150 instances.
The column details are
sepal length in cm
sepal width in cm
petal length in cm
petal width in cm
class:(Iris Setos/ Iris Versicolour / Iris Virginica)
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `flower_trainer.ipynb` is for training the data and the `flower_predictor.ipynb` is to load the trained data and to predict results.The `flower_model.sav` is the model that is saved. The `iris.data` is the file that contains the dataset.
### Algorithm
The Wine-Classifier is a classification problem.As here there are more than two types of target values (Iris Setosa,Iris Versicolour and Iris Virginica) this comes under `multinomial classification`.
The algorithm used in this is `K Nearest Neighbours`.More details about this algorithm can be found at
<https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.
