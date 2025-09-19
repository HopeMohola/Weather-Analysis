# Weather Classification Power BI Dashboard
## Project Overview
This project uses a weather dataset (13,200 records, 11 features) to build an interactive Power BI dashboard. The goal is to explore and classify weather conditions across different seasons and locations.

T## he dashboard provides insights into:
- Temperature, humidity, wind speed, and visibility trends
- Precipitation and cloud cover distribution
- Seasonal weather patterns
- Weather type breakdown by location

## Dataset
- File: weather_classification_data.csv
- Rows: 13,200
- Columns: 11

### Feature	Description
- Temperature	Air temperature in °C
- Humidity	Relative humidity (%)
- Wind Speed	Wind speed (km/h)
- Precipitation (%)	Probability of precipitation
- Cloud Cover	Sky condition (clear, partly cloudy, overcast)
- Atmospheric Pressure	Pressure in hPa
- UV Index	UV radiation level
- Season	Season of the year
- Visibility (km)	Visibility distance
- Location	Geographical context (coastal, inland, mountain)
- Weather Type	Classified condition (Sunny, Rainy, Cloudy, etc.)

## Data Cleaning & Transformation
- No missing values
- Minor transformations applied in Power BI:
      - Converting categorical columns into dimensions
      - Creating calculated measures (e.g., Average Temperature per Season)
      - Aggregating data by location and weather type

## Power BI Dashboard Features
- Overview page: Summary of weather patterns
- Seasonal trends: Compare metrics across Winter, Spring, Summer, Autumn
- Location analysis: Coastal vs. Inland vs. Mountain conditions
- Weather type distribution: Sunny, Rainy, Cloudy, etc.

## How to Use
1. Clone this repository: git clone https://github.com/yourusername/weather-powerbi-dashboard.git
2. Open Power BI Desktop.
3. Load weather_classification_data.csv.
4. Build visuals or import the included .pbix file (if shared).

## Future Enhancements
Include predictive modeling (e.g., ML weather classification)

## Authors
1. Mohola Motshabi Hope
       email : motshabimohola@gmail.com
