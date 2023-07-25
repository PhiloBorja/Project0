---
title: "Seattle Airbnb Analysis"
date: 2023-03-26
---

  ![image](https://github.com/PhiloBorja/Project1/assets/129383661/9016271d-0cec-481a-b63a-52c5c79fa33a)
  


# Introduction
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.
The following Airbnb activity is included in this Seattle dataset:

•	Listings, including full descriptions and average review score

•	Calendar, including listing id and the price and availability for that day

In This Project, we answer 3 questions:

1.	The busiest month in terms of availbility of listing
	
2.	The highest mean price per night of listings
	
3.	The most expensive in terms of 'accomodate'

There are a wide variety of points of view to analyze the data. We can base it on different points such as the price, the name of the host, its score, the number of reviews of the ad, etc.
But in our case, I think that the most representative for this dataset are the points that we will see below:

# Part I: What is the busiest month?

In this chart I was interested in knowing which is the month in which the occupancy is highest. To do this, we assign 1 to occupied accommodations and 0 to those that are not. Therefore, when performing the average, the values close to one will be those with the highest occupancy and those closest to zero will be those with the lowest occupancy.
The months with the highest availability correspond to the months of Christmas (November and December). January is the month with the lowest availability followed by the summer months (July and August). We can see that from summer time, the availlabity increase.

![image](https://github.com/PhiloBorja/Project1/assets/129383661/ebdc3973-5407-4924-a26c-0e0c01df6d30)

 
# Part II: What is the highest mean price per night of listings?

In this chart I was interested in knowing which is the mean price per night and month and the highest of them. To do this, we sum the price of the accommodations per month and divide by the total of this accommodations. 

The highest average price per night, we find it in the summer months (June, July and August), which coincide with those with less availability.

![image](https://github.com/PhiloBorja/Project1/assets/129383661/bfb9bd68-3ff5-477b-8f3a-543864c473c6)

![image](https://github.com/PhiloBorja/Project1/assets/129383661/43584b70-a369-4a90-8e9f-d408401a0260)

 
# Part III: What is the most expensive in terms of 'accomodate'?

In this chart I was interested in knowing which is the most expensive accomodations in terms of  the number of pax. To do this, we obtain the mean price of the accommodations per pax. 

The average price per accommodates, we can see that between 1-7 pax, the relationship is direct. But from there no, being 11 pax the highest average price, that is more high than a 16 pax accommodation

![image](https://github.com/PhiloBorja/Project1/assets/129383661/48e18f0a-ff7e-4e04-b314-e68ff32f0037)
 
# Conclusion

In this article, we took a look at how to do a analysis based on different situation and different conditions with the Seattle AirBnB database.

1.	The months with the lowest availability correspond to the month with the lowest availability followed by the summer months (July and August)

2.	The highest average price per night, we find it in the summer months (June, July and August), which coincide with those with less availability. It makes sense, since the lower the offer, the higher the price

3.	11 pax is the accommodations with the highest average price.
