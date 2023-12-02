---
name: FP3
tools: [Python, HTML, vega-lite]
image: assets/pngs/fp3.1.png
description: There are two visualization parts!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
# Coastal Climate Insights: Analyzing Beach Water, Solar Radiation, and Air Temperature Trends 

Group Members: 
Yuefan Zhou, Ian Lin, Zixu Gong

# Introduction to the dataset

The primary dataset, Beach Water Temperature Trends, offers a comprehensive record of the water temperatures recorded at various beaches over time. Using this dataset, we can analyze fluctuations in water temperature, which is crucial for understanding the environmental conditions of beach areas. Such data is invaluable for environmental studies, tourism planning, and local residents who may use the beaches for recreational activities.

The visualizations are based on this [raw data](https://query.data.world/s/ioozdhrxwt5uyqyyuh5hfcpnxwh7xw?dws=00000).
A link to the [Python notebook](https://github.com/nivaGzx/nivaGzx.github.io/blob/main/python_notebooks/FP3.1.2.ipynb).


## Discussion of the Primary Dataset's Visualization

The "Average Monthly Water Temperature and Range" graph we plotted is a multifunctional visualization tool that shows temperature changes at various beaches over time. Users can compare and analyze specific trends and patterns in water temperatures across beaches by selecting different beaches through the dropdown menu. Additionally, hovering over the plot displays detailed information at specific points, supporting the need for precise temperature analysis.

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_with_dropdown.json" style="width: 100%"></vegachart>

## Discussion of the Two Contextual Datasets' Visualization

Two contextual visualization were created by ourselves, here is the [Python notebook](https://github.com/nivaGzx/nivaGzx.github.io/blob/main/python_notebooks/FP3.1.2.ipynb).

### Solar Data Graph Description

The "Average Monthly Solar Radiation and Range" graph is an assistant tool that illustrates solar radiation levels over time. This graph has functionality similar to the Primary Dataset's visualization. It also contains a dropdown menu for beach selections and a similar visualization for Solar Radiation level, which is a potentially impactful factor for the water temperature. Users can select a specific beach and observe its solar radiation trends over time, which can be compared with water temperature data from the primary visualization to draw deeper insights into environmental patterns.

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_with_dropdown_solar.json" style="width: 100%"></vegachart>

### Air Data Graph Description

The "Average Monthly Air Temperature and Range" graph is also an assistant tool that displays air temperature variations over time. Similar to the Primary Dataset's visualization, it also includes a dropdown menu for beach selection and detailed visualization of air temperature levels that would change based on beach selection. Air temperature might also be a critical factor influencing water temperature, making this graph an essential component in the comprehensive environmental analysis of water temperature. This data can be used with the primary dataset's visualization, enabling users to gain deeper insights into the environmental factors affecting beach conditions and their water temperatures.

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_with_dropdown_air.json" style="width: 100%"></vegachart>

# Conclusion

In conclusion, by integrating the Beach Water Temperature Trends dataset with the contextual dataset, we provided a multifaceted visualization tool providing insights into environmental conditions at various beaches. By enabling users to visualize and compare data across water temperature, solar radiation, and air temperature, our visualizations offer valuable insights for environmental research, tourism planning, and community engagement.