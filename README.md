# PREDECTING-EMPLOYMENT-STATUS-IN-INDIA-A-MACHINE-LEARNING-APPROACH
This repository contains a machine learning project aimed at predicting employment status in India using data from the Periodic Labour Force Survey (PLFS) for the year 2023–2024.

📌 Project Overview

In a developing country like India, employment plays a crucial role in socio-economic development. This project leverages machine learning models to classify individuals as Employed or Non-Employed based on socio-demographic and economic variables.

📊 Dataset

Source: Periodic Labour Force Survey (PLFS), Ministry of Statistics and Programme Implementation (MoSPI)

Observations: 418,159

Variables: 139 (e.g., Age, Gender, Education, Sector, Region)

Target Variable: Employment status (Employed, Non_Employed)


🔧 Data Processing

Missing values analysis and handling

Categorical transformation of employment codes

Standardization of continuous features

Train-test split (80:20) with reproducibility


📈 Exploratory Data Analysis (EDA)

Key EDA insights include:

Significant class imbalance: more individuals are Employed than Non-Employed

Employment rates vary significantly across age groups, gender, education levels, sectors, and states

Gender gap: ~53% of females are non-employed vs ~20% of males

State-level and sectoral disparities exist


🤖 Machine Learning Models Used

1. Logistic Regression

Highest recall (97%) for Non-Employed individuals

Precision for Non-Employed: 85%

Best overall performing model



2. Random Forest Classifier

High accuracy but prone to overfitting



3. Decision Tree Classifier

Simple and interpretable, but lower recall (71%) for Non-Employed



4. Pipeline with Decision Tree

Structured preprocessing + controlled complexity




🏁 Results

Best Model: Logistic Regression

Why? High performance in identifying Non-Employed individuals, making it suitable for policy applications where correct classification of vulnerable groups is crucial.


🧠 Conclusion

This study highlights the potential of ML in understanding labor market dynamics. Socio-demographic variables like age, gender, education, and region significantly influence employment status. Future work can extend this approach by:

Incorporating deep learning

Addressing class imbalance

Using additional economic indicators
