# Late-Night Cafes in Manhattan

## Goal
I aimed to find the cafes and coffee shops that are open after 10pm in NYC. This project is for people like me who work late at night and are always searching for alternative workspaces.

## My Findings
I found 47 cafes in Manhattan that are considered "late-night". They are all open past 10pm, with 8 of them being open 24 hours. A large percentage of the late-night cafes are located downtown in West Village and East Village, while only one late-night cafe is located in Harlem.
 
## Data Collection
I used the Foursquare API to extract data on cafes in NYC. I filtered the search to match the conditions I was looking for, including the name of the cafe, the hours, and the availability of wifi. (https://location.foursquare.com/developer/reference/place-search)

## Data Analysis

After receiving my search results through the Foursquare API, I created a list of dictionaries for the cafe name, hours, and the latitude and longitude cooridinates. I saved this list into a dataframe and then created a CSV file. I used "if" statements to see which cafes were open 24 hours and which cafes had available wifi.

## Skills

I refined my skills in creating lists and dataframes and I learned how to use DataWrapper.

## My Original Plan/Difficulties
I originally wanted to track which cafes closed down during the pandemic, but the API would not provide me with that information. I tried to use the "date_closed" and "date_created" feature in my search, but this did not yield any results.  Many of the restaurants' hours were also not updated since before COVID. It was harder to find information on cafes post-COVID. 

Another obstacle is that Foursquare limits results to only 50 places, so I was only able to plot up to 50 places on the map. Foursquare also does not have information on every establishment in NYC.

Many cafes are listed as "bars", as they are coffee bars during the day and cocktail bars at night. I did not have the time to go into the data and discern which are actually cafes and which are cocktail bars. I limited my search to just "cafes" and "coffee shops"; however, many restaurants and delis were categorized as "cafes" when they are not considered a typical cafe.

I wish my map was prettier and more neat, but I tried!