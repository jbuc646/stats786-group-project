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
- Open stats768-group-project-report.Rmd in RStudio
- make any edits and updates there or in different files if needed
- Click Knit to render the full report
- make sure to push any changes back into the repo ASAP so we are all working off the most up-to-date version.
- and please remember to pull before making edits each time to pick up anyone's recent changes
