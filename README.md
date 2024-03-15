
# Sales Data

### Dashboard Link : https://app.powerbi.com/groups/me/reports/7e0283b3-42d6-4660-bdd3-5f7850c8541e/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps the company understand the customers better. It helps know their customers better .Helps know what is in demand, what they like best , the profit margin and their revenue. Through different demand of goods they get to know their improvement area, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these providing more goods and avoid delays.




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file then proceeded to transform the data..
- Step 2 : The column headers are identified in the first row and should be kept as 
headers.
- Step 3 : After promoting the headers, navigate to the 'Transform' tab and select 
'Detect Data Type.' This action will automatically identify the data type 
of each column and convert them as needed.
- Step 4 : Split the datetime into date and time stamp
- Step 5 : Visualize sales trend over time that is per month using the line chart.

![sum of sales](https://github.com/kibandichristine/Sales-Data/assets/91536785/955d6447-5127-443e-9594-5a3aeae26ed7)

The graph shows a gradual increase in sales at the beginning of the year up to April the a steady decrease is seen till September where the least level is then the sales increas at a high rate.

- Step 6 :Visualize the top 5 best selling products using stacked bar chart

![best selling products](https://github.com/kibandichristine/Sales-Data/assets/91536785/c8d2ed06-be6f-4213-bf80-b0bb0657e5bd)

- Step 7 : Since the data contains cities, thus in order to represent sales in the different areas, a map was added to visualize the top 5 with the most sales.
- Step 8 : Visual filters (Slicers) were added for four fields named "Day", "Month", "City" & "Product".
- Step 9 : Weekly sales distribution by weekday using column chart.
- Step 10 : Best selling products using tree map
- Step 11 : Three card visuals were added to the canvas, representing "Revenue/Total profit", "Sales Quantity", "Profit Margin" average departure delay in minutes & other representing average arrival delay in minutes.
           
           Revenue = SUM OF SALES

![Revenue](https://github.com/kibandichristine/Sales-Data/assets/91536785/619dca9a-cb15-4e48-af3e-de32783ccf44)

        Sales Quantity= SUM OF Quantity Ordered

![Sales quatity](https://github.com/kibandichristine/Sales-Data/assets/91536785/9fa286ef-7347-4206-b277-410b23738476)


      
- Step 12 : New measures were created to find the profit margin.

Find the profit margin by using this formula in the measure.

        Profit Margin = (( TOTAL SALES -TOTAL COST )/TOTAL SALES)*100;

 
 Find the total cost by using the new measure.
        Total Cost = SUM('Sales Data'[Price Eeach])
 Find the total sales by using the new measure
Following DAX expression was written for the same,
       Total Sales = SUM('Sales Data'[Sales]) 
        
        
A card visual was used to represent percentage Profit Margin.

![profit margin](https://github.com/kibandichristine/Sales-Data/assets/91536785/bb70e58b-2b11-4444-a98e-97cdf1505ad9)



        
 
 - Step 18 : The report was then published to Power BI Service.
 
 
 # Report Snapshot (Power BI DESKTOP)
 
![sales data - Power BI - Google Chrome 15_03_2024 14_10_23](https://github.com/kibandichristine/Sales-Data/assets/91536785/3e89ed17-f534-4972-95f4-4e7ff29eb392)
 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Revenue = 34,492,040,000
### [2] Total Number of Sales Quantity Ordered = 209,
### [3] Profit margin in the year 2019 was 58.83%
### Top 5 best selling products are: 
        USB-C Charging Cable = 23975
        Wired Headphones = 20557
        Macbook Pro Laptop = 4728
        ThinkPad Laptop = 4130
        Vareebadd Phone = 2068
  
