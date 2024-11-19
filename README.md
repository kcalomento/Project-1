# Mental Well-Being in the Tech Industry

Project-1 Repository contains the **analysis, code, and visualizations** for the **Mental Health in Tech Survey (2017)**. We explore factors influencing mental well-being in the tech industry and provide actionable insights for improved workplace support. This project investigates factors influencing mental well-being within the tech industry, using statistical analysis and visualizations.

---

## Overview

- **Demographics**: The impact of age, gender, and roles on mental health.
- **Workplace Factors**: Effects of company size, work hours, remote work, and wellness programs.
- **Mental Health Outcomes**: Prevalence of anxiety, depression, and treatment-seeking behavior.

This project aims to understand the relationships between demographic factors (age, gender, role, company size), work-related factors (work hours, remote work, benefits), and mental health outcomes (anxiety, depression, treatment seeking) in the tech sector. We analyze the prevalence of mental health conditions, identify potential risk factors in the tech workplace, and assess the effectiveness of company wellness programs.

The goal is to investigate factors impacting mental well-being, with a focus on identifying patterns in mental health issues, treatment-seeking behavior, and workplace support mechanisms.

The repository analyzes data from the **Mental Health in Tech Survey**, providing insights into mental health-related issues across different demographics, roles, company sizes, and countries within the tech industry. Key findings include statistical trends in mental health treatment-seeking behavior, support programs, and work interference due to mental health. Visualizations, descriptive statistics, and predictive modeling are used to uncover correlations and trends in the data, with an aim to inform potential interventions and areas for further research.

---

## Data Source

The analysis is based on the **2017 Mental Health in Tech Survey**, available on [Kaggle](https://www.kaggle.com/osmi/mental-health-in-tech-survey).

- `mental_health_analysis.ipynb`: Jupyter Notebook containing the complete data cleaning, preprocessing, statistical analysis, and visualization code.

---

## Repository Contents

- **`ReadMe/`**: This file.
- **`glossary/`**: 
  - `Column Glossary.pdf`: – Documentation and data dictionary for the survey dataset.
- **`notebooks/`**: 
  - `OSMH_Survey.ipynb` – Jupyter Notebook with data cleaning, analysis, and visualizations.
- `**proposal/`**:
  - `Project Proposal - Mental Well-being in the Tech Industry An Exploratory Data Analysis.pdf`: Project proposal outlining the project's goals, key questions, and analysis plan.
- **`report/`**: 
  - `Mental_Health_Results.pdf` – Summary of findings and recommendations.
- **`slides/`**: 
  - `Project One UCI.pdf` – Presentation slides with key insights and visuals.
- **`proposal/`**: 
  - `Project Proposal - Mental Well-being in the Tech Industry An Exploratory Data Analysis.pdf` – Project proposal outlining goals and analysis plan.
- **`cleaned data/`**:
  - `cleaned_data_df.csv and cleaned_df.csv` –  The cleaned data which is the output of OSMH_Survey_Data_Exploration_Cleanup.ipynb.
- **`code_description/`**: 
  - `Mental Health in Tech Survey Code Description.pdf`: Detailed description of the Python code used in the analysis, including explanations of statistical concepts and techniques.
- **`slides/`**:
  - `Project One UCI.pdf`: Presentation slides highlighting the key findings and insights.  Exported visualizations and graphs used in the report.
- **`report/`**:
  - `Synopsis of Mental Heath in Tech Results.pdf`: Comprehensive report summarizing the findings, providing conclusions of the analysis, and proposing recommendations based on the analysis.

---

## Key Features

1. **Data Preprocessing**  
   - Standardization of categorical variables, handling of missing data, and filtering responses to focus on the tech industry.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizations of demographics, treatment-seeking behavior, and workplace policy impacts.

3. **Statistical Analysis**  
   - Correlation analysis, chi-squared tests, and regression modeling.

4. **Predictive Modeling**  
   - Logistic regression to predict treatment-seeking behavior based on workplace and demographic factors.

5. **Country-Specific Insights**  
   - Analysis of mental health trends across different countries.

---

## Dependencies

The analysis requires **Python 3** and the following libraries:  
- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn`, `plotly` – Visualization  
- `scikit-learn`, `statsmodels` – Statistical modeling  

---

## Usage

1. **Open the Jupyter Notebook**:  
   Navigate to the `notebooks/` folder and launch the Jupyter Notebook:
   ```bash
   cd notebooks/
   jupyter notebook OSMH_Survey.ipynb
## Review the Findings

1. **Summary Report**:  
   Navigate to `report/Mental_Health_Results.pdf` to review the full analysis and findings.

2. **Presentation Slides**:  
   Navigate to `slides/` to explore key insights and visuals.

---

## Analysis Methodology

The analysis depicts the following techniques:

1. **Descriptive Statistics and Visualization**  
   - Distributions, frequencies, means, and visualizations (histograms, pie charts, bar plots) are used to understand the data.

2. **Correlation Analysis**  
   - Relationships between variables are examined using correlation matrices and scatter plots with regression lines.

3. **Feature Engineering and Selection** 
   - Categorical features are encoded, and a chi-squared test is employed for feature selection.

4. **Predictive Modeling (Logistic Regression)**  
   - Logistic regression with L1 regularization (Lasso) is used to model the relationship between features and treatment-seeking behavior.
  
---

## Key Findings

- **Gender Disparity**: A significant gender imbalance exists in the tech industry, potentially contributing to disparities in mental health experiences.  
- **Workplace Factors**: Work interference and access to mental health benefits are significantly associated with mental health outcomes.  
- **Wellness Programs**: Effective wellness programs that address mental health show promise in improving treatment-seeking behavior.  

---

## License

This project is licensed under the **MIT License**.  
