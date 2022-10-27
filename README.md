# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to analyze the outcome of Kickstarter campaigns based on their launch dates and funding goals. The client is looking for comparisons to similar campaign's outcomes to their crowdfunded theatrical play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The dataset contains 4,114 individual crowdfunded campaigns including project names, descriptions, funding goals, pledged amounts, outcomes, countries of origin, currencies, launch dates, backers as well as categories and subcategories. For the purposes of this analysis, I limited the data to the 1,369 campaigns in the theater category to determine the most successful launch dates.

I used this to create a pivot table to organize the data. Filters for category and years, months of the launch dates for the rows and outcomes in the columns.  

Finally, I visualized the contents of the chart into the following line graph.

### Analysis of Outcomes Based on Goals

For this potion of the project, I used the same dataset but this time focused on the sub category of plays. Utilizing the =COUNTIFS formula, I pulled data from the primary sheet into organized categories based on the quantity of successful, failed and canceled campaigns. Used =SUM forumla to total the projects, then divided to produce the percentages. I was able to utilize the results of these categories to organize the following line chart:




### Challenges and Difficulties Encountered


Initially, variances and typos in the repetitive =COUNTIFS formulas were throwing the Outcomes Based on Goals cells into inaccuracy. Copying and pasting verified formulas produced consistent results. As a result, another challenge in organizing the formulas were making the cell references absolute, so when I shifted the formulas from successful, failed, and canceled. Then, the formulas would continue to pull from the same data columns. Once the columns of successful, failed and canceled were ironed out, the rest of the data collection went smoothly.    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The highest quantity of Kickstarter Campaigns were launched in the month of May. In addition, there were more successful campaigns in the month of May than any other. Campaigns launched in December were the closest to an even success and fail rate. December also had the fewest quantity of campaigns launched. 

- What can you conclude about the Outcomes based on Goals?
There were two ranges of successful campaign goals that outpaced the quantity of failed campaigns: less than $1,000 to $14,999 and $35,000 to $44,999. Campaigns with goals over $45,000 had the largest increase in their failure rate.

- What are some limitations of this dataset?
The

- What are some other possible tables and/or graphs that we could create?
