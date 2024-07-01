# Students Performance Analysis


![R](https://img.shields.io/badge/language-R-blue)
![RStudio](https://img.shields.io/badge/RStudio-IDE-blue)

<img src="https://www.r-project.org/logo/Rlogo.png" alt="R Logo" width="100" height="100">

This project aims to analyse students' performance data using various statistical methods and visualisations to identify key factors influencing their performance. The project is implemented using the R programming language.

## Table of Contents
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Statistical Analysis](#statistical-analysis)
- [Predictive Modelling](#predictive-modelling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Run the Analysis](#run-the-analysis)

## Data Preparation and Cleaning
- Processed and cleaned a comprehensive dataset, including handling missing values and removing outliers.
- Ensured data validity and integrity for accurate analysis.

## Statistical Analysis
- Conducted a comparison of student performance across different academic years, identifying a statistically significant decline in final year marks compared to the first year.
- Explored correlations between yearly marks, revealing weaker relationships in the final year, suggesting external factors influencing performance.

## Predictive Modelling
- Developed simple linear regression models to predict final year marks based on earlier years' performance, with Year 3 being the most significant predictor.
- Analyzed the impact of language proficiency on overall academic performance, confirming a positive correlation.

## Exploratory Data Analysis
- Created visualizations to depict relationships between variables, providing clear insights into data trends and distributions.

The project provided actionable insights into the factors affecting student performance and highlighted the importance of language proficiency in academic success, paving the way for targeted educational strategies.

## Project Structure

The project is organized into the following directories and files:

- `data/`: Contains the dataset used for analysis.
  - `contents.csv`: The main dataset with student performance data.
- `docs/`: Contains the generated report.
  - `Students_Performance_Analysis_Report.pdf`: The PDF report summarizing the findings and analysis.
- `scripts/`: Contains the R Markdown script for the analysis.
  - `Student_Performance_Analysis.Rmd`: The main R Markdown script that performs the analysis and generates the report.

## Prerequisites

- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/)

## Run the Analysis

Knit the `Student_Performance_Analysis.Rmd` file in RStudio to generate the report. This will execute all code chunks and produce results and visualizations.

This setup ensures a structured approach to analyzing student performance, allowing for reproducibility and ease of understanding for future reference.
