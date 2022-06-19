# Kickstarting with Excel

## Overview of Project

The purpose of this project is to anaylze Kickstarter data in order to assist the client with the planning of her play's fundraising campaign. Using past data history, we are able to make insights into several key aspcts of a Kickstarter campaign, including:
* Average goal size of successful campaigns.
* Average duration of successful campaigns.
* The best time of year to Launch a campaign

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Taking the Kickstarter data and creating a pivot table allowed us sort and analyze the data on a month by month basis. By taking this data and visualizing it in a line graph, we are able to easier understand both the best and worst time of year to launch of fundraising campaign. 
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107593214/174493066-77a1f335-36e9-4d25-bd06-4829c856be37.PNG)

### Analysis of Outcomes Based on Goals
By creating a new table and sorting the data by the goal of each campaign, we can gain insights into whether or not the size of the fundraiser's goal has any impact on the success of a campaign. By using the `=countifs()` function of Excel we are able to easily summarize all of the campaign goals into a small table, which we can then visualize with a line graph to better understand.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107593214/174493082-419025cf-1fa5-49c6-b2eb-d81100e6dee7.PNG)

### Challenges and Difficulties Encountered

## Results

- Based on the analysis of campaign outcomes by launch date we can determine that the summer time is the best time of year to launch a campaign. May is the launch month that appears to have the highest ratio of successful to failed campaigns, followed by June, July, and August. However, the number of successful campaigns drops off dramatically around the end of the year and into the new year. 

- Based on the analysis of campaign outcomes based on the fundraiser goals, we are able to determine that the campaigns with smaller goals tend to be more successful than those with very large goals. By far the most popular goal amounts appear to be between $1000 and $4999, which accounts for more than half of all the campaigns. However, there are a few outliers within this data set that do not follow this trend. Further anaylsis of these specfic campaigns is required to see if there are any specific reasons to which these were successful. One potential reason these may have been successful is because they were in the 'Spotlight' resulting in a large number of backers in comparison to the other campaigns in this goal range. 

### - What are some limitations of this dataset?

The data set does not give an explanation as to what exactly makes a campaign a 'staff pick', nor does it indicate what exactly the 'spotlight' is. 

### - What are some other possible tables and/or graphs that we could create?

We could analyze what % of 'staff picks' and/or those campaigns in the 'spotlight' are successful. We could also make a graph based off this data. We could also make a table to find if there is a correlation between the 'spotlight' and the number of backers received.

