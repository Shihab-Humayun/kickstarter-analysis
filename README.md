# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to perform analysis on the Kickstarter data sheet to discover trends. Louise’s play, Fever, came close to its fundraising goal in a short amount of time. She wants to learn how different campaigns progressed in relation to their launch dates and funding goals. I referenced the Kickstarter dataset to create a visualization for these campaign outcomes based on their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the analysis of outcomes based on launch date, I created a pivot table and a line chart to visualize the theater campaign outcomes, which are categorized by "successful", "failed" and "canceled" based on launch date.

![image](https://user-images.githubusercontent.com/49353083/109394641-05d40100-78f6-11eb-91c5-fa5ae14e4c9e.png)

Based on the line chart, notice that during the month of May and June, there was a highest count of successful outcomes in the theater category. These months are also the time where the most fundraisers has been created. We can conclude from the chart that starting a campaign on December would not have the best chance of achieving the fundraising goal. 

### Analysis of Outcomes Based on Goals
For the analysis of outcomes based on goals, I created a data sheet with the countifs functions and a line chart to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. 

![image](https://user-images.githubusercontent.com/49353083/109395497-bb08b800-78fa-11eb-8e63-fc14b9c2d257.png)

Based on the line chart, we can analyze the data and notice that majority of the campaign goals range from the $1000 to $4999. The number of projects lowers as the goal range increases. We can see that campaign goals higher than $50000 did not reach their goals 10 out of the 12 projects made.  

### Challenges and Difficulties Encountered

#### Analysis of Outcomes Based on Launch Date
In the analysis of outcomes based on launch date, I did not encounter any problems when creating the pivot table and line chart. A possible challenge a person can face when attempting to create the pivot table is not entering the pivot chart fields to the correct categories which are, "filters", "column", "rows", and "values". When creating the pivot chart, one should be aware entering the Date Created Conversion into the rows chart. One should filter out the excess information automatically added to the rows when creating the pivot chart. Also, remembering to filter by parent category is essential in order to presenting the correct results on the chart. Paying attention to little details like this is something one can gloss over.

#### Analysis of Outcomes Based on Goals
In the analysis of outcomes based on goals, I did not encounter any problems when creating the data sheet and line chart. A possible challenge a person can face when attempting to create the pivot table is not entering the wrong information into the countifs functions. When creating a function in Excel, it sometimes adds unnecessary cells when you click on a random cell. It is important to be aware of what you click when creating the functions. Also, making sure the correct criteria has been implemented such as the goal range is tedious work. I recommend double checking the formulas before creating a chart to ensure all the information is displaying correctly. One can verify this by going to the Kickstarter sheet and use the filters to see if the count is the same as the one in Outcomes Based on Goals sheet.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
