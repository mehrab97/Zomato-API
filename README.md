# Zomato-API

For this project, we are using the Zomato API.
Zomato APIs give you access to the freshest and most exhaustive information for over 1.5 million restaurants across 10,000 cities globally.
Zomato API documentation link-https://developers.zomato.com/api 
Our Motivation for using Zomato API
By Collecting the data using Zomato API one can recommend restaurants on the basis of user’s affinity to specific cuisines, establishment types, locations, and price bands.
We can find out whether restaurant support online reservation or not.
We can find what is the most popular and/ or exclusive/new at a given location & time.

Project is divided into 2 parts

## Zomato API-I
### Zomato cuisine problem details
Mexican cuisine began about 9,000 years ago, when agricultural communities such as the Maya formed, domesticating maize, creating the standard process of corn nixtamalization, and establishing their foodways.
You are a huge fan of ‘Mexican’ cuisine. Now using the Zomato API you want to analyse the best restaurant serving the Mexican Cuisine, their locations, and cost for two, etc.
There is a list of questions related to Mexican cuisines
1. Fetch the cuisine_id of ‘Mexican’ cuisine using Zomato API.
Print the cuisine_id.
2. Fetch the entityid and entitytype of place Connaught Place.
Print the entityid and entitytype,
3. Fetch the top 10 best-rated restaurant serving ‘Mexican’ cuisine present in Connaught Place.
Print the restaurant name, user rating and restaurant id.
4. Fetch the category id of category type ‘Cafes’ using Zomato API.
Print the category_id.
5. Fetch the best-rated restaurant for ‘Mexican’ cuisine with category type ‘ Cafes’ present in Connaught Place using Zomato API.
Print the restaurant name, user rating and restaurant id.
6. Fetch the latest review of the best-rated restaurant for ‘Mexican’ cuisine with Category type ‘Cafes’ present in Connaught Place using Zomato API.
Print the name of user ,user rating and review text.

### Zomato restaurant Problem Detail
"Pa Pa Ya" is a modern Asian bistro & tapas bar from the House of Massive Restaurants and best described as a chic, modern and radical reinterpretation of Asian cuisine.
You have heard from your friends that restaurant "Pa Pa Ya" in Delhi is quite good. So now you want to extract the information related to "Pa Pa Ya" using Zomato API.
There is a list of questions related to the restaurant
1. Fetch the details of "Pa Pa Ya" restaurant using Zomato API.
Print the user rating, the average cost for two, cuisines and address of "Pa Pa Ya" restaurant.
2. Find out whether online table reservation is supported in "Pa Pa Ya" restaurant or not using Zomato API.
Print 'yes' if online table reservation is supported else 'no'
3. Fetch the latest review of "Pa Pa Ya" restaurant using Zomato API.
Print the name of the user, user rating and review text.

### Zomato Distance Problem
Distance is also a very important factor while selecting a restaurant. Suppose you are at Coding Ninjas and you want to select the restaurant which is near to you using Zomato API.
Note down the latitude and longitude of Coding Ninjas using Google Maps
There is a list of questions related to restaurant

1. Fetch the cuisine_id of of cuisine ‘BBQ’ using Zomato API.
Print the cuisine_id
2. Fetch the list of the top 10 restaurants serving cuisine ‘BBQ’ which are nearest to Coding Ninjas.
Print the restaurant name, user rating, restaurant id and locality in which restaurant is present.
3. Fetch the latest review of the restaurant serving cuisine ‘BBQ’ which is most nearest to Coding ninjas?
Print the name of user ,user rating and review text.
4. Experiment with the radius parameter that is present in ‘GET/search’. Fetch the list of top 10 best-restaurant present in a radius of 4 km of coding ninjas.
Print the restaurant name, user rating, restaurant id and locality in which restaurant is present.
5. Compare the location of the restaurant whether really they are in a distance of 4 km to Coding Ninjas. Find out whether these API radius feature is working or not.
Print 'yes' if radius feature work else print 'no'.

## Zomato API-II
The problem statements were as below-

Consider only Indian restaurants in this analysis -
1. The dataset is highly skewed toward the cities included in Delhi-NCR. So, we will summarise all the other cities in Rest of India while those in New Delhi, Ghaziabad, Noida, Gurgaon, Faridabad to Delhi-NCR. Doing this would make our analysis turn toward Delhi-NCR v Rest of India.
Plot the bar graph of number of restaurants present in Delhi NCR vs Rest of India.
Find the cuisines which are not present in restaurant of Delhi NCR but present in rest of India.Check using Zomato API whether this cuisines are actually not served in restaurants of Delhi-NCR or just it due to incomplete dataset.
Find the top 10 cuisines served by maximum number of restaurants in Delhi NCR and rest of India.
Write a short detailed analysis of how cuisine served is different from Delhi NCR to Rest of India. Plot the suitable graph to explain your inference.
2. User Rating of a restaurant plays a crucial role in selecting a restaurant or ordering the food from the restaurant.
Write a short detail analysis of how the rating is affected by restaurant due following features: Plot a suitable graph to explain your inference.
Number of Votes given Restaurant
Restaurant serving more number of cuisines.
Average Cost of Restaurant
Restaurant serving some specific cuisines.
Find the weighted restaurant rating of each locality and find out the top 10 localities with more weighted restaurant rating?
Weighted Restaurant Rating=Σ (number of votes * rating) / Σ (number of votes) .
3. Visualization
Plot the bar graph top 15 restaurants have a maximum number of outlets.
Plot the histogram of aggregate rating of restaurant( drop the unrated restaurant).
Plot the bar graph top 10 restaurants in the data with the highest number of votes.
Plot the pie graph of top 10 cuisines present in restaurants in the USA.
Plot the bubble graph of a number of Restaurants present in the city of India and keeping the weighted restaurant rating of the city in a bubble.


This project was done as a part of Data Science and Machine Learning course offered by Coding Ninjas.


