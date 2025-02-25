# US Heat Map Politeness Level by Regions

## Overview
This project is an interactive Streamlit application that visualizes politeness levels across different regions in the United States. The visualization is based on survey data collected from individuals who were asked about various social interactions during flights. The results are displayed using an interactive choropleth map and bar charts.

## Features
- **Interactive Heat Map**: Displays politeness scores across US regions based on user-selected income and gender filters.
- **Data Filtering**: Users can filter data by household income and gender to see differences in politeness scores.
- **Dynamic Graphs**: Additional visualizations show politeness scores based on education level, income, and gender for a selected region.
- **GeoJSON Integration**: Uses GeoPandas and Plotly to handle geographic data and render an accurate regional heat map.

## Data Sources
- **Survey Data**: The application reads a preprocessed dataset containing politeness scores from a Google Drive CSV file.
- **GeoJSON Data**: A GeoJSON file containing the boundaries of aggregated US regions is downloaded from GitHub.

## Technologies Used
- **Python Libraries**:
  - `streamlit` (for building the interactive web app)
  - `pandas` (for data manipulation)
  - `geopandas` (for working with geographic data)
  - `matplotlib` and `plotly` (for visualizing data)
  - `shapely` (for handling geometric operations)
  - `requests` (for downloading external files)

## Installation
To run the project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/tzuflahan/Streamlit.git
   cd Streamlit
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Launch the application using the command above.
2. Use the sidebar to select household income and gender filters.
3. Explore the interactive heat map to analyze politeness scores across regions.
4. Select a specific region to view detailed graphs on education, income, and gender.

## Authors
- **Ayelet Hashar Cohen**
- **Tzuf Lahan**

## License
This project is licensed under the MIT License.

