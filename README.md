# Exploratory Data Analysis (EDA) of Capital Bikeshare

![Capital Bikeshare](capital_bikeshare.jpg)

This repository contains an Exploratory Data Analysis (EDA) of the Capital Bikeshare dataset. The analysis aims to gain insights into bike usage patterns, user behavior, and other relevant information to understand the dynamics of the Capital Bikeshare system.

## Introduction

Capital Bikeshare is a bike-sharing service that operates in [Washington, D.C.](https://www.capitalbikeshare.com/), offering a convenient and eco-friendly transportation option for residents and visitors. This EDA uses Python and various data visualization techniques to explore the dataset and extract meaningful information.

## Data

The Capital Bikeshare dataset used for this EDA can be obtained from [Capital Bikeshare's official website](https://www.capitalbikeshare.com/system-data). The dataset includes the following information:

- **datetime**: Datetime of each record.
- **season**: season encoded as a number.
- **holiday**: whether it was a holiday or not.
- **workingday**: whether it was a working day or not.
- **weather**: encoded as one of the categories:
    1. Clear, Few clouds, Partly cloudy, Partly cloudy
    2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog.
- **temp**: measured temperature in Celsius.
- **atemp**: actual temperature in Celsius.
- **humidity**: humidity.
- **windspeed**: wind speed.
- **casual**: number of non-registered user rentals initiated.
- **registered**: number of registered user rentals initiated.
- **count**: number of bikes rented in total.
  
## Files

- `notebook/`: Jupyter Notebooks containing the Python code for the exploratory data analysis.
- `data/`: This folder contains the dataset files in CSV format, which will be used for the analysis.

## Usage

To perform the EDA of Capital Bikeshare:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/Capital-Bikeshare-EDA.git
   ```

2. Place the dataset file (`dc_bikes.csv`) inside the `data/` folder.

3. Install the required Python libraries by running:

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels
   ```

4. Open the Jupyter Notebook folder `notebook/` and using Jupyter or JupyterLab and execute the cells to perform the exploratory data analysis.

## Analysis Insights

The Jupyter Notebook `capital_bikeshare_eda.ipynb` includes an in-depth exploratory analysis of the Capital Bikeshare dataset. Some of the insights obtained from the analysis are:

- Usage patterns of Capital Bikeshare bikes throughout the day, week, and year.
- Trip duration distribution and outliers.
- Weather and user behavior, including peaks and off-season.
- Seasonal trends and their impact on bike usage.

## Contribution

Contributions to this project are welcome. If you have ideas for additional analyses, improved visualizations, or general enhancements, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and analysis results as per the terms of the license.


I hope you find the Exploratory Data Analysis of Capital Bikeshare informative and insightful! Thank you for visiting the repository.
