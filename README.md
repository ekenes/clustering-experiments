# Clustering Experiments

Clustering is a method of grouping points based on their spatial proximity to one another. Typically, clusters are proportionally sized based on the number of features within each cluster. This is an effective way to show areas where many points stack on top of one another.

The apps in this repo explore various ways to visualize clustered data.

## Default styles

The following apps demonstrate how clusters are automatically styled based on the layer's renderer when clustering is enabled.

- [Global earthquakes - total count](https://ekenes.github.io/clustering-experiments/default/earthquakes-count.html) - This app visualizes earthquakes along the Ring of Fire in November 2022 as point clusters. The size of each cluster indicates the total number of earthquakes within the cluster. Data source: USGS.
- [Global earthquakes - average magnitude](https://ekenes.github.io/clustering-experiments/default/earthquakes-average-magnitude.html) - This app visualizes earthquakes along the Ring of Fire in November 2022 as point clusters. The size of each cluster indicates the total number of earthquakes within the cluster. The color indicates the average magnitude of earthquakes within the cluster. Data source: USGS.
- [311 calls by incident type - predominant type](https://ekenes.github.io/clustering-experiments/default/nyc-311-predominant-type.html) - This app visualizes vehicle-related 311 incidents in 2015. Each incident is colored based on the incident type. Cluster colors indicate the most common incident type within the cluster. Data source: NYC OpenData.

## Custom styles

The following apps explore a few ways you can override the default style for point clusters.

- [Global earthquakes - distinct aggregate symbols](https://ekenes.github.io/clustering-experiments/custom/earthquakes-distinct-clusters.html) - This app visualizes earthquakes along the Aleutian Islands, Alaska in November 2022 as point clusters. Individual earthquakes are symbolized with a triangle. Clusters of earthquakes are symbolized with a circle. Data source: USGS.
- [New York City vehicle crashes - injuries](https://ekenes.github.io/clustering-experiments/custom/nyc-crashes-injuries.html) - This app visualizes vehicle crashes in New York City as point clusters in 2020. The color of each cluster indicates the ratio of injured persons to crash incidents. Data source: NYC OpenData.
- [New York City vehicle crashes - fatalities](https://ekenes.github.io/clustering-experiments/custom/nyc-crashes-fatalities.html) - This app visualizes vehicle crashes in New York City as point clusters in 2020. The red clusters indicate at least one fatality occurred within the cluster. Data source: NYC OpenData.
- [Clusters of high population world cities](https://ekenes.github.io/clustering-experiments/custom/population-total.html) - This app visualizes world population as clusters of high-population cities. Each cluster is sized based on the total population living in the cluster. Data source: ArcGIS Living Atlas of the World.
- [311 calls by incident type - donut charts](https://ekenes.github.io/clustering-experiments/custom/nyc-311-donut-charts.html) - This app visualizes vehicle-related 311 incidents in 2015. Each incident is colored based on the incident type. Clusters are represented as a donut chart where each color indicates an incident type that occurred within the cluster. Data source: NYC OpenData.
- [311 calls by incident type - pie charts](https://ekenes.github.io/clustering-experiments/custom/nyc-311-pie-charts.html) - This app visualizes earthquakes along the Ring of Fire in 2022 as point clusters. Clusters are represented as a pie chart where each color indicates an incident type that occurred within the cluster. Data source: NYC OpenData.
