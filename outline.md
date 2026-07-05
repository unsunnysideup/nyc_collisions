# Collisons in NYC (2012 - 2026)
This project places emphasis on wrangling big messy data and interactive visualizations while simultaneously improving my skills in storytelling and analysis. 

## Dataset
The data is sourced from NYPD on [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data). It has over 2 million reported crash incidents with over $1000 loss in damages from 2012 to 2026. The data comprises of 29 variables comprising the following categories:
1. Time
2. Date
3. Location
4. Reason
5. Casualties
6. Vehicle Type Involved

## Objectives
My goals for this project is to create an interactive dashboard in Shiny R to allow users to explore trends and patterns of vehicular collisions happening in the five boroughs of NYC from 2012 to 2026. I plan to include the following in my dashboard:
1. Chloropleth Map (Leaflet): Collisions Frequency
2. Tree Map (Plotly): Casualties Breakdowns
3. Line Plots (Plotly): Collision Timeline 
4. Bar Charts (Plotly): Reasons behind collisions
5. Table Explorer (DT Table)


### Customization by User Preference 
1. By Time (Ideally: Animation)
2. By Borough
3. By Neighborhood
4. Side by Side Comparisons

### Specs:
Three tabs:
1. Collisions in New York City:  
    A. What does the page contain?  
        - Chloropleth  
        - Bar Chart  
        - Tree Maps  
        - Line Plots  
    B. Customization:  
        - Time  

2. Data Explorer  
    A. What does the page contain?  
        - Bar Chart  
        - Tree Map  
        - Line Plots  
    B. Customization:  
        - Time  
        - Borough  
        - Neighborhood  
        - Side by Side Comparison  

3. Data Table   
    A. What does the page contain?  
        - Data Table  
    B. Customization:  
        - Filters in dropdowns Corresponding to what User wants  





