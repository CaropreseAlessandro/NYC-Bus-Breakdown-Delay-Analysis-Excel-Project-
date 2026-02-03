# 🚌 NYC Bus Breakdown & Delay Analysis (Excel Project)

## 🎯 Project Objective
The goal of this project is to analyze operational data from the NYC school bus system to identify patterns in service disruptions. By processing over **280,000 rows** of data, this study pinpoints the primary causes of delays and identifies the worst-performing bus companies and boroughs to support logistical improvements.

## 🧹 Data Cleaning & Preparation
To ensure data integrity and analytical accuracy, I performed the following steps:
* **Handling Large Datasets**: Efficiently managed and structured a raw dataset exceeding 280,000 records.
* **Date Standardization**: Utilized the `YEAR()` function to extract and isolate specific years (2015-2019) for annual trend comparisons.
* **Data Filtering**: Cleaned inconsistent entries in the "How_Long_Delayed" and "Reason" columns to enable accurate categorization and measurement.

## 🧠 Technical Skills & Formulas Applied
I utilized advanced Excel functions to transform raw data into actionable insights:
* **Lookup Functions**: Applied `VLOOKUP` and `XLOOKUP` to connect bus company IDs with their operational names and specific routes.
* **Statistical Aggregation**: Used `COUNTIFS` and `SUMIFS` to aggregate the total number of breakdowns per borough and per school year.
* **Logical Categorization**: Implemented `IF` and `IFS` statements to segment delay durations and identify critical delay types.

## 📊 Data Visualization
I developed a series of decision-oriented charts to make the findings accessible for stakeholders:
* **Clustered Bar Charts**: Used to visualize and compare the frequency of breakdowns across different NYC boroughs, such as the Bronx, Brooklyn, and Manhattan.
* **Pie Charts**: Created to demonstrate the percentage distribution of delay reasons, highlighting "Heavy Traffic" as the dominant factor.
* **Conditional Formatting**: Applied to bus company rankings to instantly highlight those with the highest number of reported delays, such as Reliant Trans or Leesel Trans.

## 💡 Key Business Questions Addressed
1. **Which borough is most affected?** The analysis identifies the specific geographical areas suffering most from service interruptions.
2. **What are the main causes of delays?** Quantified that "Heavy Traffic" and "Mechanical Breakdowns" are the leading reasons for school bus lateness.
3. **Who are the lowest-performing vendors?** Ranked bus companies by total incidents to provide a data-driven basis for performance audits.

## 📂 Repository Contents
* `Bus_Breakdown_and_Delays_NYC Project.xlsx`: The complete Excel workbook containing raw data, pivot tables, and visualizations.
* `Data Source`: NYC Open Data - Bus Breakdown and Delays.
