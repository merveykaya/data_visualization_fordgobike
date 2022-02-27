readme.md

# Communicate Data Findings : Ford GoBike Data

# Table of Contents
- Introduction
- Dataset
- Summary of Findings 
- Key Insights for Presentation

## Introduction

This is the final project(explanatory data visualization) of Udacity Nanodegree Data Analyst Program. 
It has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In Part I, I used Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. Also, In Part II, I produced a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying my findings is through transforming the exploratory visualizations from the first part into polished, explanatory visualizations.

## Dataset

I would like to use Ford GoBike dataset. According to Wiki/BayWheels, Bay Wheels is the first regional public bicycle sharing system in the U.S. that services more than just a single city or adjacent cities.On June 28, 2017, the system officially re-launched as Ford GoBike. Coinciding with the expansion and rebranding as Ford GoBike, several new programs such as integration with Clipper cards and a low-income pricing option were launched. Ford GoBike expanded electric bicycles by 250. In 2018, the Bay Wheels system reached around 10,000 annual subscribers, over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. However, in 2019 the system rebranded to Bay Wheels and dropped the Ford naming, with funding motivation of another company.

The data (201902) includes 183.412 rows and 16 columns which include both categorical and numeric features. It is in a csv format.

As my main interest, I focused on the customer informations because I was wondering which people mostly prefer renting a bike and how they can be classified because it is important to know the customer. Also, I indestigated the details of the trips. I believe that it is important to understand which stations most popular, how long do people rent a car and the attitude of the users about leaving bikes whether to the same station back or what is the route mostly used for a trip. These are all significant for pricing and profit side.

I created new variables for member_age and duration_minutes. Also, changed birth_years before 1939 as a null value, base year selected as 2019. Moreover, I tested the data coverage, the dataset looks pretty normal but also checked for the null values and cleaned them before start visualization. When visualize the duration_minutes, I changed the x-axis limit to get rid of the outlier's extension. 

## Summary of Findings 

Male proportion is about 71% while female proportion is approximately 22%. Males are using the system more than three times compared to females. Also, 89% of users are subscribers while only %10 of users are customers. The least usage is made by people over 70 years old. There is only one exception is that 18 years old people are in the group of least frequently users. On the other hand, the top five frequently users' ages are between 26 and 31.

Beside of these main variables I mentioned above, I investigate the duration times. I created a new variable as duration_minutes and focused on the average time period because of the extreme outleir that someone rent the bike for about 24 hours. On average, people rent less than a hour, so that the extreme outlier affects the distribution a lot. In the visualizing part, I just pretended where was no outlier to be able to see the distribution better. I also splitted datetime to week-days and hours. The statistics show that people are more renting bikes on Wednesday and in the peak hours.

There is no correlation between duration length and duration hour. Two peaks I observed on duration hours are significant for the usage duration of bikes. However, it can be said that people prefer to ride in longer durations after 13:00. Also, the relationship between customer type and duration length is non-monotanic. Subscriber tends to take shorter trips than customers. On the other hand, the findings show no relation between starting hour of duration and gender. Moreover, subscribers tend to rent bike in a more wide of range in a day, as starting to rent earlier. Furthermore, female tends to have longer minutes biking than males. Subscriber females have longer trips than customer females while customer females prefer to have less longer trips than customer males. The average of subscribers' ages are not significant for durations hour or duration length on gender in case they are customers or subscribers. Also, from the weekday comparison based on user type and duration length represents a trend for both customer males and females are more tend to ride longer on the Weekends.

## Key Insights for Presentation 

 I decided to present these key insights listed accordingly:

- When are most trips taken in weekdays?

- How long does the average trip take?

- What is the proportion of subscribers?

- What is the gender distribution for renting GoBikes?

- What age group rides bikes the most?

- Is there any relation between the day of trip and user type based on gender?

- Is there any relation between user type, duration length and the day of trip based on gender?

The reason why I chose these specific questions from the findings is that these visualizasions are good indicators for my main interests I mentioned in the dataset section above.
