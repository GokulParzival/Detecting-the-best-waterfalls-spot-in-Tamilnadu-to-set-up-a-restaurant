# Coursera Capstone Project
To detect the best spot to set up a restaurant near waterfalls spot in TamilNadu.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Data](#data)
* [Machine Learning Algorithms Used](#machine-learning-algorithms-used)
* [Results](#results)

## General info
This project is about using Machine Learning algorithms to detect best spot for setting up a restuarant for near famous watefalls in Tamilnadu.
	
## Technologies
* Python
* Jupyter
* Foursquare API

## Data
The data regarding the names of the waterfalls has been taken from the [Wikipedia website](https://en.wikipedia.org/wiki/Category:Waterfalls_of_Tamil_Nadu) listed here. The data lacks the exact location of the waterfalls as well as the venues nearby. Hence these datas are acquired from the [Geocoder Package](https://pypi.org/project/geocoder/) in Python. The nearby venues are found using the [Foursquare API](https://foursquare.com/).

## Machine Learning Algorithms Used
* Kmeans clustering

## Results

From the above data analysis, we can predict that it would be a good decision if the restaurants are constructed in Cluster 3. Cluster 1 seems to be equipped with good hotels and restuarants nearby. On further analysis on Cluster 3, Cluster 2 and Cluster 1 we find that these Waterfalls have shortage of good hotels and restaurants nearby

* Courtallam
* Catherine Falls
* Thirparappu Falls
* Thirparappu
* Vaideki
* Siruvani Falls
