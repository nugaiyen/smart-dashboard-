# smart-dashboard-
I used AI in this project to debug, and explain c3 and d3. I did not use AI to write or complete any components where AI use is prohibited. I can explain the relevent codes and the reasoning behind them. <br> <Br> 
For this project, I used two datasets: <a href ="https://data-seattlecitygis.opendata.arcgis.com/datasets/b4a142f592e94d39a3bf787f3c112c1d_0/explore?location=47.614610%2C-122.336918%2C11" target="_blank"><strong>Neighborhood Atlas Map</strong> </a> and <a href="https://home.urbanlogiq.us/public/sdot-crash-analysis?c=47.9133696%2C-122.241024&z=11" target="_blank"><strong>Crash Analysis.</strong> </a>

Using Google Colab, I cleaned both datasets, formatted coordinates, and then combined them through a spatial join. This linked each collision to its neighborhood, enabling analysis of collision patterns across Seattle.

This dashboard visualizes car collisions in Seattle. The data is choroplethed by neighborhood while also displaying individual collision points. The choropleth is rendered with partial opacity so that the underlying road network remains visible. Warmer colors convey a sense of danger, red was avoided for the choropleth to ensure the individual points remain the most prominent feature.


This work connects to my group project because it also focuses on transportation, specifically public transportation, allowing us to analyze spatial patterns and accessibility in the city.

https://nugaiyen.github.io/458p6-smart-dashboard/