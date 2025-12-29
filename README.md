# COVID-19 Dashboard (R)

## Overview
Interactive Shiny dashboard to analyze COVID-19 cases by age, sex, COVID outcome, patient type, and underlying conditions.  
Demonstrates:
- Data cleaning and preprocessing
- Interactive visualizations using Shiny and ggplot2
- Filtering and summary statistics
- Heatmaps and stacked bar charts

## Features
- Filter by sex, age, COVID-19 outcome, patient type, underlying conditions, pregnancy, ICU admission, ventilator usage
- Interactive dashboard with multiple tabs:
  - Overview & Summary
  - Outcome Analysis
  - Underlying Condition Analysis
  - Fatality Factors
- Displays filtered dataset statistics
- Includes plots: bar charts, density plots, boxplots, heatmaps

## Project Structure
- `cov.r` – Full Shiny app code
- `data/Covid Data.csv.zip` – Dataset
- `.gitignore` – Files/folders to ignore
- `requirements.txt` – R package dependencies

## How to Run
1. Open RStudio and set working directory to this project
2. Install required packages:
   ```r
   install.packages(c("shiny","shinythemes","shinyWidgets","tidyverse","ggplot2","data.table","patchwork","plotly","purrr"))
3. Run the dashboard: cov.R
4. The Shiny dashboard will open in your browser.
