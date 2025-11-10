# Live API Data Integration: Real-Time Dashboards with Python & Power BI

## Overview

This project focuses on building a **live, interactive dashboard** that displays important global statistics such as health, education, employment, and other key indicators. The data is sourced from a **public API** that updates regularly with the latest information.

Using **Python**, a script automatically fetches and processes this data for analysis, ensuring that the dataset remains **fresh and accurate without manual downloads or updates**.

The processed data is connected directly to **Power BI** using a live data connection. Because of this live integration, the dashboard refreshes automatically whenever new data becomes available, making it **highly efficient, reliable, and ideal for real-time monitoring**.

## Workflow Summary

1. **Data Fetching**: Python script connects to a public API and retrieves data.
2. **Data Processing**: Data is cleaned and structured for Power BI ingestion.
3. **Live Connection**: Power BI connects directly to the Python dataset.
4. **Automatic Refresh**: Power BI updates automatically as new API data arrives.
5. **Visualization**: Interactive visuals (charts, graphs, maps) display dynamic insights.

## Key Dashboard Objectives

Once connected, the Power BI dashboard addresses several key analytical questions:

### 1. Understand the Overall Economic and Social Landscape

* What is the average **GDP per capita**, giving a sense of individual economic well-being?
* What is the **average trade value**, showing how active countries are in global markets?
* How much do countries **spend on health relative to GDP** (indicating national priorities)?
* What is the **average GDP growth rate**, revealing economic momentum?
* What proportion of total land area is **classified as forest**, influencing natural resource use?

### 2. Analyze Trends in Socio-Economic Indicators Over Time

* Evaluate how key indicators (forest area, mobile subscriptions, internet subscriptions, GDP, renewable energy, unemployment, etc.) have **changed over time**.
* Identify positive or negative trends to understand countries' development pathways.

### 3. Evaluate the Impact of Internet Access on Immunization Awareness

* Analyze the relationship between **internet penetration and immunization rates**.
* Assess whether digital connectivity enhances awareness and access to health information.

### 4. Assess the Role of Internet Access in Reducing Unemployment

* Investigate whether expanding **internet access helps reduce unemployment levels**.
* Explore the economic implications of digital inclusion.

### 5. Identify Underperforming Countries in Poverty Reduction Efforts

* Determine the **bottom 10 countries** showing the **least progress** in poverty reduction.
* Guide policymakers, NGOs, and development agencies to prioritize interventions.

### 6. Identify Top-Performing Countries in Poverty Reduction Efforts

* Highlight the **top 10 countries** that have made the **most progress** in reducing poverty.
* Study the strategies of these successful countries for policy insights.

### 7. Examine Interrelationships Among Health Indicators

* Explore how indicators such as **health expenditure, life expectancy, immunization rates, child mortality,** and **disease burden** are **related to each other**.
* Identify strong or weak relationships to inform integrated health policies.

### 8. Investigate the Relationship Between Health Spending and Life Expectancy

* Analyze whether **increased investment in health expenditure** leads to **improvements in life expectancy using trend lines**.
* Evaluate if spending is an effective tool for improving population health or if complementary factors are required.

## Tools and Technologies

* **Python**: Data fetching, cleaning, and preprocessing.
* **Power BI**: Real-time dashboard visualization and live API integration.
* **Pandas, Requests**: Data handling and API interaction.
* **Public API (e.g., World Bank, WHO)**: Source of live global development data.

## Expected Outcome

The final Power BI dashboard will:

* Automatically refresh with new data.
* Display key metrics in interactive, dynamic charts.
* Help users explore global economic, health, and development patterns.
* Provide actionable insights for policymakers, NGOs, and researchers.

 

## Future Enhancements

* Add **AI-based forecasting** for GDP, health, and poverty indicators.
* Integrate **real-time alert systems** for major economic or health shifts.
* Include **country-specific drill-downs** and correlation matrices for deep analytics.

---

**Author:** Ghanshyam Gohil
**License:** MIT
**Keywords:** Power BI, Python, Live API, Data Dashboard, Global Statistics, Automation
