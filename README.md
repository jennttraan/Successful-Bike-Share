
# How Does A Bike Share Navigate Success?
<br>
![Untitled design](https://github.com/jennttraan/Successful-Bike-Share/assets/144400508/d156e2d8-89a3-4de4-91e5-81ea6a27478f)

<br>
### Background scenario

I am a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members.

### About the company

In 2016, Cyclistic launched a successful bike-share company. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, The director of marketing believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, she believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

## The goal of this case study

Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?

2. Why would casual riders buy Cyclistic annual memberships?

3. How can Cyclistic use digital media to influence casual riders to become members?

<b>In this assignment, I will produce a report with the following deliverables:</b>

1.  clear statement of the business task

2. A description of all data sources used

3. Documentation of any cleaning or manipulation of data

4. A summary of my analysis

5. Supporting visualizations and key findings


### Business Task

In order to maximize the number of annual membership, I, the data analyst, will find trends and patterns among casual riders and membership riders, and identify potential riders who benefit from annual membership.

### About The Data Set

Since Cyclistic is a fictional company, I will use Divvy’s, a bike-share program based in Chicago, data from May 2020 – April 2021 to complete this case study. For the dataset please click <a href="http://divvy-tripdata.s3.amazonaws.com/index.html">here</a>.

## Processing And Analyzing The Data

Complete R analysis can be found <a href="https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/blob/main/R%20Analysis">here</a> and <a href="https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/blob/main/R%20Cleaning">here</a>.
<br>
I calculated ride durations based on start and end times. Filtered out excessively long or short rides. Ensured data accuracy and reliability. Summarized statistics for ride length.I also broke down the customer types (annual members vs. casual riders). Calculated total rides and ride durations by customer type. Determined ride length patterns by day of the week and month. Found differences in ride behavior between customer types.

## Visualizations

![TotalRides_Vs_WeekDays](https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/assets/144400508/666555ff-b95c-4abf-b2ce-df856a6f1a06)


![AverageRideLen_Vs_WeekDays](https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/assets/144400508/28fd7063-e182-41bc-9300-85260a85c5a9)

Casual riders ride more on the weekends. Members ride more on the week days.

![TotalRiders_Vs_BikeType](https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/assets/144400508/1d794ab6-7832-4ea4-8759-4f87528f480e)

Classic bikes are more popular overall.

![AvgRideLength_Vs_Month](https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/assets/144400508/4e84bc91-c974-49dd-a61e-55a72d7858ff)


![TotalRides_Vs_Month](https://github.com/jennttraan/How-does-a-bike-share-navigate-success-/assets/144400508/c1004494-4af9-41d9-86fb-61ea1c04d536)


Generally, the most popular months are during the Spring and Summer. The weather is probably better during these months.


## In Conclusion

<b>Based on the analysis, the following recommendations are made:</b>

Increase marketing efforts targeting leisure riders on weekends and in the summer.
Encourage annual members to use bikes more regularly throughout the week.
Evaluate the popularity of docked bikes and consider improvements.
Focus on improving classic bike fleet.
Consider offering longer rental periods for casual riders.
Increase marketing efforts during winter months.
