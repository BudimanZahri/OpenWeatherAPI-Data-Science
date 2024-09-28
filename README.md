# Weather Data Analysis using OpenWeatherMap API

## Project Overview

This Python project retrieves and analyzes weather data from various cities using the OpenWeatherMap API. It demonstrates how to interact with a public API, process JSON data, store it in CSV format, and analyze the weather patterns across different cities. The project includes data analysis techniques such as calculating average temperatures, finding cities with extreme temperatures, and identifying common weather patterns. Additionally, visualizations are generated using Seaborn and Matplotlib to display the temperature distribution in different cities.

## Features

- Fetch weather data (temperature, humidity, weather conditions, wind speed) from OpenWeatherMap for multiple cities.
- Store the data in a structured format (CSV).
- Perform data analysis using **Pandas** and **NumPy**:
  - Calculate the average temperature across cities.
  - Identify the city with the highest and lowest temperatures.
  - Determine the most common weather condition.
- Visualize temperature data across cities using **Seaborn** and **Matplotlib**.
  
## Technologies Used

- **Python** for scripting
- **OpenWeatherMap API** for fetching real-time weather data
- **Requests** for making API calls
- **Pandas** for data manipulation
- **NumPy** for numerical analysis
- **Matplotlib** and **Seaborn** for data visualization

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/weather-data-analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install requests pandas numpy matplotlib seaborn
    ```
3. Create an `api_key.py` file with your OpenWeatherMap API key:
    ```python
    API_KEY = 'your_openweathermap_api_key'
    ```
4. Run the script:
    ```bash
    python weather_analysis.py
    ```

## Data Analysis

- **Average Temperature:** Calculates the average temperature across all cities.
- **Highest and Lowest Temperatures:** Identifies which city has the highest and lowest temperatures.
- **Common Weather Patterns:** Determines the most frequent weather condition across the cities.

## License

This project is licensed under the MIT License.
