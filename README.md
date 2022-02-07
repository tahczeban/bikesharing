# bikesharing
______________


***RESOURCES***


Data Source:201908-citibike-tripdata.csv, Citibike2

Software: Tableau Public, Anaconda/Pandas, Python, Jupyter, VSC


______________
***OVERVIEW***
______________
For complete Tableau story interactivity, please visit the following Citibike_Challenge link: 
[link to Citibike_Challenge](https://public.tableau.com/app/profile/tanya.czeban/viz/Citibike_Challenge_16441767677530/D3CitibikeStory?publish=yes "link to Citibike_Challenge")

<img width="1440" alt="Intro Generalized NYC Info" src="https://user-images.githubusercontent.com/90135381/152699136-f474c13a-86b3-4b80-a125-cbef2022af84.png">

                                 FIGURE 1: Dashboard of NYC Citibike Info

The purpose of this analysis was to research and present the Citibike bike-sharing business proposal visualizations in NYC to the stakeholders, in order to check the feasibility of implementing same in Des Moines, Iowa. In total there were 2,344,224 trips for the month of August in 2019. Average trip duration by age, bike utilization and top NYC starting and ending locations were depicted in the configured Dashboard above (FIGURE:1). Further Analysis was requested to include:
- the length of time the bikes are checked out for all riders and genders
- the number of bike trips for all riders and genders for each hour of each day of the week
- the number of bike trips for each type of user and gender for each day of the week
- additional visualizations were included at the end for gender subset totals, usertype and times of popularity

_______________________________________________________________
***RESULTS***
_______________________________________________________________
***DELIVERABLE 1: Change Trip Duration to a Datetime Format***


<img width="1440" alt="D1:Trip duration Time Change" src="https://user-images.githubusercontent.com/90135381/152699006-3a690f15-1d35-40f3-906d-b9290cbc0af3.png">

                            
                                  FIGURE 2: Pandas Trip Duration Time Change
                                  
Initial code was written in Pandas to convert the data from integer to datetime to obtain the hours, minutes and seconds for the trip durations (FIGURE: 2). This data was then exported as a CSV file to Tableau Public, in order to create the required trip analysis and subsequent visualizations for presentation via a new CSV file.



***DELIVERABLE 2: Visualizations for the Trip Analysis***

<img width="1440" alt="D2: Checkout Times for Users" src="https://user-images.githubusercontent.com/90135381/152699010-4a1cc073-f71b-4774-82bd-6d1c17e04e4e.png">


                                   FIGURE 3: Line Chart for Checkout Times for Users
                                   
In FIGURE: 3, the length of time the bikes were checked out for all of the riders was generated, illustrating that most of the times were under one hour for trip duration. 


<img width="1440" alt="D2:Checkout Times by Gender" src="https://user-images.githubusercontent.com/90135381/152699014-bbc8c905-d1ec-4fc2-ba69-7fdc91d929c6.png">

                                   FIGURE 4: Line Charts for Checkout Times by Gender

A further breakdown of data exhibited that males had significantly more checkouts than the other gender subsets, as well as longer checkout times (FIGURE: 4).

<img width="1440" alt="D2:Trips:Weekday Per Hour" src="https://user-images.githubusercontent.com/90135381/152699025-88502b9f-c841-4157-9c7a-cf9a6cb6bfeb.png">

                                  FIGURE 5: Heatmap of Trips by Weekday for Each Hour

The heatmap above visualizes the number of bike trips by weekday for each hour of the day (FIGURE: 5). This shows that Thursday has the most concentrated number of trips generally. The most popular times are between 6-10AM, 5-8PM on weekdays and 8AM to 8PM on weekends; howwever, to a lesser extent.

<img width="1440" alt="D2:Trips:Gender:Weekday:Hour" src="https://user-images.githubusercontent.com/90135381/152699041-629fbd19-0172-41fb-b070-db0f511b537a.png">

                                  FIGURE 6: Heatmap of Trips by Gender (Weekday per Hour)
                                  
In the heatmap depicted in FIGURE: 6, it can be seen that males are the highest users during peak hours, followed by females and unknown gender users. Again, Thursday and early morning, evening being the most popular times for ride-sharing participation.

<img width="1440" alt="D2:User Trips:Gender:Weekday" src="https://user-images.githubusercontent.com/90135381/152699042-12a94f43-35ec-4408-9a26-eed4f63a058b.png">

                                  FIGURE 7: User Trips by Gender by Weekday
                                
The number of bike trips was further analyzed including gender and usertype. Male subscribers are significantly more participatory in general; however, weekdays, particularly Thursday show the greatest concentration of activity.


***DELIVERABLE 3: Story and Report for Final Presentation***


<img width="1440" alt="August Peak Hours" src="https://user-images.githubusercontent.com/90135381/152698997-c3327aa0-ec31-4831-8b20-51dfd16a2233.png">

                                  FIGURE 8: Horizontal Bar Chart for August Peak Hours
                                  
As illustrated in FIGURE: 8, peak hours are 8AM and between 4 and 7PM, while non-peak hours fall between 1-5 AM.


<img width="1440" alt="Rides by Gender" src="https://user-images.githubusercontent.com/90135381/152699687-13838fdd-8cea-4816-883b-e51040fdd14a.png">


                                  FIGURE 9: Pie Chart for Rides by Gender
                                  
The pie chart in FIGURE: 9 clearly portrays significantly and predominantly greater numbers of male riders (1,530,272), followed by female riders (588,431) and, lastly those of unknown gender (225,521).

<img width="1440" alt="Usertype Usage" src="https://user-images.githubusercontent.com/90135381/152700152-ca07cc9b-80d8-4f44-b6ff-f65d884861e7.png">

                                   FIGURE 10: Bar Chart for Usertype Usage
                                   
Figure 10, is an additional illustration of subscriber versus customer utilization. Out of the total number of ride-shares, 1,900,359 were bikesharing subscribers and 443,865 were customers.

______________
***SUMMARY***
______________

In conclusion, as depicted above, it can be ascertained that implementing a bike-sharing business in Des Moines can be a successful endeavour. To summarize, there were a total of of the 2,344,224 trips in August, 2019; males predominated the bike-sharing service utilization; peak hours were morning and evening with Thursday being the most popular day for utilization. To make this business more lucrative, incentives can be provided for greater female participation. Additionally, a 'family day' proposal can be suggested to increase rider usage on weekends.
_____________________________________________________________________________________________________
***REFERENCES*** BSC, Google, StackOverflow, GitHub
