# python-api-challenge
In this project I use the open weather map api and the geoapify api to analyze how location affects weather and choose a nice vacation destination.
WeatherPy.ipynb contains the code to make api calls based on a list of cities then reads the response as a json and saves it as a pandas dataframe. Then I make some data visualizations and liner reggression to analyze the trends.
VacationPy.ipynb then uses the data collected in WeatherPy.ipynb to identify hotels to stay at given a set of weather restrictions.