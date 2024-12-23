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

![image](https://github.com/user-attachments/assets/85d04843-7bde-4cbb-a85e-0b9b0afb22c1)



Steps:

Check for null values in all datasets.

Replace missing values in the Rating column with the rounded mean.

Standardize column names for consistency. 

![image](https://github.com/user-attachments/assets/4b58f439-29c5-4ec1-91f8-b50460354934)



Merging Datasets

All three datasets were merged using the User ID column as the primary key.


![image](https://github.com/user-attachments/assets/4279b597-a8c7-4977-af0c-c422708611d7)



Analyzing Cooking Sessions and Orders

Steps:

Group by User ID to calculate total cooking sessions and total orders per user.


Identifying Popular Dishes

Steps:

Group data by Dish Name and count the number of unique users who ordered each dish.

Create a bar plot to visualize the most popular dishes.

![image](https://github.com/user-attachments/assets/38a133b8-fe89-4f08-926b-b1471388fd8d)


Exploring Demographic Factors

Steps:

Analyze age groups, locations, and favorite meals to uncover behavioral trends.

Create visualizations for age distributions and meal preferences.

Visualizing Cooking Duration by Dish Name and Favorite Meal

Steps:

Plot cooking duration for each dish, segmented by Favorite Meal.

Visualizations

To enhance aesthetics, background styles were applied to visualizations using seaborn themes and matplotlib options.

![image](https://github.com/user-attachments/assets/fd34913c-9020-43d4-9941-4c62e9d67f6e)

Report:

![image](https://github.com/user-attachments/assets/2909f1b7-24cc-425b-962c-155872f01830)

Recommendation:
![image](https://github.com/user-attachments/assets/44d1c982-6848-4e59-9413-3058f84b3dec)





