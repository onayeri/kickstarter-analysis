# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
---
## Overveiw of Project 
The purpose of the Kickstarter assignment was to serve as an introduction to the tools untilized in excel. Through this assignment, data was extracted from a dataset into a pivot table which allowed a general overveiw of the filtered data to be presented in a visual graph. The Kickstarter worksheet consisted of data regarding the film/television shows/videos along with the outcome status, the financial goal amount, the pledged amount and  the other details associated with each film category. The details of the Kickstarter dataset was explored by creating a pivot table and graph for the "Theatre Outcomes Based on Launch" and "Outcomes Based on Goals". This allowed for a more filtered inspection of subcategories within the data and detailed analysis of the relationship between outcome status and the financial goal amount.
---
## Analysis and Challenges 
#### Theater Outcomes By Launch Date
In order to perform the analysis for the "Theater Outcomes By Launch Date" worksheet, the launch date column neeeded to be converted from the unix time stamp to the standard date format: mm/dd/yyyy. Once this was fixed, my challenge was to create a column for the month name for each of those dates. I did this by creating a "Month" column with the following formula: =MONTH(serial_number). This allowed me to isolate the months into a colunm, but it was still in numerical format. To convert the numerical month into text, I tried changing the format using the format tool on excel. I proceeded to search the specific formula for converting a numerical month date to the name in text. I found the formula =TEXT(serial_number*29, "mmm") on the site: [OficeExtend] (https://www.extendoffice.com/documents/excel/5146-excel-convert-1-12-to-month.html). This allowed me to get the abbrevieted name for each month and create a column titled "month name" and continue to properly filter my pivot table and analyze the number of outcomes that were successful, failed and canceled specifically for the category, "Theater" by month name.
---
#### Outcomes Based on Goals 
The main challenge for the "Outcomes Based on Goals" worksheet was to create an organized table with all of the proper financial goal ranges and filtering the formula for not only the ranges and the outcome type, but the subcategory, "plays". My challenge was to figure out why my graph was not replicating the demo graph presented in the Module challenge. I figured out that because I was missing a goal range within my table, I was also missing a data point in my graph. These important features heavily impacted the corresponding percentages in the table. By fixing them, my graph more accuratley represented the targeted data for analysis.
---
##Results
#### Theater Outcomes by Launch Date Conclusion
*Conclusion 1: The highest amount of successful theater outcomes were launched in the month of May and June. This indicated as the highest data point on the graph.
*Conclusion 2: There was no value input that indicated a cancelation occured within the month of October. This is reflected as a break in the line graph represented for cancelations during the month of October. 
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
---
####Outcomes Based on Goals Conclusion
*Conclusion 1: The data for the percentages of successful and faild plays are shown to an direct inverse relationship  of one another within each specific financial goal range. This is shown on the graph when the success point i
