# gci-world-data-science
Assignments and Machine Learning competition notebooks from GCI World course - Matsuo Lab, The University of Tokyo.

# GCI World: Global Consumer Intelligence & Machine Learning
This repository contains my comprehensive coursework, practical assignments, and competitive machine learning models developed during the **GCI World 2026** program, organized by the prestigious **Matsuo-Iwasawa Laboratory at The University of Tokyo**.

## Course Overview
Primarily designed for university-level students, the program bridges theoretical mathematical statistics with intensive hands-on programming to solve commercial and consumer behavior problems. While open to ambitious high school students, the fast-paced curriculum and technical depth present a steep learning curve. Key learning domains include high-performance data manipulation, exploratory data analysis (EDA), and building scalable machine learning pipelines.

## Skills and Tools Developed
- **Data Manipulation:** Leveraged `NumPy` for vectorized matrix operations and `Pandas` for structural data wrangling, missing value imputation, and feature creation.
- **Exploratory Data Analysis (EDA):** Built advanced visualization dashboards using `Matplotlib` and `Seaborn` to detect statistical outliers, correlation matrices, and distribution anomalies.
- **Machine Learning Pipelines:** Implemented baseline to advanced models via `Scikit-Learn`, incorporating cross-validation, feature scaling, and ensemble methods.

## Repository Structure
- `/Assignments`: Structured notebooks covering data transformation and mathematical foundations.
- `/Competition`: My optimized end-to-end Machine Learning model designed for the in-class Kaggle-style data competition.

## In-Class Machine Learning Competition
- **Task:** build a classification model that predicts whether an athlete will be selected in the National Football League (NFL) Draft ("Drafted" vs. "Not Drafted") using data such as physical performance test results and position information.
- **My Approach:**
  1. *Feature Engineering:* Generated target-encoded variables and extracted temporal features from raw timestamps.
  2. *Model Evaluation:* Evaluated multiple architectures including Random Forests and Gradient Boosting.
  3. *Optimization:* Utilized Grid Search for rigorous hyperparameter tuning to prevent overfitting.
- - **Result:** Ranked in the Top 20% of the global cohort with a **0.8383 / 1.00** ROC-AUC score.
