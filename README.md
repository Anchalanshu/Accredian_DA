# Instructor Effectiveness Analysis

## Project Overview
This project analyzes instructor effectiveness using course engagement and performance metrics.  
The goal is to identify factors that influence course completion rates and build a machine learning model to predict student course completion.

The analysis includes exploratory data analysis, feature engineering, and predictive modeling using Python.



## Dataset Description
The dataset contains information about course batches, instructors, and student engagement metrics.

Key features include:

- batch_id – Unique identifier for each course batch
- instructor_id – Unique identifier for instructors
- course_id – Unique identifier for courses
- completion_rate – Percentage of students who completed the course
- avg_score_improvement – Average improvement in student scores
- avg_quiz_score – Average quiz performance
- dropout_rate – Percentage of students who dropped out
- avg_watch_time – Average time spent watching course content
- assignment_submission_rate – Assignment completion percentage
- forum_activity_rate – Student participation in discussions
- avg_feedback_score – Average student feedback rating

Dataset Size: **2000 rows**



## Project Workflow

### 1 Data Loading
Dataset loaded using Pandas.

### 2 Data Cleaning
Checked for missing values and ensured data consistency.

### 3 Exploratory Data Analysis
Visualized distributions and relationships between variables using:
- Histograms
- Scatter plots
- Correlation heatmap

### 4 Feature Engineering
Prepared relevant features for model training.

### 5 Model Building
Used **Random Forest Regressor** to predict course completion rate.

### 6 Model Evaluation
Model performance evaluated using:
- Mean Squared Error (MSE)
- R² Score

### 7 Business Insights
Key factors influencing completion rate were identified through correlation and model results.



## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab



## Key Insights

- Dropout rate has a strong negative correlation with course completion.
- Higher quiz scores and score improvement positively influence completion rates.
- Instructor engagement metrics contribute to better student performance.



## How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook
2. Install required libraries
3. Run all cells sequentially

