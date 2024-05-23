# Hotel Aggregator Analysis 
![image](https://github.com/Mahmoudabuelfadl25/Mentorness-Hotel-Aggregator-Analysis/assets/150693366/3af93b02-37db-4c01-a42f-10461476155e)


# Objective

Our primary objective in this project is to delve deep into the intricate dynamics of the hotel industry using the powerful data visualization and business intelligence tool, Microsoft Power BI. We aim to harness the capabilities of Power BI to transform raw data into meaningful insights, thereby enabling us to understand the complex interplay of various factors in this sector.
Our analysis will not be limited to merely identifying patterns and trends. We aspire to go beyond the surface-level observations and unravel the underlying mechanisms that drive these patterns. By doing so, we hope to gain a comprehensive understanding of the sector’s dynamics.

----------------------------------------------------------------------------

# Questions To Answer : 

Which city has the highest number of hotels listed?

Are there specific regions that lack sufficient hotel listings?

What is the average price per night for hotels in different cities?

How do prices fluctuate based on the time of year (seasonality)?

How does the size or capacity of the hotel (number of rooms) impact the rating?

How do occupancy rates vary across different cities or regions.

How do the prices, ratings, and occupancy rates compare across different types of properties?

---------------------------------------------------------------------

# Processing 

Our journey begins with the crucial step of data cleaning. In the vast ocean of data, not all information is useful or relevant. We first removed columns with all null values, as they do not contribute any meaningful information. 

We also eliminated unnecessary columns such as neighbourhood_group_cleansed, bathrooms, Calendar_updated, License, and name. These columns either contained redundant information or were not relevant to our analysis.

We also tackled the issue of duplicate columns like minimum_minimum_nights and minimum_maximum_nights. Having duplicate information can lead to confusion and inaccuracies in our analysis.

Next, we embarked on the task of data transformation. We renamed some columns for clarity and ease of understanding. For instance, bedrooms became num_of_Bedrooms, Calendar_Last_Scraped became Last_Scraped_date, number_of_reviews_ltm became Last Year Reviews, number_of_reviews_l30d became Monthly_Reviews, and so on.

We also split the host_locality column into host_country and host_cities. This allowed us to separate country and city information, making it easier to analyze geographical trends.

In the data imputation phase, we replaced all null values with 0. This ensured that our data was complete and ready for analysis. We also transformed certain columns like Available, instant_bookable, host_has_profile_pic, and host_is_superhost from ‘t’ and ‘f’ values to True and False respectively. This made the data more consistent and easier to interpret.

 We replaced all null values with 0. This ensured that our data was complete and ready for analysis. We also transformed certain columns like Available, instant_bookable, host_has_profile_pic, and host_is_superhost from ‘t’ and ‘f’ values to True and False respectively. This made the data more consistent and easier to interpret.

With our data cleaned, transformed, and imputed, we moved on to the exciting phase of data analysis. We found that Melbourne had the most rooms, followed by Southbank, South Yara, Carlton, and Richmond. This gave us an insight into the geographical distribution of rooms.

------------------------------------------------------------------

# Insights & Conclusion


Our analysis revealed a variety of interesting insights. For instance, we found that the highest-rated hosts varied each year from 2014 to 2023, with Madcomfy earning the highest rating of all years at 4.81. This showed us the importance of maintaining high-quality service in the hotel industry.
We also discovered that hotel rooms, despite being the least common, had the highest prices overall. This was particularly true from 2019 to 2023. This could be due to a variety of factors, such as increased demand or higher operating costs.
Through this project, we’ve gained valuable insights into the hotel industry. We’ve uncovered the factors that influence room availability, pricing, and ratings. We hope these findings will be useful for both businesses and customers in making informed decisions.

------------------------------------------------------------------

# Recommendations 

Geographical Distribution: Since Melbourne has the most rooms, it might be beneficial to focus marketing efforts in this area. However, don’t neglect areas like Southbank, South Yara, Carlton, and Richmond as they also have a significant number of rooms.

Quality of Service: The success of  Madcomfy, with the highest rating of 4.81, underscores the importance of high-quality service. Hotels should invest in training their staff and maintaining their facilities to ensure customer satisfaction.

Room Types and Pricing: Despite being the least common, hotel rooms had the highest prices overall. This suggests that there is a market for high-end, luxury accommodations. Hotels could consider adding more such rooms to their inventory. However, they should also conduct market research to understand the reasons behind this trend, such as increased demand or higher operating costs.

Yearly Trends: The data shows that the highest-rated hosts and room prices varied each year. It’s important for businesses to stay updated with these trends and adjust their strategies accordingly.






