# Upliance-AI
Determining information from the given dataset

User Behavior Analysis 

This project analyzes datasets related to user behavior, cooking preferences, and order trends to derive actionable business insights. Below is a step-by-step explanation of how the analysis was performed and visualized, along with instructions for replicating the results. 

Objective

The objective of this analysis is to:

Clean and merge datasets: UserDetails, CookingSessions, and OrderDetails.

Analyze the relationship between cooking sessions and user orders.

Identify popular dishes based on user orders.

Explore demographic factors influencing user behavior.

Visualize insights and provide business recommendations.


Dataset Preparation

Datasets:

UserDetails: Contains demographic and account information.

CookingSessions: Tracks user cooking activity.

OrderDetails: Logs order history and ratings.


Steps:

Check for null values in all datasets.

Replace missing values in the Rating column with the rounded mean.

Standardize column names for consistency.


Merging Datasets

All three datasets were merged using the User ID column as the primary key


Analyzing Cooking Sessions and Orders

Steps:

Group by User ID to calculate total cooking sessions and total orders per user.


Identifying Popular Dishes

Steps:

Group data by Dish Name and count the number of unique users who ordered each dish.

Create a bar plot to visualize the most popular dishes.

Exploring Demographic Factors

Steps:

Analyze age groups, locations, and favorite meals to uncover behavioral trends.

Create visualizations for age distributions and meal preferences.

Visualizing Cooking Duration by Dish Name and Favorite Meal

Steps:

Plot cooking duration for each dish, segmented by Favorite Meal.

Visualizations

To enhance aesthetics, background styles were applied to visualizations using seaborn themes and matplotlib options.




