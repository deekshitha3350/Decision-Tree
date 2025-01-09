# Decision-Tree

Decision Tree Analysis for Heart Disease Dataset
Objective
The goal of this project is to perform exploratory data analysis (EDA) on a heart disease dataset and prepare it for Decision Tree Classification.

Tasks Covered in the Code
1. Data Loading
Load the dataset heart_disease.xlsx into the Python environment using Pandas.
2. Data Inspection
Display the first few rows of the dataset using .head().
Use .info() to understand the structure of the dataset, including column types and non-null counts.
Check for missing values with .isnull().sum().
3. Exploratory Data Analysis (EDA)
Box Plots: Identify outliers in numerical features using box plots.
Histograms: Analyze the distribution of numerical features with histograms and KDE plots.
Correlation Matrix: Generate and visualize a correlation matrix to understand relationships between numerical features using a heatmap.
4. Handling Edge Cases
Ensure the correlation matrix is valid by handling cases where numerical data might be missing or invalid (e.g., all NaN values).
Requirements
Python 3.x
Libraries:
pandas
numpy
matplotlib
seaborn
How to Run
Place the heart_disease.xlsx file in the same directory as the script.
Install the required libraries using:
bash
Copy code
pip install pandas numpy matplotlib seaborn
Run the script to perform EDA and generate visualizations.
Output
Data Overview: Insights into the structure and completeness of the dataset.
Box Plots and Histograms: Visual representations of data distributions and outliers.
Correlation Heatmap: A heatmap showing relationships between numerical features.
Future Work
Perform feature engineering based on EDA results.
Train and evaluate a Decision Tree Classification model on the dataset.
Optimize the model through hyperparameter tuning.
