# Analyzing COVID-19 Preparedness and Risk Factors Across the U.S.

## Business Question
Placeholder copy


## Python Visualizations and Insights
All data from provided [Business Analytics GitHub repository](https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis "COVID-19 Case Python Data Analysis Respository").

[Link to .ipynb file](https://drive.google.com/file/d/1vVlLRpT2Fv4mGToSR4xMI9btd_sS1wGQ/view?usp=sharing "Bowerman_Python1.ipynb").

### Age Distribution by County
![](Images/us_counties_highest_over60.html)

![](Images/us_counties_highest_pct_over60.html)

These bar graphs show the twenty US counties with the highest number of residents 60 years or older and the highest percentage of residents 60 years or older, respectively. These graphs could help identify which counties may have the higher at-risk population, both in raw numbers and proportionally, for COVID-19 cases or deaths, assuming age is one of the most significant factors in suspectibility to the disease.

Interestingly, there is no crossover between the top 20 counties with the largest 60+ population and the top 20 with the highest percentage of 60+ residents. This may be a potential complication in decisions to distribute COVID-19 relief materials and funds: Which counties are more likely to be overwhelmed by cases? Those with more residents over 60 or those with a largest percentage of their residents over 60?

### BUBBLE GRAPH EXAMPLE:
![](Images/us_counties_hospitals_v_beds_deaths.html)

I created this visualization to see if there was any strong correlation between the number of hospitals (x-axis), hospital beds per 1000 people (y-axis), and COVID-19 deaths per 1000 people (size of bubble) . The very strong relationship between hospitals and hospital beds is evident. However, there doesn't seem to be an especially strong relationship between number of deaths and hospital beds, as supported by the correlation heatmap (Deaths per 1000 people has a correlation of 0.12 with hospital beds per 1000 people and of 0.09 with number of hospitals). This relationship, or lack thereof, is even more evident when you zoom in on the data, as seen below. There do appear to be more deaths in counties with more hospitals, most likely due simply to greater population in those counties.

![](Images/hospitals_v_beds_deaths_zoom.PNG)

### Correlation Heatmap
A correlation I thought was interesting was the 0.93 correlation between Number of Hospitals and Number of Hospital Beds, indicating, I think, that most hospitals across the country have a similar number of beds. This is makes me wonder if all hospitals have a similar capacity for beds and are currently at capacity, assuming that they don't have much, if any, room for more beds. If these are fair assumptions to make, that means that US hospitals could potentially all reach capacity at the same time, meaning we may see a severe peak in deaths if hospitals all have to begin turning people away at the same time.
