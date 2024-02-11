# Analyzing-Wildfire-Activities-in-Australia

**Description**

This is IBM Python for Data Visualization Course Practice Project. This include two parts.
- Part 1 : Analyzing the wildfire activities in Australia
- Part 2 : Dashboard to display charts based on selected Region and Year

**Purpose**

To analyze and visualize the wildfire activities in Australia, explore patterns and trends and create visualizations to gain insights into the behavior of wildfires in different regions of Australia.

To create dashboards using Dash and Plotly, the dashboard will display the following two charts: 
1. Pie Chart on Monthly Average Estimated Fire Area
2. Bar Chart on Monthly Average Count of Pixels for Perfumed Vegetation Fires

**Data Description**

This wildfire dataset contains data on fire activities in Australia starting from 2005. Additional information can be found here.
The dataset includes the following variables:

- Region: the 7 regions
- Date: in UTC and provide the data for 24 hours ahead
- Estimated_fire_area: daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for a each region in km2
- Mean_estimated_fire_brightness: daily mean (by flagged fire pixels(=count)) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin
- Mean_estimated_fire_radiative_power: daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts
- Mean_confidence: daily mean of confidence for presumed vegetation fires with a confidence level > 75%
- Std_confidence: standard deviation of estimated fire radiative power in megawatts
- Var_confidence: Variance of estimated fire radiative power in megawatts
- Count: daily numbers of pixels for presumed vegetation fires with a confidence level of larger than 75% for a given region
- Replaced: Indicates with an Y whether the data has been replaced with standard quality data when they are available (usually with a 2-3 month lag). Replaced data has a slightly higher quality in terms of locations

**Source**

https://www.coursera.org/learn/python-for-data-visualization/home/welcome

**Dashboard**

![Screenshot (399)](https://github.com/thantthirimaung/Analyzing-Wildfire-Activities-in-Australia/assets/125528949/eadb98cf-8c41-4256-9fbe-49d6ce86a2f1)
