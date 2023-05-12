This project aims to predict whether a person is an adult or not using machine learning algorithms.

Dataset
The dataset used for this project is the Adult Income dataset from the UCI Machine Learning Repository. The dataset contains information about individuals such as age, education, marital status, occupation, and income level.

Preprocessing
The following preprocessing steps were applied to the dataset before training the machine learning model:

Missing values were replaced with the mode for categorical features and the median for numerical features.
Categorical features were one-hot encoded.
Numerical features were normalized using MinMaxScaler.

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

Model
The model used for this project is a Random Forest Classifier from the scikit-learn library. The model was trained on 80% of the dataset and evaluated on the remaining 20%.

The model achieved an accuracy of 85% on the test set.

Conclusion
In conclusion, this project demonstrates the use of machine learning algorithms for predicting whether a person is an adult or not. The model achieved an accuracy of 85% on the test set, which is a reasonable performance given the complexity of the problem. The model can be further improved by using more advanced techniques such as feature engineering and hyperparameter tuning.