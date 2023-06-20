The provided Python code is developed to extract data from the Federal Reserve Economic Data (FRED) regarding Bachelor's or Higher degree education in the United States, specifically at the state and county levels. The code generates data based on the current date and is available up until the year 2021. It utilizes the FRED API to extract the latest data whenever it is run in the future.
This code is useful for research purposes, particularly for conducting comparative analyses involving educational and economic indicators. There are two distinct CSV files associated with this code. One file contains information on the percentage of Bachelor's or Higher degree holders among residents of all USA states, while the other file provides data on states, counties, and municipalities throughout the entire USA.
The extraction process involves applying different criteria, including content filtering (such as title, frequency, seasonal adjustment, and unit) and collaborative filtering based on item similarity. For the first CSV file, the algorithm extracts data for each state in the USA and assigns corresponding state names to the respective FRED codes using a loop. Similarly, for the second CSV file, data is extracted based on a given query, encompassing USA states, counties, and municipalities.
To extract the data provided in the attachment, various criteria were applied:
Content Filtering: The data was filtered based on several attributes, including the title, frequency, seasonal adjustment, and unit. This filtering process ensured that only relevant data meeting the specified criteria was included.
Collaborative Filtering: Another filtering technique used was collaborative filtering, which relies on item similarity. This approach involves finding data items that are similar or related to the given query. By leveraging this method, the algorithm identifies and extracts data based on similarities between items.
In the algorithm, the focus is on identifying all states based on the provided search query. The data extraction process begins by retrieving information specific to USA states. A loop is then used to assign state names to the respective codes assigned by FRED, facilitating easier data handling and analysis.
A similar approach is applied to the second CSV file. Here, the algorithm extracts data based on the provided query, encompassing USA states, counties, and municipalities. The extracted data includes all items that match the search query, enabling comprehensive data collection for the specified regions
Visit For Details:
Visit For Details:
Full Repository: https://github.com/Saadaziz1985/Fred-API-Bachelor-s-or-Higher-Degree-Data/
Data Gathered From: 
https://fred.stlouisfed.org/searchresults/?st=Bachelor%27s%20Degree%20or%20Higher%20for
https://fred.stlouisfed.org/searchresults/?st=Bachelor%27s%20Degree%20or%20Higher
Algorithm Applied: https://github.com/Saadaziz1985/Fred-API-Bachelor-s-or-Higher-Degree-Data/blob/main/Dataset%20for%20Bachelor's%20Degree%20or%20Higher%20for%20USA%20States%20%26%20Counties.ipynb
Output files:
https://github.com/Saadaziz1985/Fred-API-Bachelor-s-or-Higher-Degree-Data/blob/main/Bachelor's%20Degree%20or%20Higher%20for%20States%20%26%20Counties.csv
https://github.com/Saadaziz1985/Fred-API-Bachelor-s-or-Higher-Degree-Data/blob/main/Bachelor's%20Degree%20or%20Higher%20for%20USA%20States.csv
