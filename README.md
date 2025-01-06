# Analysis of the “Adult Income Dataset”

### Authors:
- AJ Beiza
- Riley Hughes
- Tim Goncharov
- Avyay Vennam

### Affiliation:
The School of Data Science: The University of North Carolina at Charlotte  
**Course**: DTSC 1302: Data & Society  
**Instructors**: Dr. Marco Scipioni & Dr. Ilieva Ageenko  
**Date**: December 2, 2024  

---

## Introduction
This project investigates income inequality and socioeconomic mobility using the "Adult Income Dataset," a subset of the 1994 Census database. The dataset includes 48,842 records with 14 variables, encompassing demographic, occupational, and income-level details. Our analysis seeks to:

1. Develop a machine learning model to predict whether an individual earns above or below $50,000 annually.
2. Identify the most significant variables for predicting income levels.
3. Examine gender-based income disparities and potential influencing factors.

We explore these questions using statistical methods, data visualization, and machine learning, providing insights into the socioeconomic dynamics of the 1990s while addressing the dataset’s historical limitations.

---

## Context and Implications
Our findings are relevant to a wide range of stakeholders, including businesses, policymakers, educators, and the general public. Key insights include:

- The impact of marital status, education, and occupation on income levels.
- Gender-based disparities in income, influenced by systemic biases and sociocultural norms of the 1990s.
- Limitations stemming from the dataset’s historical and sampling biases.

These insights pave the way for future comparative analyses with modern datasets to understand how income dynamics have evolved.

---

## Data and Methods
### Data Overview:
- **Dataset Source**: UCI Machine Learning Repository
- **Variables**: 14 features, including age, education, marital status, occupation, and income level.
- **Target Variable**: Income (above/below $50,000 annually)

### Preprocessing:
- Handled null values (~4.9% of rows affected).
- Created a ‘net-capital’ feature by combining ‘capital-gain’ and ‘capital-loss.’
- Removed multicollinear features and irrelevant columns (e.g., ‘relationship,’ ‘fnlwgt’).

### Analysis Techniques:
1. **Machine Learning**: Random Forest classifier optimized using Grid Search, achieving 85.2% accuracy.
2. **Feature Importance**: Identified key predictors such as marital status, education, and age.
3. **Visualization**: Used histograms, bar charts, and feature importance plots to analyze trends.

---

## Key Findings
- **Model Performance**: Random Forest achieved high accuracy, with insights into feature importance.
- **Significant Predictors**: Marital status, education level, and net capital were critical in predicting income.
- **Gender Disparities**: While women earn less than men on average, disparities are partially explained by variables like hours worked, occupation, and marital status. Systemic biases likely persist.

---

## Limitations
- **Historical Bias**: Dataset reflects the socioeconomic context of the 1990s.
- **Sampling Bias**: Dataset may not fully represent the U.S. population.
- **Excluded Variables**: Missing data on geographic regions, cost of living, and taxation effects.

---

## Future Directions
Future research should focus on:
1. Incorporating modern datasets for comparative analyses.
2. Exploring other intersectionalities (e.g., race, nationality).
3. Investigating systemic income disparities in greater detail.

---

## References
For a detailed list of references, see the full project report included in this repository.

---

## Repository Structure
- **data/**: Contains cleaned dataset and preprocessing scripts.
- **notebooks/**: Jupyter notebooks for data analysis and modeling.
- **reports/**: Full project report and supplementary materials.
- **README.md**: This file.

---



