# Temporal-Trends-in-Antidepressant-Prescriptions
Longitudinal exploration of antidepressant prescriptions and costs across NHS England regions (2021-2024) as part of Dig Data's NHS Step Up Career Challenge.
# NHS Data Challenge

## Project Overview
The **NHS Data Challenge** project is focused on analyzing antidepressant prescribing trends in NHS England, specifically the prescribing of Sertraline. The project includes analysis of costs, prescription trends, and potential strategies for improving cost efficiency in the system.

## Files Overview

### Main Files:
- **`AntidepressantPrescribingReport.Rmd`**: This is the RMarkdown file that contains the code, analysis, and discussions for the project. It is the source file for generating the final report.
- **`AntidepressantPrescribingReport.html`**: This is the knitted version of the `AntidepressantPrescribingReport.Rmd`. It contains the output of the RMarkdown file, formatted into a readable HTML report. This version is ready to be shared or viewed directly.
- **`dig-data-step-up.Rproj`**: This is the RStudio project file. It sets up the working environment, making it easy to manage the project's files, settings, and R scripts in one unified space. Opening this file in RStudio ensures all paths and environment settings are correctly configured for this project.

### Data Folder:
The **`data/`** folder contains the following RDS files:
- **`EEXTENSION_STEP_UP_REGIONAL_ANTIDEPRESSANTS.Rds`**
- **`STEP_UP_REGIONAL_ANTIDEPRESSANTS.Rds`**

  
  You can install them with the following commands:
  ```r
  install.packages("tidyverse")
  install.packages("highcharter")
  install.packages("dplyr")
  install.packages("ggplot2")
