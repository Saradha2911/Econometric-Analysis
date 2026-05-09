# Cardio-Hepatic Determinants Analysis

An econometric study investigating the socio-demographic and lifestyle drivers of Cardiovascular Disease (CVD) and Chronic Liver Conditions using NHANES data.

## 📌 Project Overview
This analysis explores the "cardiohepatic" relationship—the clinical overlap between heart and liver dysfunction. We model how factors like diet, alcohol, and demographics influence disease prevalence to help identify high-risk populations.

## 📊 Data Source
- **Dataset:** NHANES (National Health and Nutrition Examination Survey)
- **Timeframe:** 2017–2020
- **Scope:** Representative U.S. population data combining interviews, physical exams, and lab samples.

## 🔬 Analysis & Methodology
We employed econometric modeling using **Python (`statsmodels-0.15.0`)**:
- **CVD Models:** Logit and Probit regressions.
- **Liver Models:** Logit, Probit, and **Multinomial Logit** (consolidating specific liver types into categorical outcomes).
- **Optimization:** Addressed quasi-complete separation via variable refinement to ensure model convergence.

## 🧬 Key Variables
- **Socio-Demographics:** Age, Gender, Race/Ethnicity.
- **Lifestyle & Clinical:** BMI, Diet, Alcohol consumption, Diabetes, and Hypertension.
- **Outcomes:** Cardiovascular disease and Chronic liver conditions (NAFLD, ALD, Viral Hepatitis).
