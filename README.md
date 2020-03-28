![header_pic](/header.png)
 
#### Table of Contents  

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)  
[Limitations](#limitations)  
  
## Project Overview  
This module is a deep dive into Excel, a tool that can be used across all areas of life, from household budgeting to complex financial analysis. Learning the intricacies of Excel will draw on (and enhance) skills we may have already, like computer literacy, data literacy, and quantitative reasoning.  

## Resources  
- **Software:** Excel   
- **Data Source:** [data.census.gov](https://data.census.gov)    

## Objectives  
- Use filters and Excel formula to create new datasets
- Create visualizations using Excel charts and pivot tables
- Interpret the summary data provided from the visualizations 

## Summary  
In this challenge, we continued to exercise our Excel prowess! This time, we created two new analyses: outcomes based on goals and outcomes based on launch date.  

**Background**  
Louise’s play Fever came close came close to its fundraising goal in a short amount of time. How many other Kickstarter campaigns were able to do this as well? In this challenge, we conducted a data analysis to answer this question and determine whether the length of a campaign contributes to its ultimate success or failure.  

**Objectives**  
The goals of this challenge were to:
- Use filters and Excel formula to create new datasets
- Create visualizations using Excel charts and pivot tables
- Interpret the summary data provided from the visualizations  

**Instructions**  
Open Excel and create two sheets. Name them "Outcomes Based on Launch Date" and "Outcomes Based on Goals."  
In the "Outcomes Based on Goals" sheet, do the following:  

1. Create 8 new columns with the following headings:
- Goal
- Number Successful
- Number Failed
- Number Canceled
- Total Projects
- Percentage Successful
- Percentage Failed
- Percentage Canceled  

2. In the Goal column, create 12 new rows to sort each project. This will hold each goal range we're charting:  

3. Use COUNTIFS()to count the number of successful, failed, and canceled projects within the newly defined ranges. (Filter the Kickstarter sheet to show only the Plays subcategory, otherwise, our scope includes all campaigns instead of the ones we are interested in.) Populate the appropriate columns.  

4. Add each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column.  

5. Use division to find the percentage of projects that fall into each category (percentage successful, percentage failed, and percentage canceled).  

6. Create a line chart to visualize the relationship between the goal amount and the campaign’s chances of success, failure, or cancellation.  

7. Save the line chart as a .png image.  
![Goal Chart](/Goal%20Chart.png)   
<br/>
<br/>
<br/>
<br/>
In the "Outcomes Based on Launch Date" sheet, do the following:  

1. Create a pivot table that charts the outcome of each Kickstarter project based on the launch date.  

2. Set the “Parent Category” filter to “theater” and save the chart as a .png image.  

![Launch Date Chart](/Launch%20Date%20Chart.png)
