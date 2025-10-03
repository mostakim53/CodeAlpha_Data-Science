# CodeAlpha_Data-Science
# Irish Data Analysis Project
##🌸 Iris Flower Species Classification
#Project Overview
This project is a classic machine learning endeavor focused on the Iris flower dataset, which serves as an excellent introductory case study for classification algorithms. The goal is to build a robust model capable of classifying an Iris plant into one of three species: Iris-setosa, Iris-versicolor, or Iris-virginica, based on its physical measurements.

#The project follows a standard data science workflow, including Exploratory Data Analysis (EDA), data preprocessing, model training, and performance evaluation.

#Features
The dataset contains the following features (in centimeters) for 150 Iris flowers, with 50 samples from each of the three species:

-SepalLengthCm

-SepalWidthCm

-PetalLengthCm

-PetalWidthCm

-Species (Target variable)

#Methodology and Results
1. Data Analysis and Preprocessing
The initial steps involved loading and cleaning the data:

Loaded the Iris.csv dataset.

The redundant Id column was dropped.

Data integrity checks confirmed no missing values.

Duplicate rows were checked and handled.

An EDA phase was conducted to understand the distribution of features and the strong positive correlation between PetalLengthCm and PetalWidthCm.

#2. Machine Learning Model
A Logistic Regression model was selected for the multi-class classification task. The dataset was split into training and testing sets to validate the model's performance on unseen data.

#3. Evaluation
The trained model achieved a high level of performance on the test set:

Accuracy Score: 0.93 (93%)

#The classification report indicates excellent precision and recall across all three species, demonstrating the model's capability to generalize well:
| Species | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- |
| Iris-setosa | 1.00 | 1.00 | 1.00 |
| Iris-versicolor | 0.90 | 0.90 | 0.90 |
| Iris-virginica | 0.89 | 0.89 | 0.89 |

#Technologies Used
-Python
-Jupyter Notebook
-pandas for data manipulation
-numpy for numerical operations
-seaborn and matplotlib for data visualization
-scikit-learn for machine learning (Logistic Regression)




