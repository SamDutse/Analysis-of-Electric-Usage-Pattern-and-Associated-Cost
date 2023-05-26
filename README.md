# Analysis-of-Electric-Usage-Pattern-and-Associated-Cost

# INTRODUCTION
The data was collected from my apartment unit in San Jose for one plus year. The data is collected with smart meters and shared by the energy company. This is time-series data by nature and can be used for various time-series Machine Learning experiments.

## Description of Data
The data contains eight attributes.

TYPE - This is an information column. The value is 'Electric usage' for all the observations.
DATE - Date of electric consumption. There is no timestamp in this field.
START TIME - Start time of the consumption.
END TIME - End time of the consumption
USAGE - Consumption in kWh
UNITS - This column denotes measurement unit. It is kWh for all the observations.
COST - Cost of consumption in $.
NOTES - Mostly an empty column
With this data obtain from kaggle, this project check power consumption with the cost of consumption using MS SQL.

# KEY FINDINGS
- Analyzed yearly, monthly, and weekly electric usage patterns, grouping data by year, month, and weekday to calculate metrics such as average, minimum, and maximum usage.
- Identified stable average usage patterns over the period studied, with highest consumption in 2017, and noted that total usage tended to peak in the winter months.
- Discovered that electric usage was highest on Sundays, indicating potential areas for optimization.
- Conducted cost analyses over years, months, and weekdays, revealing that winter months and weekends were associated with higher costs.
- Provided insights to stakeholders on electric usage patterns and associated costs, helping to inform decision-making and potentially identify areas for cost savings.

