# IBM-Data-Science-Capstone-Project

## Identify A Strategic Location to Open a Brazilian take away restaurant in London, United Kingdom

Marcello Dichiera
Capstone Project

## 1. Introduction
### 1.1 Background

 The success of establishing a new restaurant depends on several factors: demand, brand loyalty, quality of food, competition, and so on. In most cases, a restaurant's location plays an essential determinant for its success. Hence, it is advantageous and of utmost importance to determine the most strategic location for establishment in order to maximize business profits. 
Whether you’re opening your first full-service restaurant, it’s important to understand what to look out for when choosing a new restaurant location. For seasoned restaurateurs, you may have a successful location where you are but how much of that success is inadvertently down to accidental—or purposeful—restaurant location choice? The answer may be it has everything to do with it. 
### 1.2 Problem Statement
- Brazilian family of chefs would like to open a Brazilian take away restaurants, selling Brazilian traditional food such as pizza katupiri', pastels, picanha in London.
-Objective is to identify the optimal neighborhood location to open. key factors to consider are: spending power of the London population, distribution of Brazilian ethnic group, competition, trafficked areas.
- To identify the right London neighborhood, we are going to use Foursquare API, data scraping, geopy, scikit learn for the clustering model building and matplotlib/seaborn to visualize data during our EDA (Exploratory Data Analysis)
### 1.3 Key Clients
- Brazilian Family of chefs, highly experienced in cooking for small to medium restaurants
## 2. Data Acquisition, Wrangling and Cleaning
### 2.1 Data Sources
The neighbourhoods alongside their respective postal codes, boroughs and the geographical coordinates, population and income for each neighborhood will be scraped from here: https://www.doogal.co.uk/UKPostcodesCSV.ashx?area=London0 . 
For returning the number of Brazialian restaurants in the vicinity of each neighbourhood, we will be utilizing Foursquare API, more specifically, its explore function. 
After cleaning, and apply exploratory analysis we will create a London map through Folium with an overview of the location of each neighborhood. From there we will implement some data preprocessing (feature scaling with standard scaler) to prepare the data for the clustering KMeans model to identify the neighborhood cluster with more potential to open a Brazilian restaurant.
### 2.2 Data Cleaning
## Next step

## 3. Exploratory Data Analysis
### 3.1 Folium Mapping

### 3.2 Frequency Distribution of Brazilian Restaurants
### 3.3 Distribution of Median Household Income

## 4. Clustering Modeling 
### 4.1 Data Pre-processing
### 4.2 k-Means Clustering unsupervised model
### 4.2.1 Cluster Labels
## 5. Conclusions
