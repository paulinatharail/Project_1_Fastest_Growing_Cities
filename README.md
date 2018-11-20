# Project_1_Fastest_Growing_Cities
Project1: Fastest growing cities in the US

Team Members: Francis Yu, Helen Zhou, Paulina Paul

Data folder: contains CSV files exported from Census API & after data cleaning/ filtering
    From Census API => census_2012.csv - census_2016.csv
    Data cleaning & Filtering => merge_city_pop_greater_than_200k.csv

Images Folder: Visualizations from the datasets
    - *_map.png => Visualizations on US map
    - *_bar.png => bar graph comparing population growth vs factors
    - LinRegres*.png => Linear regression
    - speed*.png => Speed of population growth vs factors for top 10 cities
    - population_Vs_*.png => Actual population numbers vs factors (actual numbers). We didn't use this set of visualizations.

Jupyter Notebooks:
    1) Census_API.ipnyb => Extracts 2012-2016 census API data and exports to CSV files 
    2) DataCleaning_maps_barCharts.ipynb => Data cleaning and visualizing 
    3) Population_Growth_Vs_Factors.ipynb => Generates visualizations of Top 10 cities
    4) Linear_Regression.ipynb => Linear regression 