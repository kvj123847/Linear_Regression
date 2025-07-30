ML Concepts - Linear and Multivariate Regression
This project demonstrates basic machine learning concepts using Python and Scikit-learn. The primary focus is on linear regression and multivariate regression with real-world datasets such as housing prices, per capita income, and salaries based on experience and test scores.

Files
ml_concepts.py: Core Python script containing code for data loading, preprocessing, training regression models, and visualizing predictions.



Concepts Covered
Simple Linear Regression

Predicting house prices based on area.

Predicting per capita income over the years.

Multivariate Linear Regression

Predicting house prices based on area, number of bedrooms, and age.

Predicting salaries based on experience, test scores, and interview performance.

Data Preprocessing

Handling missing values using median imputation.

Feature selection and transformation.

Visualization

Scatter plots and regression lines using Matplotlib and Seaborn.

Requirements
Make sure you have the following Python libraries installed:

bash
Copy
Edit
pip install numpy pandas matplotlib seaborn scikit-learn
Datasets Used
These CSV files are expected to be present in your working directory or Google Colab environment:

hr_data.csv: Contains area and price for houses.

ml.csv: Contains area values for predictions.

canada_per_capita_income.csv: Contains yearly per capita income.

price.csv: Contains area, bedrooms, age, and price for houses.

experience.csv: Contains experience, test_score(interview_score), interview_score(out of 10), and salary($).

Update the file paths if you're running this script outside Google Colab.





How to Run
Ensure all required CSV files are available in the runtime environment.

Execute ml_concepts.py step-by-step, or run the equivalent notebook if using Jupyter or Colab.

Check the output for model training results, predictions, and visualizations.




Example Use Cases
Estimating house prices using area and other features.

Forecasting future per capita income trends.

Predicting employee salaries based on test scores and experience.



Notes
Always preprocess data (such as handling NaN values) before fitting a model.

Output includes both numerical predictions and visual plots.
