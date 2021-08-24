#kickstarter-campaign-excel-analytics\

## Overview of Project
* Client seeks Kickstarter analytics to better inform their campaign strategy moving forward.
* With their play FEVER, their product is the "Theater" category, under the "Plays" subcategory.
* The following data was provided: [Kickstarter_Client_Data](https://github.com/nabilram/kickstarter-campaign-excel-analytics/blob/main/resources/Kickstart%20Client%20Data.zip)

## Analyses: Tools, Methods, Output

### Tools 
* This part of the portfolio illustrates advanced Excel skills: pivot tables, excel charts, nested COUNTIFs, VLOOKUP, etc.  
* See output Excel file with charts for additional insights: [Kickstarter_Output_Analytics](https://github.com/nabilram/kickstarter-campaign-excel-analytics/blob/main/resources/Kickstarter-Excel-Analysis.zip)

### Methods
* Data was wrangled with using the above tools and techniquess to create the charts, below. These methods include:
   * Use of the COUTNTIFS function for nested, conditional counts of "outcomes" based in given criteria.
   * Use of PIVOT TABLES and CHARTS to drill data, visualize it and present for actionable results.  

### Output Charts
* 1.1 _Outcomes by Launch Date Chart_: insight on campaign success/failure based on launch date's month; descend-sorted to show which monthly launch trends.
![Outcomes_by_Month](https://github.com/nabilram/kickstarter-campaign-excel-analytics/blob/main/resources/Theater_Outcomes_vs_Launch.png)


* 1.2 _Outcomes by Goal Charts_: insight on campaign success/failure rate based on goal amount.
![Outcomes_by_Goal_Amount](https://github.com/nabilram/kickstarter-campaign-excel-analytics/blob/main/resources/Outcomes_vs_Goals.png) 

## Challenges and Solutions

### Challenge I: Data Clean Up and Reformatting
* Converted Unix timestamps to readable format using DATE function
* Spliced string data within one cell using TEXT-TO-COLUMN tool; "Category" and "Subcategory"
* Gradient color fomatting using CONDITIONAL FORMATTING to indentify outliers in dataset

### Challenge II: Nested Conditions and Parentheses
* Long equations fail when parentheses aren't aligned correctly. 
* Being mindful of parentheses when creating nested conditions and if statements is important.
* Practice makes perfect. This is a normm in coding. More practice will result in less of these. 
* Familiarize myself with COUNTIFS type functions that allow for multiple conditions -- similar of IFELSE in R.

## Results

### Outcomes by Date (chart 1.1) 
* Based on raw counts, we can assume that that months of May, June, and July are the best months to launch a campaign.
   * These months have the highest counts of succesful campaigns with May having the highest success count at 111 campaigns.
* Based on raw counts, never launch your campaign on October. 
   * This month has the highest count of failed campaigns in the last 8 years of data. 

### Outcomes by Goal Amount (chart 1.2)
* Based on campaigns specifically under the "Plays" Subcategory, the sucess rate of is higher if a campain's goal is kept below 5000 USD
   * Sucess rates in the last 8 years have not fallen below 70% if the allocated ask is less than this amount. 

## Conclusion
* The client should re-align their Kickstarter campaign strategy using the above findings. 
* Specifically, they should consider a launch date on our around May and with a budgest that is less than 5000 USD. 
* Doing so will heighten their chances of success, based on this limited data analysis. 

