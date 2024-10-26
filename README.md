# Weather Data Collection Project

## Overview
This project collects real-time weather data from all U.S. state capitals using the **OpenWeatherMap API**. The data is refreshed every 30 seconds and saved into an Excel file for easy access and further analysis. I have used my Google Drive to store the live data excel file into it. Then I connected the live excel file to the Tableau dashboard and created a sheet to present USA map with weather. 

The project fetches key weather metrics, such as temperature, humidity, wind speed, and weather conditions.

## Features
- **Real-time Weather Data Collection**: Collects weather data from the OpenWeatherMap API for all U.S. state capitals.
- **Data Storage**: Weather data is saved in an Excel file that includes temperature, humidity, wind speed, weather condition, and a timestamp for each entry.
- **Continuous Updates**: The data is updated and appended to the Excel file every 30 seconds.

## Prerequisites

Before running the project, ensure you have the following:

- **Python 3.x**
- The following Python libraries installed:
  - `requests`: Used to fetch weather data from the OpenWeatherMap API.
  - `pandas`: Used for organizing and manipulating the weather data into a DataFrame.
  - `openpyxl`: Used to save the data into an Excel file.

## Results

### Live Data in Tableau

Below is a screenshot of the live data being fed into Tableau directly from the Excel file stored in Google Drive:

![Live Data in Tableau](Results/Live%20Data.png)

### Tableau USA Weather Map

Here is a screenshot showing the weather conditions across U.S. state capitals, visualized in Tableau:

![Tableau USA Weather Map](Results/Live%20Weather%20Dashboard.png)


## Further Improvement

I can run the same Python file in AWS Lambda and automate it to pull weather updates every 30 seconds, so I don't have to run it on Colab.



