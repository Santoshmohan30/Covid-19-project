# COVID-19 Data Analysis Report

## Introduction
This report analyzes COVID-19 and vaccination data for India. The analysis focuses on understanding the spread of the virus, active cases, deaths, and vaccination progress across different states in India.

## Data Sources
- **COVID-19 Data:** The COVID-19 data is sourced from the "covid_19_india.csv" file.
- **Vaccination Data:** The vaccination data is sourced from the "covid_vaccine_statewise.csv" file.

## Data Preprocessing
- Null values and irrelevant columns were removed from the COVID-19 dataset.
- Date columns were converted to datetime format for better analysis.
- Active cases were calculated by subtracting cured and death cases from confirmed cases.

## Analysis
### COVID-19 Analysis
- The top 10 states with the most active cases were visualized using a bar plot.
- The top 10 states with the most deaths were visualized using another bar plot.
- The trend of active cases over time for the top 5 affected states was visualized using a line plot.

### Vaccination Analysis
- The total number of males and females vaccinated was visualized using a pie chart.
- The top 5 states with the highest total vaccinations were visualized using a bar plot.
- The bottom 5 states with the lowest total vaccinations were visualized using another bar plot.

## Conclusion
- Maharashtra has the highest number of confirmed cases, followed by Kerala and Karnataka.
- The vaccination drive has been successful, with significant numbers vaccinated across various states.
- Further analysis and tracking of vaccination progress are essential to combat the spread of COVID-19 effectively.

