# Iris Species Prediction Model
This project is a Python based classification task using the  Iris dataset. The objective is to demonstrate data preprocessing, model training, and evaluation of classification models.

## Installation
1. Clone the repository in an empty directory.
2. On Windows run ```setup\setup.bat```, on Unix ```setup/setup.sh``` in the terminal.
3. In the terminal run ```jupyter notebook``` and visit the webpage using the provided link in the terminal.

## Overview
The Iris dataset is a widely-used dataset in the machine learning community, featuring measurements of four features (sepal length, sepal width, petal length, and petal width) for three species of Iris flowers: setosa, versicolor, and virginica.
Libraries I will be using are:

- pandas: For organizing data.
- matplotlib: For visual aid.
- scikit-learn: Contains predefined algorithms for creating models.
- pickle: For saving and loading models.

## Progress
The project comprises the following components:

1. Importing packages: Packages that will be useful for the whole process of the development of the model are imported. These packages are listed in the overview above with their function.

2. Data preprocessing: Here, the dataset is loaded and preprocessed. Data preprocessing includes checking for missing values, examining data distribution, and encoding categorical features.

3. Data splitting: After feature and target extraction. The dataset is divided into training and testing sets, enabling the training and evaluation of machine learning models.

4. Training models: Three different classification models are employed in this project:

- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)

5. Model Evaluation: The project calculates and displays accuracy scores for each classification model to assess their performance.

6. Model Packaging: The models are saved with their names using the pickle library and stored in the Iris_Models directory. They can be loaded for use at any later time.