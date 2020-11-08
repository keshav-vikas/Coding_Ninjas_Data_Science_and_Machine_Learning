## Project Details
###                                                 Zomato API - I
#### For this project, I am using the Zomato API.  
Zomato APIs give you access to the freshest and most exhaustive information for over 1.5 million restaurants across 10,000 cities globally.  
Zomato API documentation link : https://developers.zomato.com/api   
#### Our Motivation for using Zomato API
By Collecting the data using Zomato API one can recommend restaurants on the basis of user’s affinity to specific cuisines, establishment types, locations, and price bands.  
We can find out whether restaurant support online reservation or not.  
We can find what is the most popular and/ or exclusive/new at a given location & time.  

#### Zomato cuisine problem details
Mexican cuisine began about 9,000 years ago, when agricultural communities such as the Maya formed, domesticating maize, creating the standard process of corn nixtamalization, and
establishing their foodways.  
You are a huge fan of ‘Mexican’ cuisine. Now using the Zomato API you want to analyse the best restaurant serving the Mexican Cuisine, their locations, and cost for two, etc.  

#### Zomato restaurant Problem Detail
"Pa Pa Ya" is a modern Asian bistro & tapas bar from the House of Massive Restaurants and best described as a chic, modern and radical reinterpretation of Asian cuisine.  
You have heard from your friends that restaurant "Pa Pa Ya" in Delhi is quite good. So now you want to extract the information related to "Pa Pa Ya" using Zomato API.  

#### Zomato Distance Problem
Distance is also a very important factor while selecting a restaurant. Suppose you are at Coding Ninjas and you want to select the restaurant which is near to you using Zomato API.
Note down the latitude and longitude of Coding Ninjas using Google Maps  

### Zomato API - II
#### Zomato Dataset Details
#### Dataset Collection -
Data has been collected from the Zomato API in the form of .json files(raw data) using the following url and stored in CSV file -  
https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20  

#### Details of zomato.csv -

Restaurant Id : Unique id of every restaurant across various cities of the world  
Restaurant Name : Name of the restaurant  
Country Code : Country in which restaurant is located  
City : City in which restaurant is located  
Address : Address of the restaurant  
Locality : Location in the city  
Locality Verbose : Detailed description of the locality  
Longitude : Longitude coordinate of the restaurant's location  
Latitude : Latitude coordinate of the restaurant's location  
Cuisines : Cuisines offered by the restaurant  
Average Cost for two : Cost for two people in different currencies  
Currency : Currency of the country  
Has Table booking : yes/no  
Has Online delivery : yes/ no  
Is delivering : yes/ no  
Switch to order menu : yes/no  
Price range : range of price of food  
Aggregate Rating : Average rating out of 5  
Rating color : depending upon the average rating color  
Rating text : text on the basis of rating of rating  
Votes : Number of ratings casted by people  


#### Country Codes :
 
Country Code    Country  

1     --          India

14    --         Australia

30    --           Brazil

37    --          Canada

94    --          Indonesia

148   --         New Zealand

162   --          Phillipines

166   --         Qatar

184   --         Singapore

189   --          South Africa

191   --           Sri Lanka

208   --           Turkey

214   --         UAE

215   --        United Kingdom

216   --         United States
