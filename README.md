# Morocco Weather Power BI Dashboard

An interactive and fully automated dashboard displaying current weather conditions, a 7-day future forecast, and a 7-day historical archive for 18 Moroccan cities. The project relies on live data fetched from WeatherAPI.

## Key Features
* **Automated Data Refresh:** Configured to update automatically 8 times a day directly via Power BI Service.
* **Comprehensive Insights:** Covers real-time hourly metrics, up to 7 days of future predictions, and historical weather data for the past week.
* **Dynamic API Integration:** Built using Power Query (M code) optimized with relative paths to handle dynamic web sources without breaking the cloud scheduled refresh.
* **Analytical Structure:** Data modeled and formatted efficiently to ensure seamless rendering of temperatures, wind speed, and humidity tracking.

## Technologies Used
* **Power BI Desktop & Power BI Service** (Report design and cloud scheduling)
* **Power Query / M Language** (Data extraction, transformation, and API handling)
* **WeatherAPI** (External weather data source)

## How It Works
The semantic model issues parameters for each city using the fixed domain server address coupled with query conditions. Once refreshed on the Power BI server, the updated dashboard seamlessly pushes changes to the embedded web environment.
