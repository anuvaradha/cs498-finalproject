# cs498-finalproject

This web application is for the final project for UIUC CS 498 Data Visualization class.
The following visualizations are presenting information about the ridership of Ford Go Bike, a bikesharing company operating in the Bay Area.
I utilized the dataset from [https://www.fordgobike.com/system-data]
For the purpose of this project, I have focussed on the number of trips made in the month of January.
In the web application deployed at [https://anuvaradha.github.io/cs498-finalproject/], we will explore how the ridership varies across the days of the month and when are the most popular times to ride a GoBike. 

This visualization follows an interactive slideshow narrative visualization structure because I have specified the path that the user should take (author-led) and then the user is able to investigate details on each chart but must proceed on the defined path. 

**Scenes**
There are a total of 4 scenes. The first scene is an introduction to the whole presentation and the last scene is a conclusion. The 2nd and 3rd scene contain charts. Each scene has a previous and next button and at the bottom, there are dots to allow the user to jump to any of the scenes they want. The 2nd scene is a bar graph with axes and titles. Bar graph was an appropriate choice to depict which day of the month had the most riders. The third scene is a heat map with the names of the days as the y axis and hours as the x axis. There is also a scale showing what each color represents. There are also buttons below the chart to allow the user to filter the data. A heat map was chosen so that the user could compare the most popular times across multiple days.

**Annotations**
On the second scene, I have added text annotations on the bars to indicate whether they were a holiday or a sunday. This is useful for the user to see the trend of the number of rides whether it was a holiday or not. The inclusion of the text Sunday was to help demarcate when one week started/ended. This annotation is cleared when we move to the third scene because the axis has the text Sunday and we are more of focussing on the trends of which are the most popular hours rather than days. 

**Parameters**
Each scene corresponds to a slide number and when the slide number is changed, it triggers a change in the display. On the 2nd scene, the parameters are the colors of the bar and the flag whether to show or hide the text that is shown at the bottom when hovered over a bar. On the 3rd scene, the parameters are the buttons at the bottom of the scene to determine which week of the data is to be displayed.

**Triggers**
The left and right arrows and the dots at the bottom are triggers in the sense that they control which scene to display. In the 2nd scene, when the selected bar is hovered over, it turns brown and also displays information about the bar at the bottom of the chart. In the 3rd scene, the buttons below the chart change the values in the heatmap and the scale (what range of values corresponds to what color). Also, a hover over each square displays the count of the rides. 
