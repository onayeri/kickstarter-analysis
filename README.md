# kickstarter-analysis
#### Performing analysis on kickstarter data to uncover trends
---
## Overview of Project 
---
The purpose of the Kickstarter assignment was to serve as an introduction to the tools untilized in excel. Through this assignment, data was extracted from a dataset into a pivot table which allowed a general overview of the filtered data to be presented in a visual graph. The Kickstarter worksheet consisted of data regarding the film/television shows/videos along with the outcome status, the financial goal amount, the pledged amount and the other details associated with each film category. The details of the Kickstarter dataset were explored by creating a pivot table and graph for the "Theatre Outcomes Based on Launch" and "Outcomes Based on Goals". This allowed for a more filtered inspection of subcategories within the data and detailed analysis of the relationship between outcome status and the financial goal amount.
---
## Analysis and Challenges
---
#### Theater Outcomes By Launch Date: Analysis & Challenge 
In order to perform the analysis for the "Theater Outcomes By Launch Date" worksheet, the launch date column needed to be converted from the Unix time stamp to the standard date format: mm/dd/yyyy. Once this was fixed, my challenge was to create a column for the month name for each of those dates. I did this by creating a "Month" column with the following formula: =MONTH(serial_number). This allowed me to isolate the months into a column, but it was still in numerical format. To convert the numerical month into text, I tried changing the format using the format tool on excel. I proceeded to search the specific formula for converting a numerical month date to the name in text. 
---
I found the formula =TEXT(serial_number*29, "mmm") on the site: [OfficeExtend] (https://www.extendoffice.com/documents/excel/5146-excel-convert-1-12-to-month.html). This allowed me to get the abbreviated name for each month and create a column titled "month name" and continue to properly filter my pivot table and analyze the number of outcomes that were successful, failed and canceled specifically for the category, "Theater" by month name.
---
![image](https://user-images.githubusercontent.com/105329532/177216255-bbb92d07-f701-443f-a8ae-54dd0ee1b4cd.png)
![image](https://user-images.githubusercontent.com/105329532/177216299-180d5cfa-63fa-446a-b143-2bba4cbb9b58.png)
---
#### Outcomes Based on Goals: Analysis & Challenge
The main challenge for the "Outcomes Based on Goals" worksheet was to create an organized table with all the proper financial goal ranges and filtering the formula for not only the ranges and the outcome type, but the subcategory, "plays". My challenge was to figure out why my graph was not replicating the demo graph presented in the Module challenge. I figured out that because I was missing a goal range within my table, I was also missing a data point in my graph. These important features heavily impacted the corresponding percentages in the table. By fixing them, my graph more accurately represented the targeted data for analysis.
---
![image](https://user-images.githubusercontent.com/105329532/177216335-68605231-8bb0-46f4-bf7d-aad2d2d9755e.png)
---
## Results
#### Theater Outcomes by Launch Date Conclusion
* Conclusion 1: The highest amount of successful theater outcomes was launched in the month of May and June. This indicated as the highest data point on the graph.
---
* Conclusion 2: There was no value input that indicated a cancelation occurred within the month of October. This is reflected as a break in the line graph represented for cancelations during the month of October. 
---
![image](https://user-images.githubusercontent.com/105329532/177216654-f46a1274-6f29-4bc2-a6cf-b25be015c5e4.png)
---
#### Outcomes Based on Goals Conclusion
* Conclusion 1: The data for the percentages of successful and failed plays are shown to an direct inverse relationship of one another within each specific financial goal range. The data points for successful and failed plays mirror one another on the graph. If the success percentage is high, then the failure recorded is low or vice versa. 
---
* Conclusion 2: There were no canceled plays for any of the financial goal value ranges. This is presented on the graph as a straight line along the x-axis because there were 0 cancelations. This reveals that plays were either successful or failed with in their financial goal.
---
![image](https://user-images.githubusercontent.com/105329532/177216469-9d2249dc-15ff-4c38-aa8c-4c2790402141.png)
