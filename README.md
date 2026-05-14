# STATS786 Group Project — Nelson Temperature Time Series
## Group 4: Joshua Buchanan, Bea Cooke, Xinyi Kong, Marlon Chhour

## Overview
This repository contains the analysis and report for the STATS786 group project. We analyse a monthly average temperature time series recorded in Nelson, New Zealand, spanning April 1943 to mid-2025. The goal is to model and forecast average monthly temperatures using ETS, ARIMA, and dynamic regression models.

## Repository Structure

- nelson.csv                               # Raw data file
- stats768-group-project-report.Rmd        # Main RMarkdown report
- stats768-group-project-report.html       # Rendered report
-  786_Instructions_2026.html       # Assignment instructions from Matt
-  README.md


## Requirements
All analysis is done in R. The following packages are required:
rinstall.packages(c("tidyverse", "fpp3", "tsibble", "feasts", 
                   "fable", "lubridate"))
                   
## How to Run

- Clone the repository
- Place the data file in the data/ folder
- Open group_project_report.Rmd in RStudio
- Click Knit to render the full report
