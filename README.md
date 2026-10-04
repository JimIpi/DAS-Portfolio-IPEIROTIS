# Understanding Diabetes Progression: A Data Analytics Portfolio

## Project Overview
This repository contains a complete data analysis workflow investigating a health dataset of 442 patients[cite: 4]. The objective is to identify which clinical characteristics—such as Body Mass Index (BMI), blood pressure, and specific serum measurements—are most strongly associated with the progression of diabetes one year after the baseline measurements[cite: 4, 8]. 

This project was completed as part of the "Data Analytics and Statistics with Applications" course.

## Repository Structure
* **`2b_Scenario1_Diabetes_Starter.R`**: The reproducible R script containing data preparation, exploratory data analysis (EDA), correlation mapping, and linear regression modelling[cite: 2, 8].
* **`Analytical_Report.pdf`**: A detailed report answering the core research questions, evaluating model uncertainty, and discussing the limitations (confounding variables, non-causal nature) of the observational data[cite: 2, 6].
* **`Presentation.pptx`**: A concise, non-technical presentation designed for healthcare decision-makers, summarizing the key predictive findings and their practical implications[cite: 2, 6].
* **`diabetes.tab.txt`**: The original dataset used for the analysis[cite: 4, 9].

## Key Findings
* The blood serum measurement **s5** emerged as the strongest predictive indicator for rapid diabetes progression.
* **BMI** and **Blood Pressure** also demonstrated significant positive associations with the outcome.
* A multiple regression model utilizing these three variables successfully explains 48% of the variance in disease progression, free from multicollinearity issues.
* Because the dataset is strictly observational, these findings highlight predictive risk factors rather than causal mechanisms.

## Tools & Libraries
* **Language:** R
* **Core Packages:** `ggplot2` (data visualization), `dplyr` (data manipulation), `broom` (tidying statistical model outputs)
