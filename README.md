🌦️ Weather Analytics Dashboard (Power BI + Live API)

This project is a real-time weather analytics dashboard built using Power BI and a live Weather API. It provides insights into current weather conditions and 7-day forecasts for major cities in Nepal.

📊 Features
🌡️ Real-time temperature monitoring
📅 7-day weather forecast visualization
🌧️ Rain probability analysis
🌅 Sunrise and sunset tracking
🌬️ Wind speed, humidity, pressure, and visibility metrics
☀️ UV Index and precipitation tracking
🌍 Multi-city comparison (Nepal major cities)
🧪 Air Quality Index (AQI) monitoring:
PM2.5, PM10, CO, NO2, O3, SO2
Dynamic AQI color coding
Health status & recommendations
🛠️ Tech Stack
Power BI – Dashboard development
DAX (Data Analysis Expressions) – KPI calculations and logic
Power Query (M Language) – Data transformation
REST API – Live weather data integration
JSON – Data format
🔄 Data Pipeline
Connected to Weather API using API key
Extracted JSON data via Web connector in Power BI
Fetched data for multiple cities by modifying API query parameters
Combined datasets using Append Queries
Created a Master Table
Built derived tables:
Current → real-time metrics
Forecast_DAY → daily forecast data
Cleaned data:
Removed unnecessary columns
Removed duplicates
Filtered required fields
Loaded final dataset into Power BI model
📈 Key DAX Measures
AQI classification and color indicators
Temperature (Current & Forecast)
Humidity, Wind Speed, Visibility
UV Index, Pressure, Precipitation
Last updated timestamp
Rain probability analysis
🎯 Use Case

This dashboard helps users:

Monitor real-time weather conditions
Analyze upcoming weather trends
Track air quality for health awareness
Compare weather across cities


👨‍💻 Author

Sanjeeb Sapkota

SAP B1 HANA | Data Analytics | Power BI
GitHub: https://github.com/sanjeebsapkota
