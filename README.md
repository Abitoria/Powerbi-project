#  IDSS2 Disease Outbreak & Health Analytics Dashboard

**Analyst:** Olawoyin Olufunmilayo Esther

##  Problem Statement
Despite continuous efforts in disease monitoring, there is limited visibility into how different diseases spread across states, affect various age and gender groups, and vary in their recovery and fatality outcomes. Without a clear understanding of these patterns, allocating resources effectively, targeting interventions, or anticipating emerging public health risks remains difficult. 

This project solves that problem by building an end-to-end analytical pipeline using **R** for data preprocessing and **Power BI** for interactive visual reporting, providing actionable insights into multi-disease outbreaks across 500 observations and 15 variables.

## 🛠️ Tools & Skills
* **R Programming** (Data Wrangling, Exploratory Data Analysis, Statistical Summary Metrics)
* **Microsoft Power BI** (Interactive Visualizations, Data Modeling, DAX Measures, Dashboard Layouts)
* **Public Health Analytics** (Geospatial Recovery Rates, Disease Prevalence, Temporal Trend Forecasting)

## Dashboard Preview
![Power BI Health Dashboard](health%20report.png)

## Key Findings & Insights
* **Overall Metrics:** The analytics model tracks an average recovery rate of 62.0%, across 132K confirmed cases, 156.6K reported cases, and 13K total deaths.
* **Disease Prevalence:** Malaria recorded the highest proportion frequency (0.22), followed closely by Typhoid (0.206) and COVID-19 (0.20).
* **Demographic Breakdown:** Patients show an average age range between 36.8 and 40.4 years across diseases, with a near even gender distribution of 50.42% male (67K) and 49.58% female (66K) vulnerability.
* **Geographic Disparities:** Recovery performance varies across states, with Plateau and Kano leading the recovery sums while Lagos records lower throughput figures.
* **Temporal Trends (2018–2022):** Multi year quarterly tracking of recovery rates reveals cyclical fluctuations, providing a historical baseline for outbreak preparedness.

## Strategic Recommendations
* **Targeted Resource Allocation:** Direct healthcare resources and intervention programs to states with lower recovery rates.
* **Age & Gender Specific Programs:** Implement tailored public health outreach addressing the specific age demographics most affected by malaria and typhoid.
* **Outbreak Preparedness:** Utilize historical 2018–2022 trend lines to anticipate seasonal surges and strengthen early testing and reporting systems.

## Repository Files
* `data analysis R.R`: The underlying R script used for data cleaning, variable transformation, and exploratory statistical analysis.
* `healthcare_data_model.pbix`: The Power BI file containing data relationships, measures, and the interactive visual interface.
