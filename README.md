## Overview of the analysis: 
On a recent trip to New York City with my friend, Kate, I used CitiBike to ride around town and explore neighborhoods I never could have acessed on foot. I loved the freedom of bike travel, and I wondered if such a program might fit in my home town of Des Moines, Iowa.

I downloaded one month of CitiBike data from August 2019 for analysis. August is a warm month in New York, optimal for bike-riding. To illustrate what I had learned, I used Tableau.

## Results: 
I enjoyed Tableau. The program graphs data beautifully, and it's pretty easy to filter data and choose alternatives for the presentation. Stuff that would take hours on Plotly or Matplotlib can be done in five clicks of the mouse. This program is a game-changer.

I was able to *map locations* around New York City, both for bike pick-up and bike returns. This gave me an instant understanding of the logicistics of CitiBike. Would staff be needed every evening to shuttle bikes back to origin locations, for example, or were most bikes returned to area bike stands? By comparing the two maps (and using different colors for pickup and return, I was able to get answers to this question.
![Map locations example](https://github.com/JDittes/bikesharing/blob/main/mapping.png)

A line graph helped me to identify how much the bikes were actually used by riders. I was surprised to see the peak usage crest at 10 minutes or less. I was expecting to see rides reach 15 to 30 minutes, but this line chart changed my mind. ![line chart ridership](https://github.com/JDittes/bikesharing/blob/main/line.png)

I was also able to split the data into the genders of riders. Through this study, I noticed a huge gap between male and female riders. A *pie chart* helped me to realize that almost 2/3rds of riders are men. A further *line chart*, splitting the minutes of riding also showed this gap. Such a huge discrepancy makes me think that there is a large, untapped market for CitiBike. It should invest in reaching out to female bike riders. 
![Pie chart](https://github.com/JDittes/bikesharing/blob/main/pie.png)
![Line chart riders](https://github.com/JDittes/bikesharing/blob/main/gender-line.png)

With thoughts towards bicycle maintenance, I looked at the use of the bikes in the program. I created a *text table* to find just the bikes that had the most utilization. Charts like these could help the program identify which bikes to maintain without taking too many bikes off the streets.
![Text table bike usage](https://github.com/JDittes/bikesharing/blob/main/text-table.png)

*Heatmaps* helped me to show the busiest times of the day for ridership. I found that--on weekdays--the ridership was busiest at rush hour. When I looked at the weekends, I saw strong usage throughout the daylight hours. These heatmaps could also show ideal times for maintenence so that high-demand times wouldn't be affected by routine maintenance.
![Heat map main ridership times](https://github.com/JDittes/bikesharing/blob/main/heatmap.png)

When I was done, I assembled the graphs into a *Tableau story*, adding captions and subtitles to the text to show the story of CitiBike during the month of August 2019.  [Here is a link to the CitiBike Ridership story](https://public.tableau.com/views/CitiBikeData_16472989855810/CitiBikeRidership?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


## Summary: 
The CitiBike data give Des Moines-area investors a solid platform from which to base decisions on a local bike-sharing program. It shows the busiest times of day, and it reflects the reality that some bikes--specifically those in high-demand areas--will need to be maintained more often than others. It also shows a gender breakdown that shows real possibilities for growth if female riders are targeted by markeging.

Also, I believe that the total number of riders (2.4 million) will surprise the investor, even given the difference in overall population between New York City (8.4 million) and Des Moines (215,000).

There is data that would help the angel investor. One might be a look at CitiBike usage in winter months, which are cold in both locations. It would also be interesting to compare the cities using demographic data: how many residents live within 2 miles of downtown Des Moines vs New York City, for example.

The next step is close research on our target location. I think this Tableau presentation is a good start towards a more comprehensive view of the Des Moines Market.
