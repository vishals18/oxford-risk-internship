# Oxford Risk Internship Task – Summer 2025

## Overview

This repository contains my submission for the **Behavioural/Data Science Intern – Summer 2025** role at Oxford Risk. The goal of the task was to analyse financial asset data alongside personality traits to identify meaningful behavioural patterns using Python.

---

## Contents

- `analysis.ipynb` – Main notebook containing data extraction, transformation, EDA and visualisations
- `insights_report.docx` – Summary of insights from the analysis in a non-technical format
- `README.md` – This file

---

## Dataset Sources

1. **Personality Data (CSV from GitHub)**  
   [GitHub CSV Link](https://raw.githubusercontent.com/karwester/behavioural-finance-task/refs/heads/main/personality.csv)

2. **Assets Data (Supabase API)**  
   Supabase URL: `https://pvgaaikztozwlfhyrqlo.supabase.co/rest/v1/assets?select=*`  
   Accessed using a provided API key via Python `requests` library

---

## Key Task Requirements

- Combine the personality and asset datasets
- Identify the person with the **highest total asset value in GBP**
- Extract their **Risk Tolerance score** and include it in the cover letter
- Conduct EDA to explore patterns between financial traits and personality dimensions

---

## Key Findings

- The individual with the highest total assets in GBP has a **Risk Tolerance score of 0.555**
- Higher impulsivity is positively correlated with higher asset value
- Confidence and risk tolerance are strongly correlated personality traits
- Currency standardisation was essential due to a large variation in values (e.g. JPY vs GBP)

For detailed plots and deeper analysis, please refer to the `insights_report.docx` and visualisation graphs.

---

## Tools Used

- Python 3.11
- pandas, numpy, plotly, seaborn, matplotlib
- requests (for API access)
- Jupyter Notebook

---

## Submission

This project was submitted to Oxford Risk as part of the application for the Summer 2025 internship.  

---

Vishal Subramani   
