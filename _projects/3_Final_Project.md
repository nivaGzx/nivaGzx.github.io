---
name: Final Project 
tools: [Python, HTML, vega-lite]
image: assets/pngs/Final_project1.png
description: There are two interactions which are combining each other!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Final Project

The visualizations are based on this [raw data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv).
A link to the [Python notebook](https://github.com/nivaGzx/nivaGzx.github.io/blob/main/python_notebooks/Workbook.ipynb).


## Understanding the Primary Dataset:

Beach Water Temperature Trends The primary dataset provides a detailed look at the water temperatures recorded at various beaches over time. By converting the 'Measurement Timestamp' to a date-time format and extracting the 'Year' and 'Month' from it, we can analyze the seasonal and yearly fluctuations in water temperature. This is crucial for understanding the environmental conditions of these beach areas. For instance, the visualization for a selected beach, let's say "Montrose Beach," showcases how water temperature varies each month and highlights the differences from year to year. Such data is invaluable for environmental studies, tourism planning, and local residents who may use the beaches for recreational activities. The use of line plots with markers for each data point makes it easy to observe trends and compare temperatures across different years.

<vegachart schema-url="{{ site.baseurl }}/assets/json/Montrose_Beach_water_temperature_chart.json" style="width: 100%"></vegachart>

## Insights from the Contextual Dataset: Weather Station Observations

In contrast, the contextual dataset gives us insight into the broader climatic conditions of the region, focusing on air temperature and humidity as recorded by a specific weather station. By preprocessing this dataset in a similar manner (extracting 'Year' and 'Month' from timestamps), we can draw parallels between the atmospheric conditions and the water temperatures from the primary dataset. The visualization of air temperature and humidity from a selected weather station for the year 2016 allows us to observe the ambient environmental conditions. Higher air temperatures during the summer months, for example, might correlate with higher water temperatures, indicating a direct impact of air temperature on beach water conditions.

## A Comprehensive Environmental Picture 

Bringing these two datasets together paints a comprehensive picture of the environmental conditions at the selected beach locations. The water temperature trends from the primary dataset, when viewed alongside the air temperature and humidity data from the contextual dataset, can help us understand how broader weather patterns influence beach environments. For instance, a particularly hot and humid year might lead to warmer water temperatures, affecting marine life, water quality, and beachgoer experiences. This kind of analysis is fundamental in fields like environmental science, where understanding the interaction between different environmental factors is key to addressing ecological challenges. For a novice, this exploration underlines the interconnectedness of our ecosystem, showcasing how changes in one aspect of the environment can have ripple effects in another.
