# Kickstarting with Excel

## Project Overview
- This analysis was put together in order to determine how successful different fundraising campaigns were in comparison to the play Fever. 

### Purpose
- The purpose of this study is to perform data analysis on various Kickstarter campaigns to determine how each of them performed regarding their launch dates and funding goals. The data was sorted and filtered first by the parent category for Theater, then by Subcategory for Plays, to create visual representations of the data for Louise.

## Analysis and Challenges
- To appropriately analyze this data, a spreadsheet in Excel was made using the data Louise collected from the other Kickstarter Campaigns from 2009-2017. The original spreadsheet contained 4115 campaigns, sorted into 42 categories and subcategories. For this analysis, we will focus on the Theater parent category and Plays subcategory. Once the data was filtered, we were left with 1369 Theater campaigns, of which 1046 were for Plays. Though there is a lot of data, there is a limit to what can be shown. These campaigns lack demographic data, such as the average age of pledgers and suburban/city settings, which could affect the fundraising potential. 

### Analysis of Outcomes Based on Launch Date
- For the first portion of our analysis, we took the 1369 Theater campaigns and looked at their outcomes based on the launch date. To do this, we begin by converting the Unix Timestamps of each campaign to a readable format. This conversion is put into a separate column labeled “Date Created Conversion”. We then create a pivot table in a new sheet, labeled “Theater Outcomes Based on Launch Date”. The pivot table is filtered by “Year” and “Parent Category”. In columns, we put “outcomes” and “Date Created Conversions” in rows. We use the pivot table to help visualize the outcome of the theater campaigns based on the month they were launched by creating a line graph. By looking at the pivot chart and line graph, we can determine that the months of May and June have the highest rates of successful campaigns. We are also able to see that there is a higher rate of success than failure and cancelations. 

### Analysis of Outcomes Based on Goals
- The second half of the analysis was performed to show the relationship between the success of the campaign and the goal. A new sheet was opened with column A labeled “Goal” which ranged from “Less than 1000” to “50000 or more” shown in the chart “Outcomes Based on Goals”. We then pulled data from the original Kickstarter spreadsheet and filtered for the number of successful, failed, and canceled Play campaigns. This was performed through the COUNTIFs function. From there, the total number of projects, percentage successful, percentage failed, and the percentage canceled were calculated. A line chart was created to show the relationship between the goal amount and the percentage of each outcome. Both the data and the line chart show that there are no canceled campaigns for any of the goal ranges. We can also see that the “Percentage Successful” and “Percentage Failed” have a trend. The trend is more apparent in the line chart where we can see that the two go back and forth starting from “20000 to 24999”.

### Challenges and Difficulties Encountered
- The biggest challenge that I encountered when first attempting to analyze this data was how to properly write the COUNTIFs function. Once I was able to understand how to properly write that, I gained a better understanding of how functions work in Excel. Once I was able to get past the technical difficulties, I noticed that there was a lack of demographic data included. Demographic data is an important aspect of understanding the success rates of campaigns for each category. 

## Results
- Demographics play a large role in how popular certain categories may be. Without considering whether these campaigns were performed in suburban or city areas, we can’t understand whether that may affect the success of that campaign. The age and median income of pledgers may also offer more insight into who these campaigns may appeal. I also noticed that this data ends in the year 2017, which is 5 years ago. The demographics, popularity, and campaigns may have changed rather drastically over the years, especially considering the recent issue with inflation. In order to account for this, I would recommend expanding upon the study to the current date. I would also include demographic data to show how different campaigns fared in different states and cities, as well as the age group of the average pledger. To visualize this data, I would use a stacked column chart to see the relationship average age of pledgers for each campaign, the number of pledgers, and whether they succeeded, failed, or canceled. 
