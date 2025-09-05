# CO2 Emission Analysis: A Tableau Project

### An interactive data visualization project exploring global carbon dioxide emissions and trends from 1960 to 2021.

---

#### Table of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---

**Project Overview**

This project provides an in-depth analysis of global carbon dioxide emissions (kt) from 1960 to 2011. The purpose of this project is to visualize the trends, identify major contributing countries and regions, and provide actionable insights for stakeholders interested in climate change, environmental policy, and sustainable development. The dashboard created allows users to dynamically explore emissions data by country, region, and year.

**Data Sources**

The primary dataset for this analysis is CO2 emissions (kt), sourced from the World Bank Open Data. This dataset contains annual measurements of carbon dioxide emissions for over 200 countries and territories, providing a robust foundation for time-series and geospatial analysis.

**Tools Used**

* Tableau Public: Used for creating the interactive dashboard and visualizations.
* Microsoft Excel: Used for initial data preparation, cleaning, and exploratory analysis.

**Data Cleaning and Preparation**

The raw data was prepared before being loaded into Tableau to ensure accuracy and consistency. The key steps included:
* Handling Missing Values: Missing values for specific years or countries were identified and handled.
* Data Type Conversion: Ensured that the 'Year' column was correctly formatted as a date, and the 'CO2 Emissions' column was a numerical type.
* Standardizing Country Names: Verified and corrected any inconsistencies in country or region names to ensure accurate mapping and filtering in Tableau.
* Duplicates: Looked out for duplicates.
* Spaces: Eliminated Unwanted spaces.
  
**Exploratory Data Analysis**

When we first explored the dataset, we noticed big differences in emission levels across countries and over time. Overall, global emissions have been rising, but the share from each country has shifted.
The top contributors, in order, are the United States, China, Japan, Russia, and Germany. Among them, the U.S., China, and Japan have shown a steady increase in emissions since 1960. In contrast, Russia and Germany followed a different path—their emissions only started being recorded around 1991–1993, and since then they have generally declined.
This phase of the analysis was mainly about getting a sense of the data: how emissions are distributed, spotting broad trends, and identifying countries that stand out from the norm.

**Data Analysis**

The core of the analysis involved using Tableau's features to visualize trends and patterns. This included creating a choropleth map to show emissions by country and a line chart to track global and regional trends. One of the key features used was the RANK() table calculation in Tableau to identify the top  emitting countries for any given year.

**Results and Findings**

Our analysis revealed some important insights:
* Rising Emissions: Global CO₂ emissions have been climbing steadily since 1960.5
* Top Contributors: The United States, China, and Japan remain the biggest emitters over time.
* Regional Shifts: Developing economies have seen sharp increases in emissions over the past 30 years, while some developed countries have been able to stabilize or even reduce theirs.

**Recommendations**

Based on these findings, we suggest:
* Target Major Emitters: Policies should prioritize the countries contributing the most emissions, since action here will have the largest global impact.
* Dig Deeper by Sector: Further analysis should focus on industries like energy, transport, and manufacturing to see where emissions cuts are most possible.
* Add Per Capita Data: Including emissions per person would give a fairer picture of each country’s impact relative to its population size.

**Limitations**

While useful, the analysis has some gaps:
* Per Capita Missing: We only looked at total emissions, not per-person contributions.
* Broad View: The data is only at the country level, not broken down into regions or cities.
*Data Gaps: Some sources of emissions (like land-use changes) may not be included in the dataset.

**References**

- Dataset: World Bank Open Data – “CO₂ emissions (kt)”
- Tool Used: Tableau Public
