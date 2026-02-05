# Processed Data

This folder contains the cleaned, reconstructed, and analytically processed datasets used in *The Titanic, Retold in 20 Lifeboats*.

The datasets are the result of a six-month manual research and data-cleaning process that combined structured passenger data with historical sources, survivor accounts, and cross-referencing across lifeboat records.

Rather than treating the Titanic dataset as a static table, the data was reshaped to support **lifeboat-level analysis** and exploratory historical inquiry.

---

## Overview of Datasets

### Excel Full Workspace (Processed)
The cleaned passenger dataset consolidates demographic, class, and survival information into a consistent, analysis-ready format.

Key characteristics:
- Standardised passenger names and identifiers
- Harmonised class, gender, and age fields
- Modernised country references for readability
- Survival status verified and cross-checked
- Removal of duplicate or contradictory records where possible

This dataset serves as the analytical backbone for all subsequent lifeboat-level breakdowns.

---

### Lifeboat Lists
Each lifeboat has been reconstructed as its own dataset.

For every lifeboat (1–16 and Collapsible A–D), the following was documented where possible:
- Passenger identities
- Gender, age, class, and role (passenger vs. crew)
- Boat capacity vs. actual occupancy
- Launch order and rescue context
- Notes on transfers, rescues, swimmers, or uncertainty

Lifeboats are treated as **units of analysis**, reflecting how survival decisions were made locally and under extreme conditions.

---

## Methodological Notes

- Data cleaning was performed manually using spreadsheets to allow close inspection of individual records.
- Passenger-level decisions (e.g. classification, assignment, exclusion) were documented throughout the process.
- Manual counting and aggregation were used deliberately to surface inconsistencies, patterns, and anomalies.
- Data entry itself became an analytical act, shaping the research questions as patterns emerged.

This approach mirrors historical and archival research practices, prioritising transparency and interpretability over automation.

---

## Analytical Intent

The processed datasets are structured to support:
- Lifeboat-by-lifeboat comparisons
- Survival patterns across class, gender, age, and role
- Examination of evacuation order and capacity utilisation
- Exploration of social and logistical dynamics during the disaster

Rather than optimising for predictive modelling, the data is designed for **exploratory analysis and narrative reconstruction**.

---

## Limitations

- Historical sources frequently contradict one another.
- Survivor testimonies are incomplete, biased, or inconsistent.
- Some passenger details remain unverifiable despite extensive cross-checking.

These limitations are documented rather than concealed and should be considered part of the dataset’s historical context.

---

## File Structure

- Individual CSV files per lifeboat
- Full workspace including original kaggle passenger datasets
- Supporting tables for analysis and visualisation

All datasets in this folder represent *processed outputs* and are intended for reuse, inspection, or extension in other analytical environments.

