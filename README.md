# bikesharing

# OVERVIEW OF THE PROJECT

This project visualizes data for planning a bicycle sharing business in DesMoines.  The project uses data from the New York City bicycle sharing program found at [citibike](https://ride.citibikenyc.com/system-data). Certain data is useful to visualize such as numbers of riders, numbers of rides, duration, and other considerations.  Some preparation of the data file (in csv format) was necessary to convert the format into dates and times for graphing purposes.  
  
Tableau was used to visualize the data and gain insights for helping to consider a similar business.  Tableau graphics not only provide visual data but also data *dimensions* such as type of bicycle rider, etc, which can be grouped and displayed in popups, legends, colors, and color gradients. Tableau graphics used in this analysis were pie charts, line charts, and heatmaps.  The tool provides a sytematic method: import data, create worksheets, create dashboards and finally use the dashboards to create a "story" for the project.  


# RESULTS
  
  Prior to seeing the story for the project, the following project elements are discussed:<br><br>
  
  
  
  Fig 1  | Fig 2
  :--------:|:------------:
<img width="170" alt="Pie1" src="https://user-images.githubusercontent.com/85037467/134572525-162ceb7b-794a-4b44-b9ff-046485026e42.png">    |     <img width="165" alt="Pie2" src="https://user-images.githubusercontent.com/85037467/134572633-44b13230-b3c8-4c49-8d0a-d0debe492b48.png">

  
  **Pie maps** show the use of the bicycles by the number of rides.  The data contains a breakdown of rider information by gender, customer or subscriber.  *Men who are subscribers to the bicycle program are the largest bicycle users*.<br><br>
    
  
  
  
   Fig 3  | Fig 4
  :--------:|:------------:
<img width="271" alt="Linemap1" src="https://user-images.githubusercontent.com/85037467/134573159-9685de62-ae2f-4d3c-99cd-770b23da7e81.png">  |  <img width="263" alt="Linemap2" src="https://user-images.githubusercontent.com/85037467/134573190-e3accda0-feaa-4326-9550-5d1def6534b3.png">
  
  
  
  **Line maps** show the trip duration of the bicycle ride.  *It is easy to see that rides take less thant one hour for all riders*.<br><br>
  
  
  Fig 5  |
  :-----:|
  <img width="272" alt="Heatmap1" src="https://user-images.githubusercontent.com/85037467/134573277-fba8ee88-31db-4018-b24b-19ec04150b7a.png">
  
  
  This is a **heat map** which shows the days of the week together with the type of bicycle rider- customer or subscriber - along with the gender.  As can be seen in the more detailed story board, *the information shows that men who are subscribers ride most on Thursdays*.<br><br>
  
  Fig 6  |
  :-----:|
  <img width="779" alt="Heatmap2" src="https://user-images.githubusercontent.com/85037467/134573307-9ee009ac-3f64-4036-86b4-cd288bf900cd.png">
  
  This is a **heat map** which adds the dimension of stoptime to the previous dimensions.  In the story, *it can be seen that men ride most often and in mornings and evenings*.<br><br> 

  Fig 7  |
  :-----:|
  <img width="501" alt="Heatmap3" src="https://user-images.githubusercontent.com/85037467/134573344-9f2ae159-9ec6-49f3-a199-d19052549f8f.png">

  This is a **heat map** which plots only the dimensions of stoptime and weekday (not gender).  The data presented in th story shows *the evening and early morning are most poplular times during the week, but more rides are recorded in the evening.*<br><br>
  The story provides a more in-depth presentation of results [(click here)](https://public.tableau.com/app/profile/dan.o.neal/viz/DModule14prj/PieMapsStory). The story board discusses:<br>
  
  * The size of the project
  * Knowing the times to ride
  * Busy hours of the week
  * Addition rider data on days and times


# SUMMARY

  The results are based on a dataset of over 2 million rides in one month in NYC.  Since this is serving as a model for a similar program in DesMoines, the insights should be considered in context, namely the potential bicycle riders in terms of all the dimensions that were visualized.  From the results it appears that a scaled down version should be adopted but with some modifications.  Since subscribers are most likely to be the most active bicycle users once a subscription program is set up, it is recommended to start with a customer program first as a slow start and then move on to a subscription program.  In addition, the ridership could also be set up equally for family-type rides and for the most active group to start out with and to modify later.  Ridership size and geographical information would be beneficial and could be obtained from two additional maps:
  
  * A bubble map which has dimensions of bicyle users colors and quantitative measures of size and counts.  This shows the size of the total group of riders.
  * Another useful map would be the heatmap which plots location and station (pickup or dropoff).  This would show where the most popular stations are.<br>
  
  

