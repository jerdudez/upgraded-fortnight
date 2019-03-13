
<b>1.	Introduction</b>

For many people, choosing the right area to live in can be a difficult decision. While buying a house or signing a rental lease are likely to be some of the biggest decisions in an individual’s life, such decisions are often made without enough knowledge of differences between the different housing areas in terms of restaurants, sports facilities available and so on. 

This project will as such focus on identifying and comparing the features of different neighbourhoods in Toronto, in terms of the restaurants and facilities that are within close proximity of each neighbourhood. The target audience for this project are to-be home owners and renters.

For example, a person who is into food and dining might want to live in an area where there are more nice restaurants. In the same vein, a sports enthusiast may prefer to live in an area where there are many different types of sporting facilities. 
Such comparisons are hard to conduct due to the impracticality of it – a person who wanted to physically scout every single housing area comparing the restaurants and facilities available would not quite have the time or energy required to do so.

Foursquare’s location data provides a good solution to this problem – by aggregating the different facilities in each housing area and comparing them across the board, a person deciding where to stay can evaluate which areas may be more suitable for him or her, and hence make better housing purchases or rental decisions. 

<b>2.	Data</b>

The main data required for this analysis is data pertaining to neighbourhoods in Toronto. We will first scrap the list of neighbourhoods in Toronto from Wikipedia at this page:

https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Next, we will use the Foursquare API to call for venues that are within the vicinity of each neighbourhood. This will give us the names and category of venues and facilities within surround each neighbourhood. These categories will be further grouped into key categories such as dining, entertainment, sports etc., which will be used in the ultimate summary, analysis and clustering of neighbourhoods.

