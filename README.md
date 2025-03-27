# Homicide Data Analysis Project (2019–2023)

This repository contains a comprehensive analysis of homicide data obtained from the FBI. The project explores trends in homicide victim demographics, weapon usage, murder circumstances, and justifiable homicides. The analysis was performed using Python (in Google Colab) for data cleaning and exploratory analysis, and Tableau for interactive visualizations.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Repository Structure](#repository-structure)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Usage](#usage)
- [Future Work](#future-work)
- [License](#license)

---

## Project Overview

Homicide statistics provide critical insights into public safety and social trends. This project analyzes FBI homicide data for the years 2019 through 2023 to:
- Examine demographic disparities among homicide victims.
- Identify trends in weapon usage and murder circumstances.
- Explore justifiable homicides by both law enforcement and private citizens.
- Develop interactive visualizations to communicate findings clearly.

The analysis combines Python-driven data cleaning and exploratory data analysis with Tableau dashboards for polished, interactive presentations.

## Viewing the Tableau Dashboards

- **Interactive Dashboard:**  
  View the interactive version of my homicide data analysis by visiting:  
  [Tableau Dashboard] https://public.tableau.com/views/FBIHomicide2019-2023/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
---

## Data Sources

- **FBI Expanded Homicide Data:**  
  Data obtained from the FBI's publicly available datasets, which include detailed information on homicide incidents, victim demographics, weapon types, and circumstances.
  
- **FBI Crime Data Explorer:**  
  Additional contextual data and methodological notes available on the [FBI Crime Data Explorer](https://crime-data-explorer.fr.cloud.gov/).

---

## Repository Structure

```bash
.
├── notebooks
│   └── FBI_Homicide_Data_analysis_ipynd.ipynb    # Jupyter/Colab notebook containing data cleaning and analysis
├── cleaned_data
│   ├── Cleaned_Table_1.csv                       # Victims by Race, Ethnicity, and Sex
│   ├── Cleaned_Table_2.csv                       # Victims by Age, Sex, Race, and Ethnicity
│   ├── Cleaned_Table_8.csv                       # Murder Victims by Weapon
│   ├── Cleaned_Table_9.csv                       # Murder Victims by Age by Weapon
│   ├── Cleaned_Table_10.csv                      # Murder Circumstances by Relationship
│   ├── Cleaned_Table_11.csv                      # Murder Circumstances by Weapon
│   ├── Cleaned_Table_12.csv                      # Murder Circumstances Over Time
│   ├── Cleaned_Table_13.csv                      # Murder Circumstances by Sex of Victim
│   ├── Cleaned_Table_14.csv                      # Justifiable Homicide by Weapon (Law Enforcement)
│   └── Cleaned_Table_15.csv                      # Justifiable Homicide by Weapon (Private Citizen)
├── dashboards
│   ├── Tableau_Dashboard.pdf                     # PDF export of your Tableau dashboard
│   └── Tableau_Dashboard_URL.txt                 # A text file with the published dashboard link
├── README.md                                     # This file
