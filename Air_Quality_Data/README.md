📊 Air Quality Index (AQI) Dashboard
This repository contains a dynamic and interactive Power BI dashboard for analyzing air quality data. The project provides a comprehensive solution for visualizing and exploring trends in Air Quality Index (AQI) across various cities.

---

Key Features
* Interactive Dashboard: The `.pbix` file is a fully functional Power BI report with interactive visuals and slicers, allowing users to explore data at a high level or drill down into specific details.
* Time-Series Analysis: The dashboard includes visuals like line charts with trend lines to show air quality trends over time (daily, monthly, and yearly).
* Geospatial Visualization: A filled map is used to show the geographical distribution of air quality, with cities color-coded based on their average AQI values.
* Data Consolidation: The Power BI file demonstrates a best practice of data consolidation using Power Query to append multiple monthly data files (`.csv` or `.xlsx`) into a single, clean table for analysis.
* Key Performance Indicators (KPIs): The dashboard features cards to display key metrics such as the average AQI, total cities, and total pollutants, providing a quick summary of the data.

---

### Files in this Repository
 `AirQuality.pbix`: This is the main Power BI project file. You can open this file with Power BI Desktop to view the data model, reports, and underlying DAX measures and queries.

---

How to Use
1.  Prerequisites: You must have **Power BI Desktop** installed on your machine. You can download it for free from the Microsoft website.
2.  Download: Clone this repository or download the `AirQuality.pbix` file.
3.  Open: Open the file in Power BI Desktop. The report will load, and you can begin interacting with the visuals and slicers.

---

Data Source
The data used in this dashboard is based on monthly air quality index reports. The Power Query section of the file is configured to read from a folder, allowing for easy data refreshes by simply adding new monthly files to the source folder.
