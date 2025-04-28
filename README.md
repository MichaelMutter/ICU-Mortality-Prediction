# ICU Mortality Prediction: Machine Learning Application in Medicine

![ICU Image](https://upload.wikimedia.org/wikipedia/commons/6/65/Intensive_care_unit_%28ICU%29.jpg)

## Project Overview
In this project, we explored clinical predictors of **mortality in Intensive Care Unit (ICU) patients** using real-world medical data from the **MIMIC-III** database.  
The analysis focused on two main clinical variables:
- The presence of **Chronic Obstructive Pulmonary Disease (COPD)**.
- **Potassium levels** throughout the ICU stay.

Our goal was to determine whether these factors are significantly associated with ICU mortality and could serve as early indicators for clinical decision-making.

## Key Steps:
- **Data Processing:** Merging multiple clinical tables (patients, admissions, diagnoses, lab results) and engineering new features such as potassium statistics (mean, median, first, last, max).
- **Exploratory Data Analysis (EDA):** Using visualizations (boxplots, histograms, density plots) to understand distributions and detect outliers.
- **Statistical Testing:** Performing Chi-square tests, Mann-Whitney U tests, and normality checks (Shapiro-Wilk test) to validate associations.
- **Findings:**  
  - **Higher maximum and last potassium levels** were significantly correlated with mortality.
  - **An upward trend in potassium levels** during ICU stay was strongly associated with higher death rates.
  - No statistically significant relationship was found between gender, ethnicity, or COPD diagnosis alone and mortality.

## Project Files:
- 📓 `Assignment 1 on Machine Learning Applications in Medicine.ipynb`: Full Jupyter Notebook analysis.
- 📑 `death_during_ICU.csv`: Processed dataset.
- 📊 `Presentation 1 on Machine Learning Applications in Medicine.pdf`: Executive summary presentation.
