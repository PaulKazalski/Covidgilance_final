This folder contains files that aid in understanding the spread of the Coronavirus throughout the US. 

SVC_ML_Model2.ipynb utilizies a support vector machine learning model to fit converted categorical data into numeric data, 
to predict the daily total Coronavirus cases in the US.
Our model accuracy score was a 0.94.

The Visualization_of_COVID_statistics.ipynb file uses beautiful visualizations to monitor the spread of the Coronavirus in the US. 
It also uses fbprophet to predict the number of cases that will arise over a seven and fourteen day time span. 

The World Meters Scrape Notebook.ipynb utilizes the splinter library to webscrape worldmeters.com data, then convert this data into dataframes
and save these dataframes as csv files. We also used the opencage website and API to obtain the latitudes and longitudes of all Counties and 
States in the US.

Chromedrive and Driver files allow us to control web browsering applications to webscrape.  

An enriched version of this notebook can be found at the following 
link: https://nbviewer.jupyter.org/github/PaulKazalski/Covidgilance_final/blob/master/Covid-19/Visualization_of_COVID_statistics.ipynb