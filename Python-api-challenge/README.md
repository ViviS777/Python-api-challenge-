# Weather and Vacation Planning Project

This project is a weather and vacation planning application that utilizes several APIs to gather and analyze weather data and identify potential vacation destinations.

## Project Overview

The project consists of two main components:

1. **WeatherPy**: This Jupyter Notebook performs the following tasks:
   - Retrieves weather data for a large number of cities around the world using the OpenWeatherMap API.
   - Analyzes the weather data and generates various visualizations and insights.

2. **VacationPy**: This Jupyter Notebook builds on the weather data from the previous notebook and performs the following tasks:
   - Identifies the best cities for vacation based on certain weather criteria.
   - Uses the Geoapify API to find hotels in the selected vacation cities.
   - Generates a heatmap to visualize the hotel locations.

## API Keys

The project requires two API keys:

1. **OpenWeatherMap API Key**: This key is used to retrieve weather data for the cities.
2. **Geoapify API Key**: This key is used to retrieve hotel information for the selected vacation cities.

The API keys are stored in the `api_keys.py` file, which is excluded from the Git repository using the `.gitignore` file.

## Getting Started

1. Clone the repository to your local machine.
2. Install the required dependencies, such as `pandas`, `hvplot`, and `requests`.
3. Obtain your own API keys from OpenWeatherMap and Geoapify, and update the `api_keys.py` file with your keys.
4. Open the `WeatherPy.ipynb` and `VacationPy.ipynb` files in Jupyter Notebook and run the cells to generate the weather analysis and vacation planning results.

## Project Files

- `api_keys.py`: Contains the API keys for OpenWeatherMap and Geoapify.
- `WeatherPy.ipynb`: Jupyter Notebook for the weather data analysis.
- `VacationPy.ipynb`: Jupyter Notebook for the vacation planning.

## Contributions

Contributions to this project are welcome. If you have any suggestions, bug fixes, or additional features you would like to add, please feel free to submit a pull request.