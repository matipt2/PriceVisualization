# Krakow Real Estate Analysis

This project aims to analyze real estate data in Krakow, Poland, focusing on average prices and price per square meter in different districts of the city. It utilizes web scraping techniques to gather data from real estate websites and employs various libraries for data manipulation, visualization, and geographical mapping.

## Libraries Used

- `requests`: For making HTTP requests to fetch web pages.
- `BeautifulSoup`: For parsing HTML content.
- `random`: For generating random numbers.
- `json`: For working with JSON data.
- `re`: For regular expressions for text processing.
- `folium`: For creating interactive maps.
- `geojson`: For working with GeoJSON data.
- `IPython.display`: For displaying interactive visualizations.
- `matplotlib.pyplot`: For data visualization.
- `unidecode`: For text normalization.


## How It Works

The project consists of several functions that perform the following tasks:

- **Web Scraping**: It scrapes real estate data from a specified URL using `requests` and `BeautifulSoup`.
- **Data Processing**: It processes the scraped data to extract relevant information such as prices and districts.
- **Data Analysis**: It calculates average prices for each district and visualizes the data using `matplotlib` and `folium`.
- **Visualization**: It generates visualizations such as bar charts and heat maps to represent the data effectively.

## Example Outputs

The project generates outputs such as:

- A map displaying average prices in different districts of Krakow.
- Bar charts showing average prices and price per square meter for each district.

- ## Heatmap
- ![HeatMap](/images/heatmap.png)
-  ## Plots
- ![Bar Chart](/images/permeter.png)
- ![Bar Chart](/images/price.png)
-![Bar Chart](/images/districtsfrequency.png)
-![Bar Chart](/images/numberofrooms.png)
-![Bar Chart](/images/priceperarea.png)

