# Exploring Third Places in Nashville
> This project aims to investigate the availability and distribution of third places—such as coffee shops, parks, and community centers—in Nashville, with an added focus on examining the relationship between neighborhood home values and income levels. Key objectives include the distribution and characteristics of third places across different neighborhoods and whether neighborhoods with higher home values and incomes have a larger number of these spaces. Additionally, I will assess how these home values and income levels have changed over a ten year period (2012-2022) to better understand their impact on the current availability of third places, particularly in the context of gentrification.

## Table of Contents
* [Motivation](#motivation)
* [Data Questions](#data-questions)
* [Sources and Tools](#technologies)
* [Setup](#setup)
* [Conclusions](#conclusions)
* [Dashboard Link](#dashboard-link)



## Motivation
- Growing up in Tennessee, I’ve witnessed firsthand the evolution of my childhood neighborhood in Chattanooga. As new developments have emerged these changes bring both positive and challenging impacts. On one hand, these new spaces offer exciting opportunities for socialization and community engagement, but on the other they have contributed to rising home values and living costs, which push out long-time residents who can no longer afford to stay in their neighborhoods. Ironically, many of these displaced individuals are unable to enjoy the very amenities that are transforming their communities. 
This personal experience sparked my interest in understanding how these dynamics are playing out more broadly across Nashville. With an increasing number of transplants moving to Tennessee and fueling local economic changes, it's important to explore how the availability and distribution of third places are influenced by gentrification. With my capstone, I aim to investigate the relationship between the current availability of third places and neighborhood home values and incomes. By analyzing data on home values, income levels, and the distribution of third places, I hope to provide insights into how economic changes are affecting access to these important spaces.


## Data Questions
What is the distribution and characteristics of third places across different neighborhoods in Nashville?
Is there an economic correlation between home values and the availability of third places?
Is there an economic correlation between average household income and the availability of third places?
How have income levels and home values changed over a ten year period (2012-2022)


## Sources and Tools
Yelp (business listings)
Nashville.gov (geospatial data)
Zillow (home values)  
American Community Survey (income levels)


Excel -- Income data from the ACS were in separate workbooks for each year and zip code 
Python/Pandas - for exploration and aggregation of the data
Tableau - for creating interactive dashboard


## Setup
First I downloaded the Yelp dataset that was in a Tar file. I had some trouble extracting the files from there, but Python was a great asset. From there I cleaned and prepared the data in Python. I followed a similar process with the Zillow and ACS data. The ACS data had to be cleaned in Excel first and then transferred to Python. After that working in Geospatial to create zip code/neighborhood boundaries was easier after having already worked with that file structure in class previously.


## Conclusions
• Both income levels and home values have experienced significant growth over the last decade. However, home values have increased at a significantly higher rate compared to income levels.
• Since the correlation with home value growth is weak, it might indicate that home values alone are not a strong driver of third place availability. Factors related to income and economic conditions may play a more significant role in the presence of third places.
• There is a notable correlation between areas with higher income growth rates and the number of third places. This may suggest that as neighborhoods become more affluent, they attract more businesses catering to varied social, recreational, and retail needs
• The positive correlation with income growth might reflect gentrification effects. As income levels rise, neighborhoods might see new businesses and amenities, including third places, contributing to the community’s transformation.
While higher-income areas tend to have more third places, the rapid rise in home values compared to income growth suggests economic and social dynamics that impact the availability and nature of these community spaces. Addressing these disparities could help in fostering a more balanced and inclusive development of third places across the city.


## Dashboard Link



