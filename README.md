# CitiBike sharing in NYC 
Module 15 Tableau Challenge

Link to Data Story and Vizzes: https://public.tableau.com/app/profile/emprr/viz/NYCBikeShare_Story_Final/Story1

## Overview of Project
To show visually the relationships between the soft Starts and Stops of rental hours, subscribed riders vs non, and a breakdown of bike rentals by gender for the downtown area of NYC. It will be "used to predict and plan a similar ridesharing network in Des Moines" (for "RP'ing the challenge purposes").

### Purpose
The purpose of this module and challenge are to get an initial look at Tableau and its inner workings. We learned how to import data and create relationships within that data, how to create "vizzes" based on that import, and how to create a story to pull all of it together. The lessons provided an overview of what Tableau can be used for, its major benefits, and how it may be used in a corporate or similar analytic setting to make a feed of data (in this case millions of lines long) digestible and easy to follow and sort depending on the kind of information required. It feels like a distant cousin of Sequel, but instead of writing the queries by hand, the information is attained via drag-and-drop of the identified categories within a .csv file.

## Results

The visualizations created provide an immediate estimate of a few key factors.

<img width="1344" alt="1" src="https://user-images.githubusercontent.com/116296092/219983154-cb4d0629-52a5-4ae3-b599-b7f7edb05ebb.png">

Clearly shown here, the male population of riders provides the backbone of rentals in NYC. There is a staggering difference between the male and female populations, and moreso with the undefined. There are a few reasons this may be the case, societal or otherwise, but we aren't here to speculate on that. As shown in the partner chart (as with all heatmaps, the darker the color, the higher the concentration):

<img width="359" alt="2" src="https://user-images.githubusercontent.com/116296092/219983167-fc0cdf98-8d00-490c-bee6-1ccc9cf6617c.png">

The majority of the riders - as a whole - are subscribed. Supported by the data above, it holds that a high percentage of the male riders are subscibed to the CitiBike service. 

<img width="652" alt="3" src="https://user-images.githubusercontent.com/116296092/219983173-c1692383-b2fb-4d5f-86ef-202bccff75c3.png">

Considering the "Undefined" gender category among unsubscribed riders, it is likely these in particular are one-off accts that simply did not take the time to finish filling out the sign-up and/or liability form. Accounts that are used once or only as needed and irregularly. This conclusion was drawn from the fact there is a vastly higher number of Undefined, Unsubscribed riders than there are Undefined, Subscribed riders. Riders that are subscribed and Undefined may find more engagement if there were more gender options upon account creation, and may increase the company's image as a whole.

<img width="1511" alt="4" src="https://user-images.githubusercontent.com/116296092/219983177-5504de76-44da-44c4-8b48-d26928a6e837.png">

Male riders tend to rent the bikes during the workweek, unsurprisingly during the hours of 0600 through 0900. The concentration drops off in the middle of the day (with a slight increase going into the weekend), and then picks back up from 1600 hours through 2000. Explained easily, this confirms the bikes are most popular as individuals are traveling out to and back home from work. NYC being as saturated with CitiBike access points (pickup and dropoffs) as it is, this also explains the first visual's claim that the most rides are roughly 5-10 minutes long. Below, further reinforcement that the bikes are the most popular during the start and end hours of a workday, with an interesting gap midweek on Wednesday.

<img width="520" alt="5" src="https://user-images.githubusercontent.com/116296092/219983183-6eafa282-f03b-4029-9896-60d3e7a31c8b.png">

The last visualization, below, shows further proof that the highest concentration of rides across all genders at the selected times is roughly 5-7 minutes long. Given the concentration of pickup and dropoff points across the city, this is not surprising as most customers are likely using it along a route they would normally walk, but are now conserving energy and time.

<img width="1329" alt="6" src="https://user-images.githubusercontent.com/116296092/219983191-9e2535d0-5b14-4612-b057-225855d35df1.png">

## Summary

Overall, the bike service seems to be performing very well. Subscribers are high, rides are available when necessary at peak hours, and with expansion into a new city planned, things are running smoothly. While a majority of the information presented covers the core of the business, additional visualizations could be made to help support the success of CitiBike. For instance, earlier reference was made to the concentration of pickup and dropoff points. While not immediately necessary to show, they were created internally to better understand why ride durations are as short as they are. In the event that the Des Moines expansion needs further backing, the locations in NYC could easily be added to the story as proof that more access to the service's services increases rider engagement and encourages the use of the bikes on a routine basis. Like the Disneyland garbage can philosophy, if there's one nearby then a customer will be far more likely to use it than default to something else (in this case leaving open market share).
