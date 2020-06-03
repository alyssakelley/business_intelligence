# COVID-19 Visualization and Tracker Using Tableau by Alyssa Kelley

Source: The dataset used to create this visualization is from the COVID-19 Data Hub which can be found here: https://www.tableau.com/covid-19-coronavirus-data-resources and accessed through a web data connector via data.world which can be accessed here: https://tableau.data.world/?dataset_name=covid-19-data-resource-hub%2Fcovid-19-case-counts&query=SELECT%20*%0AFROM%20covid_19_cases&queryType=SQL
Credit for the tutorial on how to get started with Tableau from Anthony B. Smaok.

# Where to access this visualization:

You can see a screenshot of the Dashboard I created in Tableau in this repository by viewing the tableau_dashboard.png image.

You can watch a demonstration of the visualiation by watching the demonstration.mov that is in this repository as well.

You can visit my public, published workbook here: https://public.tableau.com/profile/alyssa.kelley#!/vizhome/COVID19_Tracker_15911512895010/Confirmed_COVID


# About this visualization:

This is a COVID-19 visualization. 

Map:

On the left side of the page you see a map outline created via Mapbox and there are small data points in the center of each country. The size of these data points in each country are determined by the number of confirmed cases, the larger the data point, the more confirmed cases there are in that country. You can hover over these data points to see the tooltip indicating what country this data point applies to, the date this data is representing, and how many cases there are.

Data Counter:

On the top of the right side of the page, there is a number count of the confirmed cases as of the current date being displayed. This number will change as the page control is altered in the top, right corner of the application.

Line Graph:

Below the data counter, there is a line graph below showing the number of cases which is represented on the y-axis, and the date that data is for represented on the x-axis. This line graph is also syncronized with the page control. You can also hover over these data points and see the date this data reflects, and the number of confirmed cases as of that date.

Bar Graph:

In the bottom, right hand corner of the page, there is a bar graph illustrating the top 10 countries that have the highest confirmed cases of COVID-19. On the side of each bar, the numeric value is listed. You can also hover over these bars and see the country this bar is representing, the date this data reflects, and the number of confirmed cases. The countries are sorted in order of who has the highest number of confirmed cases as of the data last updated date listed to the right of the graph.

Page Control:

At the top, right corner of the page there is a white rectange with a sliding bar. You can use this page control to watch the visualizations change based on the date. When the sliding bar is shifted to the left, it is reflecting an earlier date, when the sliding bar is shifted to the right, it is reflected a later date. All of the visualization listed above are synchronized with this page control.


# Technologies used to create this visualization:

This project was created using the Tableau software.