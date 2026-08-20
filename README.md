# ⚓ An Analysis of Factors Influencing Maritime Activity in Singapore

## Overview

This project analyses factors influencing maritime activity in Singapore using publicly available datasets from Singapore's Open Data portal, data.gov.sg. The objective is to examine how weather conditions and major global disruptions affected Singapore's maritime activity, as well as to explore trends in merchandise trade.

---

## 📌 Objectives

- Analyze trends in Singapore's maritime activity using vessel arrivals and container throughput data.
- Examine the relationship between weather conditions and maritime activity.
- Assess the impact of major global disruptions on vessel arrivals and container throughput.
- Analyse the recovery of maritime activity following major disruptions.
- Analyze Singapore's merchandise trade composition and trends.
- Demonstrate data cleaning, integration, analysis and visualization using Python, SQL and Tableau.

---

## 📂 Datasets

The analysis uses multiple datasets obtained from Singapore Open Data ([data.gov.sg](https://data.gov.sg/)), including:

- Vessel Arrivals (>75 GT) Total, Monthly
- Container Throughput, Monthly
- Historical Daily Weather Records
- Merchandise Trade by Commodity Section, Monthly Seasonally Adjusted

The analysis also considers major events such as:

- Northeast Monsoon Surge (January 2011)
- SARS Outbreak (2003)
- Global Financial Crisis (2008–2009)
- COVID-19 Pandemic (2020–2021)

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Bokeh)
- SQL (NeonDB)
- Microsoft Excel
- Google Collab / Jupyter Notebook

---

## 💻 Data Preparation

The datasets were cleaned and standardized before analysis, including:

- Importing and inspecting CSV datasets
- Converting dates into standard datetime formats
- Reshaping datasets from wide to long format
- Aggregating daily weather data into monthly values
- Standardizing time periods across datasets
- Merging datasets for comparative analysis
- Handling missing and inconsistent values
- Calculating percentage changes and summary statistics
- Preparing datasets for visualization and analysis

---

## 📊 Analysis Performed

The project includes:

- Analysis of monthly vessel arrivals in Singapore
- Analysis of monthly container throughput
- Examination of the relationship between rainfall and vessel arrivals
- Analysis of the impact of major global disruptions on maritime activity
- Measurement of changes in vessel arrivals and container throughput during disruption periods
- Analysis of the recovery of maritime activity following major disruptions
- Comparison of pre-disruption, disruption and recovery periods
- Analysis of Singapore's merchandise trade composition
- Data visualizations using Matplotlib, Seaborn and Bokeh
- Interpretation of trends and relationships between datasets

---

## 📈 Key Findings

Some key insights include:

- Weather conditions may influence Singapore's maritime activity, although the relationship between rainfall and vessel arrivals was relatively weak.
- Major global disruptions resulted in noticeable changes in vessel arrivals and container throughput.
- Maritime activity showed varying levels of impact and recovery across different disruption events.
- Singapore's maritime sector demonstrated resilience by recovering following major disruptions.
- The extent and speed of recovery differed depending on the nature and duration of each disruption.
- Singapore's merchandise trade includes both domestic exports and re-exports, highlighting its important role as a regional trading and transshipment hub.
- Comparing different disruption periods provides insights into the resilience of Singapore's maritime sector.

---

## 💡 Recommendations

- Monitor the impact of major weather events on maritime operations to support operational planning and resilience.
- Analyze a wider range of weather variables, such as wind speed, visibility and thunderstorms, to better understand their influence on maritime activity.
- Consider other major global disruptions and geopolitical events when assessing the resilience of Singapore's maritime sector.
- Use historical disruption patterns to support contingency planning and improve preparedness for future supply-chain disruptions.
- Further investigate the relationship between maritime activity, trade performance and external economic factors.

---

## 📊 Visualizations

The project includes static and interactive visualisations developed using Python and Bokeh.
Interactive visualizations were developed to explore:

- Maritime activity trends
- Impact of major disruptions
- Recovery following major disruptions
- Comparison between disruption events
- Weather and maritime activity relationships

Interactive charts were also developed using Bokeh to allow users to explore the impact and recovery of different major events.
