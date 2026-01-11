# **COVID-19 Clinical Trials - Exploratory Data Analysis (EDA)**

## **Table of Contents**
- [Introduction of COVID-19 Clinical Trials](#introduction)
- [About the Dataset](#about-the-dataset--covid-19-clinical-trials)
- [Python libraries used](#libraries-used)
- [Project Work flow](#project-workflow)
- [Purpose of the analysis](#purpose-of-the-analysis)
- [Key Insights](#key-insights)

## **Introduction**
The COVID-19 pandemic triggered one of the largest and fastest global research responses in modern history.
Thousands of clinical trials were launched worldwide to evaluate vaccines, treatments, diagnostics, and public health strategies.

This project performs a comprehensive Exploratory Data Analysis (EDA) on COVID-19 clinical trial data sourced from ClinicalTrials.gov, with the goal of understanding:
* How trials were structured and conducted

* Who they targeted (demographics)

* Where research efforts were concentrated geographically

* How trial activity evolved over time

The analysis focuses on clarity, interpretability, and meaningful insights, without using advanced machine learning techniques.

## **About the Dataset – COVID-19 Clinical Trials**
**Source:** ClinicalTrials.gov
**Type:** Public healthcare research data

### Dataset Information
* Number of instances: 5,783 clinical trials

* Number of attributes: 27 columns

* Data types: Categorical, numerical, and datetime features

* Time range: Primarily 2019–2021

### Key Features Include:
* Trial status and phase

* Study type and design

* Participant demographics (age, gender)

* Enrollment size

* Study locations

* Trial start and completion dates

This dataset enables the analysis of global clinical research trends during the COVID-19 pandemic.

## **Libraries Used:**
The following Python libraries were used to complete this EDA:
* Pandas

* NumPy

* Matplotlib

* Seaborn

## **Project Workflow**
1. Importing required libraries

2. Loading and inspecting the dataset

3. Missing value analysis and cleaning

4. Feature engineering:
   *  Country extraction from locations
   *  Trial duration calculation
   *  Simplification of trial phases and study types

5. Univariate analysis:
   *  Status, phase, age group, gender, study type

6. Bivariate analysis:
   *  Status vs phases
   *  Country-wise trial distribution
   *  Enrollment size by study type

7. Time-series analysis:
   *  Monthly trend of trial start dates

8. Final insights and conclusion

## **Purpose of the Analysis**
The purpose of this analysis is to:
* Understand how clinical research scaled during a global emergency

* Identify dominant trial designs and participant groups

* Analyze geographic leadership in COVID-19 research

* Observe how research activity evolved over time

* Highlight limitations such as missing metadata in real-world datasets
This project is designed to be educational, well-documented, and aligned with intermediate-level data analysis standards.

## **Key Insights**
* Interventional trials dominated COVID-19 research, reflecting the urgency to test treatments and vaccines.

* A large portion of trials lacked clearly defined phases, suggesting rapid or emergency-driven study initiation.

* Most studies targeted Adults and Older Adults, with minimal pediatric inclusion.

* The United States led global trial activity, followed by several European countries.

* Trial registrations peaked sharply in April–May 2020, then gradually declined through 2021.

* Observational studies generally had larger enrollment sizes compared to interventional trials.

### **[Main EDA Notebook](https://github.com/Kaifzen/covid19-clinical-trials-EDA/blob/main/maincode.ipynb)**
