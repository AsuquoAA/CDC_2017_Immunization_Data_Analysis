# CDC 2017 Immunization Data Analysis

## Overview

This project analyzes data from the CDC's 2017 National Immunization Survey Public Use File (NISPUF17) to answer research questions about immunization, child health, and vaccine-related behaviors. The dataset provides insights into the correlation between vaccination practices and factors like maternal education, breastfeeding, and child health outcomes.

---

## Dependencies and Installations

To use this repository and run the notebooks, you will need to have Python and the following libraries installed:
1. Pandas
2. NumPy
3. Scipy
- code: pip install numpy pandas scipy

Installations
To get started with this repository, clone it to your local machine:
- code: git clone https://github.com/AsuquoAA/CDC_2017_Immunization_Data_Analysis.git

Navigating to directory
- code: cd CDC_2017_Immunization_Data_Analysis

---

## Dataset 

The dataset used for this project is:
1. <a href="https://github.com/AsuquoAA/CDC_2017_Immunization_Data_Analysis/blob/main/NISPUF17.csv">NISPUF17.csv</a>
    Source: CDC (Centers for Disease Control and Prevention)
    Key Features:
    - EDUC1: Maternal education level.
    - CBF_01: Breastfeeding status of the child.
    - P_NUMFLU: Number of influenza vaccine doses received.
    - SEX: Sex of the child.
    - P_NUMVRC: Number of varicella (chickenpox) vaccine doses received.
    - HAD_CPOX: History of chickenpox infection.
    Additional documentation for variable mappings is provided in <a href="https://github.com/AsuquoAA/CDC_2017_Immunization_Data_Analysis/blob/main/NIS-PUF17-DUG.pdf">NISPUF17.pdf</a>.
2. <a href="https://github.com/AsuquoAA/CDC_2017_Immunization_Data_Analysis/blob/main/census.csv">Census.csv</a>
3. <a href="https://github.com/AsuquoAA/CDC_2017_Immunization_Data_Analysis/blob/main/olympics.csv">Olympics.csv</a>
   
---

## Questions 

1. Proportion of Maternal Education Levels:
- Calculate the proportion of children whose mothers had the following education levels:
  - Less than high school (<12)
  - High school (12)
  - More than high school but not college (>12)
  - College graduate

2. Relationship Between Breastfeeding and Influenza Vaccination:
- Analyze the average number of influenza vaccine doses for children who were breastfed versus those who were not.

3. Chickenpox Vaccination and Infection by Sex:
- Calculate the ratio of children who contracted chickenpox after vaccination versus those vaccinated who did not contract the disease, categorized by sex.

4. Correlation Between Chickenpox and Vaccination:
- Determine if there is a statistical correlation between having had chickenpox and the number of chickenpox vaccine doses received.

---

## Challenges Faced

1. Logical Conditions: Constructing filters for complex conditions like combining vaccination and infection statuses.
2. Statistical Analysis: Interpreting Pearson correlation and its significance.

---

## Future Enhancements
1. Add visualizations to better illustrate findings (e.g., bar charts for education levels or scatterplots for correlations).
2. Explore additional correlations (e.g., socioeconomic factors and vaccination rates).
3. Investigate temporal relationships (e.g., timing of vaccination relative to infection).

---

## Acknowledgements
I would like to thank the University of Michigan and Coursera for providing the Applied Data Science with Python Specialization, which has been an invaluable resource for learning data science with Python, where I found this exercise.
