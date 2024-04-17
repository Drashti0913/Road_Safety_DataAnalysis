# Road_Safety_DataAnalysis

### Overview
This project analyzes road safety data to identify trends and patterns in accidents, focusing on accident severity, weather conditions, types of vehicles involved, and road conditions. The aim is to provide insights that could help in improving road safety measures.

### Data Preparation
The data preparation involves importing datasets, cleaning data, and handling outliers:

Data Import: Data is imported from an Excel workbook using Power BI's 'Get Data' option.
Data Cleaning: Includes handling missing values and removing irrelevant columns such as 'Carriageway_Hazards'.
Outlier Handling: Outliers in the data are addressed using Z-score calculations for columns like 'Number_of_Vehicles' and 'Number_of_Casualties'.
Visualizations
The dashboard includes various visualizations to explore the accident data:

Accident Severity vs. Weather Condition: Stacked bar chart
Vehicle Types vs. Rural Urban Area: Bar chart
Road Surface Conditions vs. Count of Accidents: Stacked column chart
Days of the Week vs. Counts of Accident Index: Donut chart
Count of Year vs. Accident Index: Line chart
Accident Index vs. Accident Severity: Pie chart
Dashboard
The dashboard is designed to be user-friendly, providing a comprehensive overview of the data at a glance. Filters for specific criteria like local authority districts are available to narrow down the data views.

### Tools Used
Power BI Desktop: For creating visualizations and dashboards.
Excel: Source data in Excel format.
### Project Structure
Data/: Folder containing the raw Excel data files.
Reports/: Power BI reports and other documentation.
