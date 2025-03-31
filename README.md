# Weather and Vacation Analysis Project  

This project analyzes the relationship between weather variables and latitude using the OpenWeatherMap API. It also includes a vacation planning component that identifies ideal travel destinations based on weather conditions and locates nearby hotels using the Geoapify API.  

## How to Run  
1. Clone the repository and navigate to the project directory.  
2. Install the required dependencies:  

    ```bash
    pip install requests matplotlib pandas scipy geopandas
    ```  

3. Run the Jupyter Notebook to generate weather analysis plots and maps.  
4. View the outputs, including scatter plots, regression analysis, and vacation destination maps.  

## Features  

### **Weather Data Analysis** 
The `Weather.py` file demonstrates the following:

- Retrieved weather data for a set of randomly generated cities.  
- Created scatter plots to visualize relationships between latitude and:  
  - Temperature  
  - Humidity  
  - Cloudiness  
  - Wind Speed  
- Performed linear regression analysis for each weather variable in both the Northern and Southern Hemispheres. 

### Vacation Planning  
The `VacationPy` file demonstrates the following: 

- Mapped city locations using weather data.  
- Filtered cities to find ideal travel destinations based on preferred weather conditions.  
- Used the Geoapify API to locate the nearest hotel within 10 km of each selected city.  
- Created an interactive map displaying city locations, hotels, and country details.  

## References  
This project contains generated data from edX bootcamp  
