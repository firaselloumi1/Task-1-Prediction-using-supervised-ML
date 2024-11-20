# Task1:Prediction of Student Scores using Supervised Machine Learning
Author: Firas Elloumi

## Goal 🎯
The aim of this project is to predict student scores based on the number of hours they study. This is achieved using a supervised machine learning approach, specifically linear regression. 📈

## Technologies Used ⚙️
- Python Libraries:
  - 🐼 Pandas (Data manipulation)  
  - 🔢 NumPy (Mathematical operations)  
  - 📊 Matplotlib, 🌈 Seaborn (Visualization)  
  - 🤖 Scikit-learn (Machine Learning)  
## Project Workflow 📋
- Data Import & Exploration:
The dataset is fetched from a URL and loaded into a pandas DataFrame.  
We explore the data and print it to verify its structure.  
- Data Visualization:
A 2D scatter plot is generated to visualize the relationship between study hours and scores.  
- Data Preprocessing:
Correlation between the features is checked using the .corr() method.  
Data is split into inputs (study hours) and outputs (scores).  
- Model Training:
The dataset is split into training and test sets using train_test_split.  
A Linear Regression model is trained using the training data.  
- Prediction:
The model predicts scores based on the test data.  
Actual vs. predicted values are compared in a table for evaluation.  
- Evaluation:
The model is evaluated using R² and Root Mean Squared Error (RMSE) metrics.  
## Key Features 🔑:
- Visualization: A scatter plot to observe the relationship between hours studied and the scores achieved.
- Prediction: The model predicts scores for students based on their study hours.
- Model Evaluation: Performance metrics such as R² and RMSE to evaluate the model’s accuracy.

## Conclusion :
The project demonstrates the use of linear regression to predict student scores based on the number of hours studied. The model's performance can be improved further with additional features or more complex algorithms. 💡

