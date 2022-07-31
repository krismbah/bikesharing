# bikesharing

## Overview

The purpose of this analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. The following tasks are to be completed: 

1. Change Trip Duration to a Datetime Format.
2. Create Visualizations for the Trip Analysis.
3. Create a Story and Report for the Final Presentation.

## Results

***Deliverable 1: Change Trip Duration to a Datetime Format***
Using Python and Pandas functions, convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2:

Figure 1:

![Image1](https://github.com/krismbah/bikesharing/blob/main/D1.png)

Figure 2:

![Image1.1](https://github.com/krismbah/bikesharing/blob/main/D1.1.png)


***Deliverable 2: Create Visualizations for the Trip Analysis***
Using Tableau, create visualizations that show; How long bikes are checked out for all riders and genders, How many trips are taken by the hour for each day of the week, for all riders and genders, and a breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender:

Figure 3:

![Image2](https://github.com/krismbah/bikesharing/blob/main/D2.png)

Figure 4:

![Image2.1](https://github.com/krismbah/bikesharing/blob/main/D2.1.png)

Figure 5:

![Image2.2](https://github.com/krismbah/bikesharing/blob/main/D2.2.png)

Figure 6:

![Image2.3](https://github.com/krismbah/bikesharing/blob/main/D2.3.png)

Figure 7:

![Image2.4](https://github.com/krismbah/bikesharing/blob/main/D2.4.png)



***Deliverable 3: Create a Story and Report for the Final Presentation***
Create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis from the module and in Deliverable 2:

Figure 8:

![Image3](https://github.com/krismbah/bikesharing/blob/main/D3.png)

Figure 9:

![Image3.1](https://github.com/krismbah/bikesharing/blob/main/D3.1.png)

Figure 10:

![Image3.2](https://github.com/krismbah/bikesharing/blob/main/D3.2.png)



## Summary

To summarize, worksheets, dashboards, and and story was created in Tableu in order to visualize key data from a New York Citi Bike dataset. To solidify the proposal to investors, the following steps were implemented in the analysis in order to create the following dashboard:

1. Create a DataFrame from the 201908-citibike-tripdata.csv file.
2. Check the datatypes of each column in the DataFrame.
3. Convert the "tripduration" column to a datetime datatype by passing the DataFrame column and the units inside the to_datetime() function.
4. Add the number of records or the generated field that counts the number of records in the CSV file to the Rows.
5. Add the "tripduration" column you converted to the Columns, and filter the "More" option by "Hour".
6. Add the "tripduration" column again to the Columns, and filter the "More" option by "Minute", and then change the values from "discrete" to "continuous".
7. Add the "tripduration" column that shows the "Hour" to the Filters field, and select "Show Filter".
8. Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".
9. Add the converted column for gender as a color to the Marks field, add it to the Filters field, and select "Show Filter".
10. Edit the X and Y axis labels by right-clicking on the axis label and selecting "Edit Axis".
11. Add the "Starttime" column to the Rows, and filter the "More" option by "Hour".
12. Add the "Stoptime" column to the Columns, and filter the “More” option by "Weekday".
13. Add the number of records or the generated field that counts the number of records in the CSV file to the Marks field as a color. Select "Automatic" for the type of graph to create the heatmap.
14. Format the Y axis of the Starttime by Hour to show the 12-hour format.
15. Add the "Usertype" to the Rows and to the Filters field, and select "Show Filter".
16. Use the five visualizations that you created in Deliverable 2.
17. Use at least two visualizations that you created in this module.

[link to dashboard](https://public.tableau.com/views/2019NYCCitibikeDataAnalysis/2019NYCCitibikeDataAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
