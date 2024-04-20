**VacationPy Overview**

VacationPy leverages Python and visual mapping techniques to plan vacations based on weather conditions. This project builds on the WeatherPy data, using Jupyter Notebooks, geoViews, and Geoapify API for mapping and hotel search.
Project Setup
Tools and Libraries

Jupyter Notebooks
geoViews Python Library
Geoapify API

Steps to Run the Project

Data Preparation: Load the city_data_df from the CSV file. Filter the data for ideal weather conditions (e.g., temperature, wind speed, cloudiness). Please note that you will have to supply your own api key in an api_keys file for the api to work. 
Hotel Data: Create hotel_df to store city, country, coordinates, and humidity. Use Geoapify API to find hotels within 10,000 meters.
Map Visualization: Use geoViews to plot each city on the map, sizing points by humidity.
Enhance Map with Hotel Info: Add hotel names and country to the hover message on the map.

Final Deliverable

A Jupyter Notebook (VacationPy.ipynb) with all code, visualizations, and explanations.
Contributing

Feel free to fork the repository for customization or contributions.
Acknowledgements

Geoapify API
geoViews
