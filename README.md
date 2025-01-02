# Synthetic Control Analysis with UNHR Data
This repository contains an R Markdown file designed to perform a synthetic control analysis to evaluate the impact of UN Missions on the number of yearly complaints about human rights violations, as reflected in Special Procedure communications.

## File Description
1 UNHR Data.Rmd
- Main script that processes and analyzes data from UNHR, WDI, and V-Dem sources.
- Focuses on exploring trends and performing synthetic control analysis.

2 World Development Indicators (WDI)
- Socio-economic data including GDP, population, urbanization, and access to electricity.

3 V-Dem Dataset
- Provides democracy indices, particularly the Liberal Democracy Index (v2x_libdem), for political and institutional analysis.

## Analysis Workflow
1. Data Cleaning and Visualization
- Reads and processes UNHR data.
- Visualizes trends in human rights violations using Special Procedure communications.
  
2. Data Preparation
- Prepares data for synthetic control analysis by:
- Merging UNHR, WDI, and V-Dem datasets.
- Transforming the data into a long format for analysis compatibility.

3. Synthetic Control Analysis
- Performs a Synthetic Control Method (SCM) to evaluate the impact of UN Missions.
- Constructs a synthetic comparison unit for analysis.
  - Includes:
  - Correlation matrix for predictor selection.
  - Weights table to assess the contribution of control units.
  - Visualization via Synth and Gap plots to interpret the results.

# Project Context
This project is part of a United Nations Human Rights Course at the university, aiming to analyze the effectiveness of UN interventions in addressing human rights violations globally.

