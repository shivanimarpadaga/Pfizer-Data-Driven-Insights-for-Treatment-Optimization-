# Pfizer’s Personalized Medicine Initiative

## Overview
This repository is dedicated to the in-depth analysis of Pfizer's Personalized Medicine initiative, focusing on clinical trial and genomics data. Pfizer, a global leader in the pharmaceutical industry, leverages vast data sets to tailor drug development and optimize patient treatment outcomes. This project aims to uncover actionable insights from clinical data that inform decision-making and enhance patient-specific treatment plans.

## Project Goals
- **Analyze clinical and genomic data** to identify factors influencing drug efficacy.
- **Detect demographic and genetic patterns** impacting patient responses and adverse side effects.
- **Optimize treatment strategies** by correlating trial outcomes with key patient variables.

## Dataset Details
The dataset used for this analysis is titled **Pfizer’s Personalized Medicine.csv**. It contains comprehensive information on patient demographics, medical history, clinical trial data, and genomic profiles.

### Key Columns in the Dataset:
- **Patient_ID**: Unique identifier for each patient.
- **Age**: Age of the patient.
- **Gender**: Gender of the patient (Male/Female/Other).
- **Ethnicity**: Ethnicity of the patient.
- **Medical_History**: Notable medical conditions (e.g., Diabetes, Hypertension).
- **Genomic_Profile**: Overview of patient’s genomic mutations.
- **Drug_Name**: Drug administered.
- **Trial_Phase**: Phase of the clinical trial (I-IV).
- **Dose_Administered**: Actual dose given (in mg).
- **Treatment_Outcome**: Outcome of the treatment (Improved/No Change/Deteriorated).
- **Efficacy_Score**: Score indicating treatment effectiveness.
- **Survival_Rate**: Post-treatment survival duration (in months).
- **Progression_Free_Survival**: Time without disease progression post-treatment (in months).

## Methodology
### Data Preprocessing & Cleaning
- **Handling Missing Data**: Imputation or removal of rows with critical missing values.
- **Consistency Checks**: Validating dose adherence to trial protocols and identifying outliers.
- **Categorical Encoding**: Proper labeling for fields such as Gender, Ethnicity, and Genomic_Profile.
- **Date Validation**: Ensuring correct formatting and logical sequencing of Start_Date and End_Date.
- **Duplicate Check**: Ensuring unique patient and trial records.

### Exploratory Data Analysis (EDA)
#### Basic Analyses:
1. **Patient Distribution by Age Group**: Identifies age demographics involved in trials.
2. **Drug Distribution by Trial Phase**: Highlights drug progression across trial phases.
3. **Side Effects Analysis**: Identifies drugs associated with the highest reported side effects.
4. **Average Dose Analysis**: Determines standard dosing practices across different drugs.
5. **Efficacy Score by Drug and Age Group**: Reveals age-based efficacy variations.
6. **Mutation Status and Progression-Free Survival**: Examines genetic impacts on survival rates.

#### Visualizations:
- **Histograms** for age distribution.
- **Pie charts** for gender breakdown.
- **Stacked bar charts** for drug distribution by trial phase.
- **Line charts** for survival rates by drug.
- **Scatter plots** for dose correlation with treatment success.

## Key Findings & Business Impact
- **Personalized Treatment Insights**: Identifying which drugs are most effective for specific demographics and genetic profiles.
- **Safety & Adverse Event Management**: Highlighting side effect patterns to refine dosage and enhance patient safety.
- **Optimized Clinical Trial Design**: Allocating resources effectively based on trial phase success rates.
- **Inclusivity & Diversity**: Ensuring representation of diverse populations in trials for broader applicability.

## Tools & Technologies Used
- **Excel and Pivot Table**: Data cleaning, basic analysis, and visualization.
- **Power BI**: Advanced data visualization to create interactive dashboards.

#
