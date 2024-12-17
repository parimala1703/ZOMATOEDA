
# Zomato EDA (Exploratory Data Analysis)

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Zomato restaurant dataset. The dataset contains comprehensive information about restaurants, including details like restaurant names, locations, cuisines, ratings, and more. The goal of this project is to extract meaningful insights from the data to understand trends in the food industry, particularly focusing on restaurant characteristics, cuisine popularity, and user ratings across India.

## Dataset Overview
The Zomato dataset used in this project consists of the following key columns:
- **Restaurant Name**: Name of the restaurant.
- **Location**: The city or area where the restaurant is located.
- **Cuisines**: Types of cuisines offered by the restaurant.
- **Average Cost for Two**: The average cost for two people at the restaurant.
- **Ratings**: User ratings (from 1 to 5) of the restaurant.
- **Votes**: The number of user votes received by the restaurant.
- **Timings**: The operational hours of the restaurant.
- **Restaurant ID**: Unique identifier for each restaurant.

## EDA Process
The Exploratory Data Analysis (EDA) process followed in this project includes:
1. **Data Cleaning**:
   - Identifying and handling missing values.
   - Removing duplicate records.
   - Checking for inconsistencies and outliers.

2. **Data Visualization**:
   - Creating visualizations such as bar charts, heatmaps, and histograms to better understand distributions and relationships within the dataset.
   - Exploring correlations between variables like ratings, cost, and cuisine type.
   
3. **Feature Engineering**:
   - Extracting meaningful features from the `Cuisines` column to understand the popularity of different cuisine types.
   - Grouping restaurants by city and analyzing restaurant density.

4. **Insights & Analysis**:
   - Identifying the most popular cuisines based on the number of restaurants.
   - Analyzing the relationship between restaurant ratings and cost.
   - Investigating restaurant distribution across cities in India and visualizing restaurant density.

## Key Findings
- **Top Cuisines**: The most common cuisines across the dataset were found to be North Indian, Chinese, and Continental, based on the number of restaurants offering them.
- **Rating vs. Cost**: There is a significant relationship between restaurant ratings and the average cost for two, with higher-rated restaurants often being more expensive.
- **City Distribution**: Major cities like Delhi, Mumbai, and Bangalore have the highest number of restaurants, making them the hotspots for the food industry in India.
- **Cuisine Preferences**: Different regions in India have preferences for certain types of cuisines, which were identified through visualizations and analysis.

## Libraries Used
- **pandas**: Data manipulation and cleaning.
- **matplotlib**: Data visualization.
- **seaborn**: Statistical data visualization.
- **numpy**: Numerical operations.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/parimala1703/ZomatoEDA.git
