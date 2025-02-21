# **Wine Quality Prediction Project**

**Objective :**

The objective of this project is to predict the quality of red wine using machine learning techniques based on its physicochemical properties.

**Dataset :**

The dataset used for this project is the "Red Wine Quality" dataset from the UCI Machine Learning Repository. It contains 1,599 instances of red wine with 11 physicochemical features and a quality score ranging from 0 to 10.

Link to dataset : https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?select=winequality-red.csv

**Overview of the Process :**

1. Importing Dependencies

 * The necessary libraries are imported:

2. Data Collection

 * The dataset is loaded into a Pandas DataFrame.
 * Basic exploration is done to understand the structure and contents of the dataset.

3. Data Analysis and Visualization
  * Summary statistics and data types are checked using describe and info methods.
 * Visualizations are created using seaborn to analyze the relationship between some features and quality and a heatmap showing correlations between features.

4. Data Preprocessing
 * The dataset is separated into features (X) and labels (Y).
 * Label binarization is applied to the wine quality scores to create a binary classification problem. Quality scores >= 7 are labeled as 1 (Good quality wine), and scores < 7 are labeled as 0 (Bad quality wine).

5. Model Training

 * The dataset is split into training and test sets.
 *  RandomForestClassifier is instantiated and trained on the training data.

6. Model Evaluation

 * The trained model is used to make predictions on the test set.

7. Building a Predictive System
 * function predict_wine_quality is created to predict wine quality based on new input data.
