
# US BORDER CROSSING ANALYSIS

## BUSINESS TASK STATEMENT
**To Evalauste the inbound crossings at the U.S.-Canada and the U.S.-Mexico Border at the Port Level.** 


## EXECUTIVE SUMMARY
The Bureau of Transportation Statistics (BTS) Border Crossing Data provides summary statistics for inbound crossings at the U.S.-Canada and the U.S.-Mexico border at the port level. 
Data are available for trucks, trains, containers, buses, personal vehicles, passengers, and pedestrians. 
Border crossing data are collected at ports of entry by U.S. Customs and Border Protection (CBP). 
The data reflect the number of vehicles, containers, passengers, or pedestrians entering the United States.

### MAJOR POINT FOR ANALYSIS
1.  To examine both US-Canada and US-Mexico
2.  Determine which borders have major crossings and possible reasons
3.  Check the media to which people cross borders 

### DATA SOURCE
**[US Border Crossing Dataset Link](https://catalog.data.gov/dataset/border-crossing-entry-data-683ae)**


## ANALYSIS PROCEDURE

### DATA PREPARATION, CLEANING AND EXPLORATORY DATA ANALYSIS (EDA) USING EXCEL AND POWER QUERY
1. First, we had these columns (Port Name, State, Port Code, Border, Date, Measure, Value, Latitude, Longitude, Point) before analysis on Excel.
2. I checked for null or blank rows. I had non
3. I checked and removed duplicate values
4. Uploading the datasets on Power Query.
5. I removed the columns to only the ones relevant for the analysis (Port Name, State,	Border, Date, Measure, Latitude, Longitude).
6. The measure column has related fields, so I combined related ones to form one field to make the analysis easy to understand and to avoid confusion
7. The columns were formatted to the suitable data types.
8. The cleaned datasets as now uploaded to Tableau for proper analaysis.

9. 
**Details are stated in the SQL Query:** **[SQL Server Query Link](bikeshare_combine_dataset.sql)**



### VISUALIZATION ON TABLEAU
![image](bikeshare_excel.PNG)





### **I extended my analysis on Tableau**
![image](tab.PNG)

**[Tabeau Visualization Link](https://public.tableau.com/views/2023CyclisticBikeshare/CyclisticBikeshareAfor2023?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## MAJOR FINDINGS
1.  Bike usage increases across the month as we into summer and decreases as we move into winter. The number of rides used by annual members is more compared to casual riders.
2. Casual riders use bikes more on the weekend, which suggests that the annual members might be 9-5 workers who use bikes more on weekdays.
3.  As casual riders use more bikes on weekends, they also spend more time riding especially on the weekends.
4.  We see that casual riders spend more time riding per month.
5.  Docked bikes are loved by casual riders since they used all the docked bikes as they were introduced.

## MY RECOMMENDATIONS
Converting casual riders to annual riders will boost the revenue of Cyclistics Bikeshare Company. 

These are my recommendations:
1.  Promos and discounts should be given to casual riders to enable them to become annual riders. This will help to boost business on the weekends.
2. The docked bike's introduction was beautiful. This can be used to attract more casual riders to become annual members.
3.  More bikes should be procured and more dock stations to serve more customers in Chicago.











