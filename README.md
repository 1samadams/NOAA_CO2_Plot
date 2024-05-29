Create an interactive CO2 visualization with options to switch between different time scales (hourly, daily, monthly, and yearly). 

This will allow us to create interactive plots that users can explore.

Fetches data from NOAA's FTP server, parses it, and creates an interactive plot with plotly.

Overview:
Fetch Data: downloads the data from the NOAA FTP server.
Parse Data: data is parsed into a list and then converted into a pandas DataFrame.
Create Visualization: Use plotly library is used to create an interactive line plot of daily CO2 levels. 
                      The plot includes a range slider and buttons to switch between different time scales (monthly, yearly, etc.).
