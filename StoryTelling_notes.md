
# Udacity Project_Term2 (September 2018)
## Create a Tableau Story

### Dataset
United State flight delays and performance comes from from RITA http://stat-computing.org/dataexpo/2009/the-data.html
for 20 airlines and 304 airports.



### Task
Investigate the performance of flights and look at data for a given year in Tableau.


### 1. Summary

In this analysis I used TableauPublic to investigate a given dataset from RITA (http://stat-computing.org/dataexpo/2009/the-data.html) to analyze data for flights within the United States of America for the year 2008. The leading question here was "Which is the best day of the week and the best Airline to fly from San Francisco (SFO) to New York (JFK). "Best" means, that I wanted to avoid delays for Arrival and Departure as well as canceled or diverted flights. For the airlines I choose the five major U.S. Airlines (compared to google). 


### 2. Story - Best choice from east to west coast


This Tableau story is about flights within the U.S. in the year 2008 for two destinations, one on the east coast and one on the west coast. These are John F. Kennedy International Airport (JFK) in New York for the east coast and San Francisco International Airport (SFO) in San Francisco for the west coast. In the story I want to show the number of flights per day of the week and per month. There you can easily see on which weekday and in which month there are the most flights. I'm going to investigate further the delays for arrival and departure of flights for both airports, than going to see how many flights in 2008 were canceled or diverted. With these informations I can finally show which weekday(s) and Airline(s) from the 5 major airlines might be the best choice to fly from San Francisco International Airport (SFO) to John F. Kennedy International Airport (JFK).

### 3. Design

For my first visualization I choose line charts and bar charts to tell the story. I decided for color encodings for destinations and carrier names (airlines) for easily differnciate between those. 

Following is described my final visualization, where I choose line charts and bar charts again. For the first sketch I choose line-charts, because the distribution is for flights over a time period (weekday and year). I decided for a color encoding for the destinations to easily seperate the lines in the plot. The line charts here are also good to see the changing between the days and month, so you'll have a immediately impression on which day or in which month are more or less flights. You can also explore possibly different patterns between the destinations. In my second sketch I have line charts again with color encodings for the destination to see the delays in minutes for day of the week for JFK and SFO. For the third sketch I coose bar charts for the distribution of the arrival and departure delay in minutes. For the y-axis I added the carrier/ airline. Here I decided for 5 major airlines, so the plot is not overcrowed with information. Again I encoded the destinations with color and added the delayed minutes as numbers to the plot. In the fourth sketch I have a bar chart with color encoding for the number of canceled and diverted flights for the choosen destinations compared to the total number of flights. All totals you can easy see as numbers printed in the plot where the color encoding helps to visulize this. In the fifth sketch I have a bar chart for the on-time arrival and departure of flights per airline with color encoding for on-time performance and added percent for minimum and maximum. In the last sketch I choose a line chart to show the best airline and day of the week compared to delays, canceled and diverted flights. I highlighted the airline I would choose based on the data for 2008. 

For my final visualization I changed my sketches accordingly to the feedback I was given. I seperated my slides and added more sketches. There I choose color encoding including highlights, percent and total numbers, tooltips, calculated fields as well as adding a better storyline and descriptive axis.

After review I changed the settings to make size automatic. I also included a starting slide with a map as an overview. The concluding slide a changed just a little since the results are in there. I also changed the abbreviations to full airport names.  

### 4. Feedback

##### 1st feedback

* too many vizzes per slide
* story was not clear enough, should give an introduction first
* think about the order of the slides

##### 2nd feedback

* explain the story and the aim of the story in the beginning
* number of total are easier to understand
* highlight the bar, which I want to highlight in my story
* clear and consistent axis and title

##### Final feedback

* looks awesome


### 5. Links to Visualizations

##### Initial Version of Visualization
https://public.tableau.com/profile/katrin7722#!/vizhome/2008_StoryV1/Story1

##### Final Version of Visualization
https://public.tableau.com/profile/katrin7722#!/vizhome/2008_Story4_Final/Story3

### 6. List of Ressources

(1) evolytics.com
(2) doingdata.org
(3) tableau.com
(4) stackoverflow.com
(5) en.wikipedia.org
