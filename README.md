# Glasstire DataHack

**TL;DR** - A competition hosted to draw insights and visualizations about the Houston art scene. Team was able to conduct great EDA about the Houston art to highlight major art scene trends.   

[**Link to Visualization / Presentation**](https://public.tableau.com/profile/huy.bui#!/vizhome/BaysianBoyz/EventsAnalysis)  
[**Results from the Competition**](https://glasstire.com/2019/10/13/announcing-the-winners-of-the-2019-glasstire-datahack/)  

## Context 
Glasstire is the oldest online-only art magazine in the country publishing articles and reviews on all Texas based art venues and events since 2001. Basically they are a living-breathing digital record of the Texas visual art community.

Thus, they have a lot of data on all Texas-based art venues and events that has recently happen. In **Glasstire DataHack**, they hope to share this dataset and have competitors develop unique and fascinating visualizations and insights about the visual art community to inspire new ways to relect on this great art community. 

## Our Project Summary
We did some data manipulation and cleaning in Python utilizing Pandas but the primary work of creating the visualizations was developed on Tableau. We chose to utilize Tableau as there is endless possiblities with interactivity between the user and the data.

[**Link to Visualization / Presentation**](https://public.tableau.com/profile/huy.bui#!/vizhome/BaysianBoyz/EventsAnalysis)

### Main Findings
1) **Event Concentration by Zipcode** - geospatial mapping of all art venues grouped by zipcode. We can see most all venues are concentrated in the center of the city in the Museum District area. There are some unique scattering of venues such those in Galveston. 
2) **Number of Events per Year** - From 2007 to 2012, there has been a huge growth in the number of art events for Houston. After 2012, there is a more stable number of events and the art scene is still going strong.   (Note: 2019 count is incomplete)  
3) **Number of Events per Month** -  Most events happen in the month of March and September while August and December had to the least. We found out later from the panel that is correct as there are two major seasons spring and fall events. Holiday season is slow. 
4) **Number of Events by Venue** - this visualization shows the count of how many events an art venue host and the coloring signify the location of the art venue. From this we see a good amount of events are hosted in the Museum District and primarily at the Museum of Fine Arts (MFAH) but the Houston visual art community has a plentora of events at local venues as well.  
5) **Artist Activity** - this visualization shows the count of events that an artist participated in through one year. The coloring indicated which year that worked in. In addition, if you click on an artist bar you get the information on their favorite venue to display their work and you have ability to filter out the time range with a slider. 

From this visualization we see that there seems to be a very sporadic activity of artists where we see artists come and go after several years. Artists appear onto the art scene strong and then host less events over time. However there is some artist with consistent showing such as Emily Sloan.

### Supplemental Visualizations
We attempt to map the locations of art venue against population income to see if there was a trend between concentration of art venues to general populace wealth of an area. Even though art concentrated areas have good value such as the Museum District we found there was additional factors incluenced the population income of an area so nothing profoundly conclusive could be formulated from these graphs.

However, in creating this visualization we did make a visual appealing plots :).

[**Venue to Income Tract Plot**](https://public.tableau.com/profile/patrick.m.ly#!/vizhome/GlassTire-VenuesbyIncomeTract/Sheet4)    
[**Venue to Population Income Plot**](https://public.tableau.com/profile/patrick.m.ly#!/vizhome/GlassTire-VenueLocationsbyPopulation/Sheet2)  

## Last Words
Exploring the dataset of the Houston visual art community brought up some interesting insights and it is great to see that the Houston art scene flourshing.

## Authors
**Team: βαλesΙαη βθγs** 
 - **Huy Bui** - lead 
 - **Matt Danielson** - team member
 - **Ali Rasheed** - team member
 - **Patrick Ly** - team member
 
 Advisor on supplemental geospatial visualization: **Edward Yuen**


