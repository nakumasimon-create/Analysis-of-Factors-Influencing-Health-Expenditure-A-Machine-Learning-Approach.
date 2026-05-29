# Analysis-of-Factors-Influencing-Health-Expenditure-A-Machine-Learning-Approach.

**Project Overview**

This project focuses on predicting medical insurance costs using Machine Learning techniques. The notebook performs data preprocessing, exploratory data analysis (EDA), visualization, model training, and evaluation to determine the best predictive model for insurance charges.

The analysis is implemented in Python using popular data science libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

**Objectives**

Analyze medical insurance data and identify important features.

Perform exploratory data analysis and data visualization.

Preprocess categorical and numerical variables.

Train multiple machine learning models.

Compare model performance and select the best model.

Predict medical insurance charges accurately.

**Dataset Information**
The dataset contains information about individuals and their medical insurance costs.

**Features**

age – Age of the individual

sex – Gender of the individual

bmi – Body Mass Index

children – Number of children/dependents

smoker – Smoking status

region – Residential region

charges – Medical insurance cost (target variable)

Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn


**Machine Learning Models Used**

The project compares several regression algorithms, including:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Other regression models available in Scikit-learn

The best-performing model is selected based on evaluation metrics.

Project Workflow

Import Libraries

Load Dataset

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Data Visualization

Feature Engineering

Model Training

Model Evaluation

Prediction and Results

Data Visualizations


**The notebook includes several visualizations such as:**

Distribution plots

Boxplots

Correlation heatmaps

BMI category analysis

Insurance charge comparisons

These visualizations help identify patterns and relationships within the dataset.

**Model Evaluation Metrics**

The models are evaluated using regression metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score


**Installation and Setup**

**Clone the Repository**

git clone <repository-link>
cd medical-insurance-prediction


**Install Required Libraries**

pip install pandas numpy matplotlib seaborn scikit-learn

Run the Notebook

jupyter notebook

**Open the notebook file:**

medical-insurance-cost-prediction-analysis.ipynb


**Example Usage**

Run all notebook cells sequentially to:

Explore the dataset

Train machine learning models

Evaluate prediction performance

Generate insurance cost predictions


**Results**

The Random Forest Regressor achieved strong predictive performance compared to other models tested in the project.

Future Improvements

Hyperparameter tuning

Deployment using Flask or Streamlit

Integration with real-time prediction systems

Use of advanced ensemble methods


**Author**

Prepared as part of a Machine Learning and Data Analysis project.

**License**

This project is intended for educational and research purposes.

