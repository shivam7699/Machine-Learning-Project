Titanic - Machine Learning from Disaster
This repository contains the code and resources for the "Titanic - Machine Learning from Disaster" machine learning project. The goal of this project is to predict the survival status of passengers aboard the Titanic based on various features such as age, gender, ticket class, etc.

Dataset
The dataset used for this project is the famous Titanic dataset, which is available on Kaggle. It consists of information about passengers on board the Titanic, including features like age, sex, ticket class, number of siblings/spouses aboard, number of parents/children aboard, fare, and more. The dataset is split into two CSV files: train.csv (used for training the model) and test.csv (used for testing the model).

Dependencies
To run the code in this repository, you will need the following dependencies:

Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
It is recommended to set up a virtual environment and install the dependencies within the environment to avoid conflicts with other Python projects.

STEPS:
1. Import Libraries
2. Read Data
3. Getting Dataframe Information
4. To find numeric and non numerical cols
5. Filling Missing Values
6. Using cat cols feature encoding
7. Feature reduction on corr
8. Finding X and Y Column
9. Model Building

Code Structure
The repository is structured as follows:

data/: Contains the CSV files train.csv and test.csv that contain the training and testing data, respectively.
notebooks/: Contains Jupyter Notebook files with the code for data exploration, preprocessing, feature engineering, model training, and evaluation.
models/: Contains the trained machine learning models saved as serialized files.
utils/: Contains utility functions used in the notebooks.
README.md: This file, providing an overview of the project.

Usage
To run this project, follow these steps:

Clone this repository to your local machine.
Install the required dependencies mentioned above.
Open the Jupyter Notebook files in the notebooks/ directory.
Execute the cells in the notebooks in sequential order to explore the data, preprocess it, engineer new features, train the model, and evaluate its performance.
The trained models will be saved in the models/ directory.
Use the trained model to make predictions on new data by running the appropriate code.

Resources
Here are some resources that can help you understand the problem and the techniques used in this project:

Kaggle competition: Titanic: Machine Learning from Disaster
Scikit-learn documentation: Scikit-learn User Guide
Seaborn documentation: Seaborn API reference