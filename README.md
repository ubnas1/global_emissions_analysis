# Global Emission (2000-2020)

 As global warming becomes worse, by analysing this dataset I have made visualizations of each countries' contribution in emissions of CO2.
 
 
 ## Result
 ---------
 
 
 ## Top contributing countries
 
 In year 2020, top contributing countries were China, USA, India, Brazil, Indonesia
 
 ![image](https://github.com/ubnas1/global_emmisions_analysis/assets/116352196/9c696d83-ea65-4ad4-a8c7-d43602e074ca)
 
 
 ## Total emissions of selected country
 
 User can also see a line-chart of any country's emissions per year by selecting the country's name from the dropdown menu. 
 
 ![image](https://github.com/ubnas1/global_emmisions_analysis/assets/116352196/03cab151-1c2c-4340-83dc-4c23d90d64c5)
 
 
 ## Map View
 
 Two map views have been provided where user can hover the pointer over any country and it will show the information of that country and its emissions.
 The color changes with respect to the amount of CO2 emissions.
 
 ![image](https://github.com/ubnas1/global_emmisions_analysis/assets/116352196/8c9a7eb2-093f-4247-b6e9-6f06a7e17f77)

 
 ![image](https://github.com/ubnas1/global_emmisions_analysis/assets/116352196/d2d8dbfd-d1f4-427b-b3d8-83987ea38720)
 
## Data Source

* https://www.kaggle.com/datasets/justin2028/total-emissions-per-country-2000-2020

## Dependencies:
1) Database : SQLite
2) Python 3.9 for Flask (API) 
3) JavaScript library : D3, plotly.js, chart.js, Leaflet.js


## Instructions: 

1) SQLite Database creation
  
  Used database_creation.ipynb to create database

2) Route to Interactive Dashboard

  Execute app_flask.py from the root of the repository

     ```sh 
    python3 app_flask.py
    ```

* API :

    http://127.0.0.1:5000/api/v1.0/emissions
    http://127.0.0.1:5000/api/polygons
    http://127.0.0.1:5000/api/countries

   
