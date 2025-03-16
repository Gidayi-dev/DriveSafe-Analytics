# Accident Data Analysis

## Project Overview
This project performs an **exploratory data analysis (EDA)** and **predictive modeling** on accident data using **Pandas, Seaborn, Matplotlib, and Scikit-Learn**. The dataset contains accident-related features such as age, gender, speed of impact, helmet usage, seatbelt usage, and survival status.

## Features and Objectives
- **Data Cleaning & Preprocessing:**
  - Handling missing values
  - Encoding categorical variables (Gender, Helmet_Used, Seatbelt_Used)
- **Exploratory Data Analysis (EDA):**
  - Generating summary statistics
  - Visualizing correlations between features
  - Analyzing the relationship between survival and various factors
- **Predictive Modeling:**
  - Training a **Logistic Regression model** to predict survival
  - Evaluating model performance using accuracy and classification report

## Technologies Used
- **Python**
- **Pandas** (Data cleaning and manipulation)
- **Seaborn & Matplotlib** (Data visualization)
- **Scikit-Learn** (Machine learning modeling)

## Installation
Ensure you have Python installed, then install the required libraries using:
```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Dataset
The dataset (`accident.csv`) contains the following key columns:
- `Age`: Age of the person involved in the accident
- `Gender`: Male (0) or Female (1)
- `Speed_of_Impact`: Impact speed of the accident
- `Helmet_Used`: Whether a helmet was used (1 = Yes, 0 = No)
- `Seatbelt_Used`: Whether a seatbelt was used (1 = Yes, 0 = No)
- `Survived`: Survival status (1 = Survived, 0 = Did not survive)

## Steps in the Analysis
1. **Load the dataset**
2. **Check for missing values and clean the data**
3. **Encode categorical variables**
4. **Perform EDA & Visualizations**
5. **Train a Logistic Regression model**
6. **Evaluate model accuracy**

## Running the Project
To execute the analysis, run:
```bash
python accident.py
```
Ensure the dataset (`accident.csv`) is present in the working directory.

## Results
- **Feature Correlation Heatmap:** Shows relationships between accident factors.
- **Survival Rate Analysis:** Survival trends based on age and helmet usage.
- **Model Performance:** Outputs accuracy score and classification report.

## Contact
For queries, reach out via email millyannahi@gmail.com.

