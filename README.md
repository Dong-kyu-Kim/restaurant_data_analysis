# Restaurant Data Analysis
restaurant data analysis

Dataset: https://www.kaggle.com/datasets/anthonytherrien/restaurant-revenue-prediction-dataset/data 

Since there were 8368 data in each column of this data file, when classifying data, data were classified by restaurant location and by cooking in each country using population instead of sample data.

Since the classification was made using the population, this analysis provides various advantages such as increased accuracy, reduced variability, secured representativeness, reduced need for estimation, increased accuracy of decision making, and better predictive models. 

Restaurant Analysis PPT file: [restaurant_data_analysis.pdf](https://github.com/user-attachments/files/16476956/restaurant_data_analysis.pdf)

Presentation Record: [Presentation Record.pdf](https://github.com/user-attachments/files/16477883/Presentation.Record.pdf)

# Observations and Analysis 1

![Screenshot 2024-08-05 200957](https://github.com/user-attachments/assets/e0ada083-8a77-4b1e-9949-bbdf93cd09d1)
![avg_weekend_weekday_line_comparison](https://github.com/user-attachments/assets/c02e6fd0-05a4-4093-936a-2cddc41a69c9)        

Key Observations:

  - Midweek bookings for Indian cuisine are the highest at 30.209642, and weekend bookings are also high at 29.733382.

  - Weekday bookings for Japanese dishes are the lowest at 27.842262, and weekend bookings are also the lowest at 28.534970.

  - Weekend reservations are evenly distributed between 28.5 and 30.0 for all dishes.

  - Weekend reservations generally do not vary much by type of dish, but it is unusual that Indian dishes are noticeably high and Japanese dishes are low in weekday reservations.

  - Comparing the difference between weekday and weekend reservations, if weekday reservations are higher or lower than weekend reservations, it depends on the type of dish. Indian dishes have higher weekday reservations than weekend reservations, and Japanese dishes have     the opposite.

# Observations and Analysis 2

![weekend_revenue_scatter](https://github.com/user-attachments/assets/26dacc2b-0e78-408c-b06b-3b2389c0d41f)

Key Observations:

  - For every additional weekend reservation, revenue increases by approximately $3,904.63. This indicates a positive and direct impact of weekend reservations on revenue. 

  - When there are zero weekend reservations, the predicted baseline revenue is approximately $540,916.18.

  - The scatter plot and linear regression analysis reveal a positive relationship between weekend reservations and revenue. While the model provides a useful trend for predicting revenue based on reservations, the variability in the data suggests the influence of other     factors.

# Observations and Analysis 3

![Screenshot 2024-08-05 211134](https://github.com/user-attachments/assets/e074232e-8d2a-444c-9282-43b04e5633bb)

Key Observations:

  - The data points (in blue) are tightly clustered around the regression line, indicating a strong linear relationship between the marketing budget and social media followers.

  - The positive slope of the line confirms that as the marketing budget increases, the number of social media followers also increases.

  - For every additional unit increase in the marketing budget, the number of social media followers increases by approximately 10.08. This suggests a direct and proportional impact of the marketing budget on gaining followers.

  - When the marketing budget is zero, the predicted number of social media followers is 3746.14. This represents the baseline number of followers without any marketing expenditure.

  - Scatter plot and linear regression analysis allow a clear and quantifiable understanding of the strong correlation between marketing budgets and social media followers.

# Observations and Analysis 4

![Screenshot 2024-08-05 205330](https://github.com/user-attachments/assets/e8a8c5e1-8941-494c-8ac8-4c4280fb5c10)
![avg_revenue_bar_comparison](https://github.com/user-attachments/assets/50af49aa-8a69-4081-bef0-8b4e042f1694)

Key Observations:

  - When analyzing the relationship between the number of reservations and profits, Japanese cuisine has the highest revenue despite its relatively low number of reservations. This may suggest that Japanese cuisine has a high unit price.

  - On the other hand, Indian cuisine has a high number of reservations, but its revenue is relatively low. This suggests that the unit price is likely to be low.

  - French cuisine also has an average number of reservations, but it indicates that the unit price is high due to high profits.

  - Mexican cuisine is on the lower end, both in terms of reservation and revenue.

# Observations and Analysis 5

![Screenshot 2024-08-05 210035](https://github.com/user-attachments/assets/8745a522-3b84-441a-ae2f-18cae0206e8b)
![Screenshot 2024-08-05 211329](https://github.com/user-attachments/assets/15c770c6-0392-4185-b912-fa831eb80de7)

Key Observations:

  - The downtown area has a much higher average culinary return compared to other locations. This may be a result of reflecting the high population density and economic level of the downtown area.

  - Suburban areas are lower than urban areas, but they earn higher profits than rural areas. Because suburbs have many residential areas and various populations, profits appear to be moderate.

  - The lowest returns in rural areas may be due to relatively low population densities and less economic activity.

  - With this data, we can understand the differences in culinary revenue for each location, which can provide important information for restaurant operations and location selection. 
