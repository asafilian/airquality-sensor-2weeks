# Analysis of Sensors Data for Airquality
The `SL132001-data (11).csv` file represents the data for the week of `26/05/2020`, and the `SL132001-data (12).csv` file represents the data for the week of `02/06/2020`. The data is gathered every single minute. Let's call this original dataset, minutely dataset.  

The number of observations in the data is **19,744**. It contains sensor readings for each single minute during the these two weeks. The features of the data are as follow:
- `Ozone - Low Conc.` (opm)
- `Hydrogen Sulfide - Low Conc.` (ppm)
- `Total VOCs (ppm) - PID` (ppm)
- `Carbon Dioxide - Low Conc.` (ppm)
- `Particulate Matter 1` (ug/m3)
- `Particulate Matter 2.5` (ug/m3)
- `Particulate Matter 10` (ug/m3)
- `Temperature (Internal)` (C)
- `Humidity (Internal)` (%)
- `Temperature (External)` (C)
- `Humidity (External)` (%)

I resampled the hourly and daily data from the minutely dataset and analyzed them as well. The datasets can be found in the Data folder.

In this project, I have addressed the following main problems: 
1. An Exploratory Analysis of the Data
2. Anomaly Detection

Please find the following Notebooks:

1. Gettin and Cleaning Data.ipynb
2. Exploratory Data Analysis.ipynb
3. Anomaly Detection.ipynb

Moreover, more complete reports about the datasets (minutely, hourly, daily) can be found in the Reports folder in html format.
