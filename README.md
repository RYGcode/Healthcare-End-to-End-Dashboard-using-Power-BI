# Healthcare-End-to-End-Dashboard-using-Power-BI

## Table of Contents
- [Data Overview](#overview)
- [Project Structure](#project-structure)
- [Screenshots](#Screenshots)

## Data Overview
The healthcare dataset comprises information related to inpatient and outpatient services, offering insights into medical specialties, patient demographics, and temporal patterns. The dataset is structured with the following key variables:
1. Archive_Date: The date of record archival, providing a temporal dimension to the data.
2. Specialty_HIPE: Code representing the medical specialty according to the Hospital International Patient Evaluation (HIPE) classification.
3. Speciality: Descriptive names of medical specialties corresponding to the HIPE codes.
4. Adult_Child: Categorization of patients into adult or child groups, aiding in demographic analysis.
5. Age_Profile: Further granularity in patient demographics, categorizing age groups.
6. Time_Bands: Temporal segmentation of services, facilitating the analysis of peak times or specific temporal patterns.
7. Total: The total count or volume of services.

## Project Structure
- `dashboard/`: This directory contains dashboard.py which is used to create dashboards of data analysis results.
- `datasets/`: Contains raw CSV data for data analysis.
- `README.md`: This documentation file.

## Screenshots

<img width="937" alt="Summary Page" src="Photos/Summary Screenshot.png">

<img width="935" alt="Detailed Page" src="Photos/Detailed Screenshot.png">

<img width="934" alt="Detailed" src="Photos/Drill Down Screenshot.png">
