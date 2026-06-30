# PlutoAcademy-AI-ML-Internship-Program
# Netflix Movies and TV Shows Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows Dataset. The aim is to understand Netflix's content distribution, identify trends, analyze ratings, countries, directors, and visualize important insights using Python data analysis libraries.

---

## Objectives

- Explore the Netflix dataset.
- Clean and preprocess the data.
- Identify patterns and trends in Netflix content.
- Analyze content types, ratings, release years, and countries.
- Create meaningful visualizations.
- Generate insights and conclusions from the dataset.

---

## Dataset Information

The dataset contains information about Netflix Movies and TV Shows, including:

- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow

### 1. Data Collection
- Load Netflix dataset into Google Colab.

### 2. Data Inspection
- Check dataset shape.
- Review column names.
- Examine data types.
- Identify missing values.
- Detect duplicate records.

### 3. Data Cleaning
- Remove duplicate rows.
- Handle missing values.
- Prepare dataset for analysis.

### 4. Exploratory Data Analysis (EDA)
- Analyze Movies vs TV Shows.
- Identify top contributing countries.
- Examine content ratings.
- Analyze release year trends.
- Find top directors.

### 5. Data Visualization
- Bar Chart
- Line Chart
- Histogram
- Scatter Plot
- Pie Chart
- Heatmap

### 6. Insights and Conclusions
- Summarize key findings from the analysis.

---

## Key Findings

- Movies constitute the majority of Netflix content.
- The United States contributes the largest number of titles.
- Netflix content has increased significantly in recent years.
- Certain ratings dominate the platform, indicating target audience preferences.
- A small group of directors contributes multiple titles.

---

## How to Run the Project

1. Open Google Colab.
2. Upload the notebook file (`Netflix_EDA_Project.ipynb`).
3. Upload the dataset (`netflix_titles.csv`).
4. Run all cells sequentially.
5. Review outputs, visualizations, and insights.

---

## Project Structure

```
Netflix_EDA_Project/
│
├── Netflix_EDA_Project.ipynb
├── netflix_titles.csv
├── README.md
└── images/
```

---

## Conclusion

This project demonstrates the use of Exploratory Data Analysis techniques to gain insights from Netflix content data. The analysis helps understand content trends, audience focus, and growth patterns of the Netflix platform.

-----------2-----------

# Heart Disease Prediction Using Machine Learning

## Project Overview

This project develops a Machine Learning model to predict whether a patient is likely to have heart disease based on various medical attributes. The project follows a complete machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and comparison of different classification algorithms using Python and Scikit-learn.

---

## Objectives

- Load and explore the Heart Disease dataset.
- Clean and preprocess the data.
- Perform feature engineering and correlation analysis.
- Train multiple Machine Learning models.
- Compare model performance using evaluation metrics.
- Identify the best-performing model.
- Visualize feature importance and confusion matrix.
- Draw meaningful conclusions from the analysis.

---

## Dataset Information

The dataset contains medical information of patients, including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression (Oldpeak)
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Collection
- Load the Heart Disease dataset into Google Colab.

### 2. Data Inspection
- Check dataset shape.
- Review column names.
- Examine data types.
- Identify missing values.
- Detect duplicate records.

### 3. Data Preprocessing
- Remove duplicate records.
- Handle missing values.
- Standardize numerical features.
- Split the dataset into training and testing sets.

### 4. Feature Engineering
- Perform correlation analysis.
- Identify important features influencing heart disease prediction.

### 5. Machine Learning Models
Train and compare three classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

### 6. Model Evaluation
Evaluate all models using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### 7. Data Visualization
- Correlation Heatmap
- Feature Importance Chart
- Confusion Matrix

### 8. Best Model Analysis
- Compare all model performances.
- Select the best-performing model based on evaluation metrics.

---

## Key Findings

- Random Forest achieved the highest prediction accuracy among all trained models.
- Chest Pain Type, Maximum Heart Rate, and ST Depression were among the most influential features.
- Data preprocessing and feature scaling improved model performance.
- The comparison of multiple algorithms helped identify the most reliable prediction model.
- Machine Learning can effectively assist in the early prediction of heart disease.

---

## How to Run the Project

1. Open Google Colab.
2. Upload the notebook file (`Heart_Disease_Prediction.ipynb`).
3. Upload the dataset (`heart.csv`).
4. Run all cells sequentially.
5. Review the outputs, evaluation metrics, visualizations, and conclusions.

---

## Project Structure

```
Heart_Disease_Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── README.md
└── images/
```

---

## Conclusion

This project demonstrates the complete implementation of a Machine Learning classification pipeline for heart disease prediction. By comparing multiple classification algorithms, the Random Forest Classifier was identified as the best-performing model. The project highlights the importance of data preprocessing, feature engineering, and proper model evaluation in building reliable predictive healthcare applications.

---

## Author

**Surabhi**

AI & Machine Learning Internship Project

Data Analytics Internship Project
