🏡 House Sales Price Prediction – King County, USA

This project was completed as part of the IBM Data Science Professional Certificate on Coursera, specifically under the course Data Analysis with Python. The goal of this project is to explore and evaluate regression models to predict house prices based on various features in the dataset.

📁 Dataset
File: kc_house_data.csv
Description: Real-world housing data from King County, USA (Seattle region), including features such as number of bedrooms, bathrooms, square footage, number of floors, and more.
🎯 Objectives
Load and preprocess the dataset using Pandas and NumPy.
Perform exploratory data analysis (EDA):
Use .describe() to summarize numerical features.
Use .value_counts().to_frame() to analyze categorical features such as floor count.
Train a Ridge Regression model on the original data.
Apply a second-order Polynomial Transformation, then fit a Ridge Regression model with alpha=0.1.
Compare model performances using the R² score.
📊 Results
R² Score (Linear Ridge Regression): ~0.648
R² Score (Polynomial Ridge Regression): ~0.700
🛠️ Tools & Libraries
Python
Pandas
NumPy
Scikit-learn
Google Colab
