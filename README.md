# Airbnb-Interactive-Visualization
Code in gh-pages Branch: https://github.com/angieniu/Airbnb-Interactive-Visualization/tree/gh-pages

Demo: https://angieniu.github.io/Airbnb-Interactive-Visualization/

Seattle Airbnb Rental Analysis

Group Members: Yanjie Niu, Wenxian Fei, Tianxin Song, Wei Wang, Xiaohua Shi

## Dataset and Main Question
We used JavaScript, D3, and Tableau, to work on the Airbnb dataset and answer the question:
From the perspective of hosts who want to develop business with multi B&Bs in Seattle, how to help them decide locations, prices and minimum/maximum days, in order to optimize their listing strategy and get higher revenue.

## Dataset Description
The dataset used in this project comes from Inside Airbnb, an independent, non-commercial set of tools and data that allows you to explore how Airbnb is being used in cities around the world. This dataset contains information about airbnb housing rental list, covering geographic data (geojson), housing type, price as well as ratings.
This project will be focusing on the housing in Seattle, which is closer to our actual
requirements. Besides, it provides the GeoJson data for projecting the geographic data.
Data attribute: {id, name, host_id, host_name, neighbourhood_group, neighbourhood,
room_type, price, minimum_nights, number_of_reviews, review_per_month,
avalibility_365}

## Audience Analysis
  Host Expectations from visualizing this dataset
· Price range
· Popular locations
· Popular room types
· Strategy to set listing rules (minimum night etc.)

## Specific Questions to Explore
1. How many B&Bs in each of the neighborhood?

   a. Display numbers of different room types in each neighbourhood/neighbourhood group by histogram.
   
2. What are the prices of B&Bs in Seattle distributed by neighborhood?

   a. Price range displayed by box-and-whisker plot.
   
   b. The map displaying the housing price by neighborhoods, which assists people to locate the neighborhood they can afford. This chart       can be controlled by filter (housing type, rating scores, review number per month). When users’ mouses are over the map, the tooltips will display certain neighborhood’s median price and neighborhood name.
      
3. What type of airbnb is most cost-efficient (lowest $/person)?

   a. Tableau visualization about the average cost per person for different types of airbnb(1b1b, 2b2b…)
   
4. What is the relationship between neighbourhood and reviews per month? In history and in future.

   a. Regression line and trend line to reflect both what has happened and what will happen.
   
5. How many guests/reviewers choose certain same listings for more than one time? And how many guests/reviewers choose listings 
   different than before?
   
   a. Bar chart to make the comparison.
   
6. Is there any relationship between minimum nights and availability in 365 days? Are short-term B&Bs more popular?

   a. Scatter plot and regression line showing the relationship between minimum nights and availability in 365 days
   
7. Which neighborhoods/neighborhood groups have more popular B&Bs?

   a. B&Bs will be represented by dots on the map, the less availability in 365 days is, the deeper color the dots are. Can be filtered       by room type. Tooltips will show the room types, prices, neighborhoods/neighborhood groups.
