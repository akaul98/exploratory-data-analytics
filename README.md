This is an Exploratory data analytics  of  sales of footlocker on the month of February 2021.

Step 1: Load the data

Step 2: Deal with the missing values
                i)  If the number of null values is more than 50% Drop that columns
                ii) If null value is int/float fill the data by mean of that columns
                iii)If null value is object/category fill the data by mode of that columns
                iv) Convert the data into its appropriate data types
                
Step 3:Load the Geopy Library
              Geopy is a Python client for several popular geocoding web services.Geopy makes it easy for Python developers to locate the coordinates of addresses,               cities, countries, and landmarks across the globe using third-party geocoders and other data sources.
              
Step 4: Use the zipcode column to locate obtain the  latitude and longitude this is easily achievable with the help of step 3

Step 5: Load plotply to plot the models.
        Plotly is a Montreal based technical computing company involved in development of data analytics and visualisation tools such as Dash and Chart Studio. It           has also developed open source graphing Application Programming Interface (API) libraries for Python, R, MATLAB, Javascript and other computer programming           languages

Step 6: Now we will use this latitude and longitude to plot the points at different locations at which footlocker was sold with the help of step 5

Step 7: We would conculde it will top 5 states at which the most number of footlocker was sold
