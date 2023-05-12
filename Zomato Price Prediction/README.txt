This project aims to predict the price range of restaurants listed on the Zomato platform using machine learning techniques. The project utilizes a dataset containing information about various restaurants, such as location, cuisine, ratings, and reviews.

Project Overview
Zomato is a popular online food delivery and restaurant discovery platform that provides information about restaurants, menus, reviews, and ratings. This project focuses on predicting the price range of restaurants listed on Zomato based on various factors. By building a machine learning model, we can estimate the price range of a restaurant before visiting it.

Dataset
The dataset used for this project is obtained from Zomato's public API and includes information about thousands of restaurants. It contains the following features:

Restaurant ID: Unique identifier for each restaurant.
Restaurant Name: Name of the restaurant.
Location: Location of the restaurant.
Cuisines: Cuisines offered by the restaurant.
Average Cost for Two: Average cost for two people to dine at the restaurant.
Currency: Currency used in the average cost.
Rating: Rating of the restaurant.
Votes: Number of votes received by the restaurant.
Reviews: Reviews of the restaurant.
Online Delivery: Indicates whether online delivery is available (Yes/No).


Zomato Price Prediction ML Project
This project aims to predict the price range of restaurants listed on the Zomato platform using machine learning techniques. The project utilizes a dataset containing information about various restaurants, such as location, cuisine, ratings, and reviews.

Table of Contents
Project Overview
Dataset
Machine Learning Model
Project Structure
Getting Started
Usage
Contributing
License
Project Overview
Zomato is a popular online food delivery and restaurant discovery platform that provides information about restaurants, menus, reviews, and ratings. This project focuses on predicting the price range of restaurants listed on Zomato based on various factors. By building a machine learning model, we can estimate the price range of a restaurant before visiting it.

Dataset
The dataset used for this project is obtained from Zomato's public API and includes information about thousands of restaurants. It contains the following features:

Restaurant ID: Unique identifier for each restaurant.
Restaurant Name: Name of the restaurant.
Location: Location of the restaurant.
Cuisines: Cuisines offered by the restaurant.
Average Cost for Two: Average cost for two people to dine at the restaurant.
Currency: Currency used in the average cost.
Rating: Rating of the restaurant.
Votes: Number of votes received by the restaurant.
Reviews: Reviews of the restaurant.
Online Delivery: Indicates whether online delivery is available (Yes/No).
Book Table: Indicates whether table booking is available (Yes/No).
Machine Learning Model
The price prediction model is built using a supervised learning approach. It employs a regression algorithm to predict the price range based on the input features. The model is trained on a labeled dataset, where the price range is considered as the target variable.

Various regression algorithms can be utilized for this task, such as linear regression, decision tree regression, random forest regression, or gradient boosting regression. The choice of algorithm can be explored and optimized based on the project requirements and performance metrics.

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
Book Table: Indicates whether table booking is available (Yes/No).