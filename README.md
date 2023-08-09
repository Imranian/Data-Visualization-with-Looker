# Data Visualization Project
Data Visualization using **Looker** Software.
## Project Overview
### Description
This is a personal project for learning purpose. In this project, Looker software is used for the visualization of Data regarding Airports and Flights, i.e., **FAA**(Federal Aviation Administration). Looker is a cloud-based Business Intelligence (BI) tool that helps you explore, share, and visualize data that drive better business decisions. Looker is now a part of the Google Cloud Platform. It allows anyone in your business to analyze and find insights into your datasets quickly.
### Challenge scenario
- Which states and cities have the most airports with heliports?
- What is the facility type breakdown for the states with the most airports?
- What are the airports and states with the highest percentage of flight cancellations with over 10,000 flights?
- Where are the busiest, joint-use major airports that have control towers and what are their associated codes?
- What are the origin and destination airports with the smallest average distance between them?
## Implementation
### Task 1: Which states and cities have the most airports with heliports?
Look #1: Top 5 Cities With Most Heliports.
- A table with three columns: **City**, **State**, and **Airports Count**
- Limit the results (rows) to the top **5** states
- The Airports Count column should be in descending order (most to least)
- Filter for the Facility Type = **Heliports**

Result:

<p align="center">
    <img src="https://github.com/Imranian/Data-Visualization-with-Looker/blob/main/Top%205%20cities%20with%20most%20heliports.png">
</p>

### Task 2: What is the facility type breakdown for the states with the most airports?
Look #2: Facility Type Breakdown for Top 5 States.
- A table visualization with the **Airports Count**, **State**, and the corresponding **Facility Types**
- Limit the results (rows) to the top **5** states
- The Airports facility type column should be in descending order (most to least)
Note: You will need to use a Pivot.
- Facility Types Filter Should contain = **Airport**, **Balloonport**, **Gliderport**, **Heliport**, **Seaplane Base**, **Stolport** and **Ultralight**

Result:
Table containing data
<p align="center">
    <img src="https://github.com/Imranian/Data-Visualization-with-Looker/blob/main/2.%20Facility%20type/Top%205%20Facility%20type.png">
</p>
Visualization
<p align="center">
    <img src="https://github.com/Imranian/Data-Visualization-with-Looker/blob/main/2.%20Facility%20type/Top%205%20Facility%20type.png">
</p>
