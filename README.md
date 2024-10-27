# Statistical Analysis of Blood Pressure in Diabetic and Non-diabetic Females

## Project Overview
This project aims to investigate whether there is a significant difference in blood pressure between diabetic and non-diabetic females. Using hypothesis testing and confidence interval estimation, the analysis compares the mean blood pressure of the two groups to draw statistical conclusions.

## Group Members
- Tianyu Duan
- Cheryl Hu
- Manya Jain
- Mayank Verma

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/whenamancodes/predict-diabities). It contains health-related variables, including blood pressure, diabetes status, and other attributes of female patients of Pima Indian heritage, aged 21 or older.

### Key Attributes:
- **Pregnancies**: Number of pregnancies
- **Glucose**: Glucose level in blood
- **BloodPressure**: Blood pressure measurement
- **SkinThickness**: Thickness of the skin
- **Insulin**: Insulin level in blood
- **BMI**: Body Mass Index
- **DiabetesPedigreeFunction**: Family history of diabetes
- **Age**: Age of the patient
- **Outcome**: Whether the patient has diabetes (1) or not (0)

## Methodology
1. **Data Cleaning**: Filtered out irrelevant data and focused on blood pressure and diabetes status.
2. **Descriptive Analysis**: Computed mean and standard deviation of blood pressure for diabetic and non-diabetic females.
3. **Hypothesis Testing**:
   - Formulated null and alternative hypotheses.
   - Performed hypothesis testing using both bootstrap and asymptotic methods.
4. **Confidence Interval Calculation**:
   - Estimated 95% confidence intervals using bootstrap sampling and asymptotic methods.
5. **Results Comparison**: Compared the outcomes from both methods to evaluate consistency and accuracy.

## Results
- The analysis showed a significant difference in mean blood pressure between diabetic and non-diabetic females.
- Both bootstrap and asymptotic methods produced consistent results, confirming the hypothesis that diabetic females have higher average blood pressure.

## Technologies Used
- **R** for statistical analysis and data visualization
- Libraries: `tidyverse`, `broom`, `infer`, `ggplot2`
