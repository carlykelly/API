# API
In order to run WeatherPy.ipynb you will need to enter your open weather API key and google API Key in the document api_keys_sample.py. You will also want to change the name of this document to api_keys.py

`WeatherPy.ipynb` uses Open Weather API to find weather information about several hundred randomly selected latitude and logitude coordinates. Matplotlib is then used to graph the relationships between several weather factors. These graphs are saved as png files. The weather information is saved as a csv to be used in `VacationPy.ipynb`.

In order to run `VacationPy.ipynb` you must first run `WeatherPy.ipynb`

`VacationPy.ipynb` reads in the csv that was created in `WeatherPy.ipynb`. It then uses this infomation to filter out details based on your preferred temperatures and humidity for vacation. Next the Google Maps AIP is used to find the closest hotels to the remaining latitude and logitude coordinates. Finally a heat map is created based on the humidity of your remaining latitude and longitude coordinates and places the hotels on the map as well.

The project in this folder was an assignment completed for The George Washington University Data Analysis and Visualization Bootcamp.