
# SuperStore Data Analysis

### Dashboard Link : [SuperStore Data Analysis](https://app.powerbi.com/view?r=eyJrIjoiNDNhM2RkZmUtMGM2NC00NjE5LWI1MWEtNGM2ODdmNWVhMzdhIiwidCI6ImJlOWY4YzM3LTc4MjctNGQ2ZC04NDg3LTQ4ZjhjYmFjZGJlZiIsImMiOjl9)

## Problem Statement

 In today’s competitive retail market, businesses need data-driven insights to identify trends, optimize operations, and maximize profitability. This analysis uses the "superstore" dataset to uncover key performance indicators such as sales trends, customer preferences, product performance, and geographical distribution of revenue.

The goal is to answer critical business questions, such as:

(i) **Sales Trends**: What are the seasonal sales patterns, and how do they impact overall revenue?

(ii) **Profitability Analysis**: Which product categories and regions drive the most profit, and which ones contribute to losses?

(iii) **Customer Segmentation**: How do customer segments (e.g., Corporate, Home Office, and Consumer) differ in purchasing behavior?

(iv) **Shipping Efficiency**: Are there inefficiencies in delivery modes or delays impacting customer satisfaction?

Answering these questions will help unlock business insights for strategic decision-making, optimize inventory management by identifying top-performing products, enable targeted marketing strategies by understanding customer buying habits, improve cost efficiency by analyzing shipping policies, and guide decision-makers in identifying underperforming regions and categories.

## Approach

This dashboards contains three pages of interactive reports. All the report pages are going to allow the users to change the context of what the entire report is defined for, by using slicers. The slicers included are (i) Year (ii) Region (iii) Category. When the slicers are changed, the entire report updates, including the text summary that we have at the top.

On the first page, we have four visualizations basically visualizing sales against time periods- by month and by day of the week. The first visualization is a line chart showing how sales trended over the twelve months. The second visualization helps us to be able to see how the different segments change in rank over those months. The third and fourth visualizations are stacked column charts showing the average sales by the day of the week and the number of transactions by the day of the week respectively.  A feature in this report is for users to be able to go to any of the months in the sales report and drill through into another report page which has a full scope of report for the selected month. This new report page for the selected month will display the (i) Top 10 States (ii) Bottom 10 States (iii) The frequency of the ship modes for the top 10 states (iv) a map visualization of sales distribution.

The four visualizations on the second page  will display the (i) Top 10 States (ii) Bottom 10 States (iii) The frequency of the ship modes for the top 10 states (iv)
An additional feature on the page is a donut chart tooltip that shows the percentage split for each of the three segments that we have, for each state that we are hovering over.

The third page, we would have two visualizations. The first is an advanced analysis that leverages PowerBI's AI visualizations to allow users to breakdown sales for any of the years 2014-2017 by any of the dimensions that they wish to, such as, Month, Region, Segment, Ship Mode, State, Sub-Category and Category. The second is a key influencers visual, which allows users to understand the prominent factors that increase or decrease sales. Furthermore, a question box is added to allow users to manually type in the questions that they would like to know about the data

## Findings

Using a line chart visual, the monthly sales data reveals notable trends throughout the year. November recorded the highest sales at $352k, followed closely by December at $325k, highlighting a significant surge during the holiday season due to events like Black Friday and Christmas shopping. In contrast, February saw the lowest sales at $59, likely reflecting post-holiday spending fatigue. Sales showed an upward trend from late summer into fall, peaking in the final quarter. A mid-year plateau was observed from April to August, with steady sales ranging between $137k and $159k, suggesting consistent but moderate activity during this period. Notable spikes occurred in March ($205k) and September ($307k), which may align with specific promotional campaigns or seasonal factors. Overall, the data demonstrates cyclical behavior with a slow start in the first quarter, steady mid-year growth, and a strong surge in the fourth quarter.

A ribbon chart is used to do a segment analysis. The sales data analysis reveals that the Consumer segment is the largest revenue driver, contributing over half of the total sales ($1.1M), followed by Corporate ($706K) and Home Office ($430K). November is the strongest sales month, generating $352K, followed by December at $325K, reflecting the impact of the holiday season. Conversely, February recorded the lowest sales at $60K, indicating a post-holiday slump. Sales start slow in Q1, stabilize during Q2 and Q3, and peak sharply in Q4, which accounts for 38% of annual sales. The Consumer segment consistently ranked as the number 1 segment, generating the highest revenue every month except for October, where the Corporate segment led with $78K. This deviation could be due to increased B2B purchases for year-end preparations or corporate budgeting cycles. Consumer also saw a notable spike in September ($185K), while Corporate and Home Office segments recorded their strongest performances in November. These trends suggest a strong seasonality, with steady mid-year sales and a surge during the year-end holidays. To maximize performance, strategies should focus on boosting post-holiday sales in February, optimizing inventory for Q4, and running targeted promotions for Corporate and Home Office segments during their peak months, especially October for Corporate. The Home Office segment has consistently been the lowest revenue generator throughout the period.

A stacked Column Chart is used to show the Average Sales by Day of Week. The chart shows that sales ranges in average between $216.3 and $259.68. The analysis of average sales by day of the week reveals that Tuesday consistently generates the highest revenue, averaging $259.68, followed by Wednesday at $237.35 and Friday at $235.25. This indicates that midweek, particularly Tuesday, is the most productive period for sales, likely driven by higher customer engagement or promotional activities during weekdays. In contrast, Saturday records the lowest average sales at $216.30, closely followed by Thursday at $220.07 and Sunday at $225.35, suggesting a decline in consumer activity over the weekend. This pattern could be due to customers prioritizing leisure or other commitments during weekends. Optimizing sales strategies, such as weekday promotions to maintain the Tuesday momentum and targeted weekend discounts, could help balance sales distribution across all days of the week.

A stacked Column Chart is used to show the No of Transactions by Day of Week. This reveals that the number of distinct transactions ranges between 182 and 920. The analysis of the number of transactions by day of the week reveals that Monday leads with the highest number of transactions at 920, followed closely by Friday with 916. This suggests that the start and end of the traditional workweek are particularly active for customers, potentially driven by beginning-of-week needs and Friday shopping routines. Saturday and Sunday also show strong transaction volumes, with 837 and 850, respectively, indicating high weekend shopping activity. In contrast, Wednesday records the lowest number of transactions at 182, making it the least active day, possibly due to midweek lulls in consumer activity. Tuesday and Thursday see moderate activity, with 558 and 746 transactions, respectively. These trends suggest that while weekdays have specific peaks, weekends also maintain consistent consumer engagement. Strategies to boost midweek transactions, particularly on Wednesdays, could include midweek promotions or events to drive customer traffic and increase overall sales.

The stacked bar chart is used to depict the top 10 and the bottom 10 states by Sales. It is discovered that the top 10 states with the highest sales are California, New York, Texas, Florida, Washington, Virginia, Pennysylvania, Illinois, Minnesota and Ohio. The bottom 10 states with the lowest sales, from the least are South Dakota, Nebraska, Montana, Idaho, New Hampshire, Maine, New Mexico, Iowa, Kansas and Missouri.

A matrix is used to analyse the ship modes. This reveals that Standard Class is the most frequently used shipping method across all states, with the highest percentages observed in Minnesota (66.67%), Washington (64.44%), and Illinois (63.93%), indicating a strong preference for cost-effective delivery options. Second Class shipping is the second most popular mode in many states, with Florida (24.39%) and Ohio (24.00%) showing notable usage. First Class shipping sees higher adoption in states like Virginia (19.35%), Pennsylvania (18.87%), and New York (18.69%), suggesting a demand for faster delivery options in these regions. However, Same Day shipping has relatively low adoption overall, with the highest usage in Ohio (12.00%), possibly due to local fulfillment centers or urgent delivery needs. These trends indicate that while affordability drives the preference for Standard Class shipping, certain states like Virginia, New York, and Pennsylvania exhibit a willingness to invest in faster delivery methods. Businesses could optimize operations by focusing on efficient Standard Class delivery in states with high adoption, while promoting expedited shipping options in states like Ohio and Virginia, where there is a higher inclination for faster delivery.

The analysis of city-level sales data highlights a stark contrast between top-performing and underperforming cities. A map and bubbles chart were used for this analysis. New York leads the sales chart with an impressive total of $256K, followed by Los Angeles ($176K), Seattle ($120K), San Francisco ($113K), and Philadelphia ($109K). These cities, known for their large populations and economic activity, contribute significantly to overall revenue, likely driven by higher customer bases, diverse market demands, and robust infrastructure. On the other hand, the bottom five cities—Ormond Beach ($2.81), Pensacola ($2.21), Jupiter ($2.06), Elyria ($1.82), and Abilene ($1.39)—generate minimal sales. These cities are likely smaller markets with lower population densities and less commercial activity, leading to limited customer engagement. This disparity suggests that the superstore performs best in urban hubs with strong consumer demand. Expanding marketing efforts, optimizing supply chains, and introducing targeted promotions in lower-performing cities could help improve their sales performance while maintaining dominance in high-revenue cities. On a state level, since two of the top 5 sales generating citiess: Los Angeles and San Francisco are in the state of California, this make California the state with the highest sales revenue, followed by New York. On the other hand, North Dakota is the state with the least revenue.

Finally, using Key Influencers Visual is used to identify what influences sales to increase or decrease. It is discovered that when the sub-category is Tables, the average of sales increases by $432.7 and when the category is office supplies, the average of sales decreases by $278.4.

## Summary
This report provides data-driven insights into sales trends, customer preferences, shipping efficiencies, and geographical revenue distribution, leveraging interactive dashboards and advanced visualizations. By analyzing the superstore dataset, critical business questions regarding seasonal patterns, segment performance, and shipping efficiency are addressed.

Key findings reveal that November and December consistently drive the highest sales, supported by events like Black Friday and Christmas shopping, while February lags due to post-holiday fatigue. The Consumer segment dominates revenue generation, leading monthly sales except in October, when the Corporate segment peaks. Tuesday emerges as the strongest sales day, averaging $259.68, while midweek and weekends demonstrate varied consumer engagement trends. Monday and Friday see the highest number of transactions, highlighting consumer activity at the week's start and end.

Geographically, New York and Los Angeles lead in sales, reflecting urban centers' high consumer demand. Conversely, cities like Ormond Beach and Elyria report minimal sales, attributed to smaller populations and limited commercial activity. California, with two top-performing cities (Los Angeles and San Francisco), is the highest revenue-generating state, while North Dakota ranks the lowest.

Shipping analysis reveals a strong preference for Standard Class delivery, particularly in Minnesota and Washington, while Ohio exhibits the highest use of Same Day shipping, likely due to localized logistics. First Class shipping shows increased adoption in urban states like New York and Pennsylvania, indicating a demand for expedited delivery. The business should focus on improving Standard Class operations while promoting expedited options in states with higher demand.

Finally, key influencers highlight that sales increase when sub-category "Tables" is prominent, while office supplies show a negative impact on revenue. These insights underscore the importance of tailoring marketing, inventory, and shipping strategies to maximize performance, particularly during peak periods and in high-demand urban areas.

## Step-by-Step Process

- **Step 1**: Load data into Power BI Desktop. The dataset is an Excel file.

- **Step 2**: Open Power Query Editor & in the View tab under the Data Preview section, check "Column Distribution," "Column Quality," and "Column Profile" options.

- **Step 3**: By default, profiling is applied to only 1,000 rows, so you need to select "Column Profiling Based on Entire Dataset." It was observed that there were no errors and empty values in any of the columns.

- **Step 4**: Since our report needs the Day of the Week information, which our data does not have, we need to include it. First, we need the name of the days based on the Order Date column, formatted as the first three letters:

Add Day Name: Select the "Order Date" column --> Add Column --> Date --> Day --> Name of Day.
Transform to Three Letters: Select the new "Day Name" column --> Transform --> Extract --> First Characters --> Type 3 in the box.
Second, we need to be able to have the days ranked chronologically, rather than alphabetically. We used the "Day of Week" feature.

Select "Order Date" column --> Add Column --> Date --> Day --> Day of Week.
Go back to the Power BI Desktop: Home --> Close and Apply.
- **Step 5**: Add a straight line to divide the canvas.

Insert --> Shapes --> Line
To make the line vertical instead of horizontal, under "Format Shape" to the right, select "Shape" --> "Rotation" --> Type 90 under "All."
Drag the line down and make it slimmer.

- **Step 6**: Insert a text box.

Type "Sales and Transactions Reports by Period."
Make it Bold, Size 18, Underline, and change the color to #0e1a77.

- **Step 7**: Insert two summary numbers.
Here, we want to include values from our data into what we are typing in text. The first one will be the total sales, and the other one will be the total transactions.
Insert Another Text Box:

Type "Total Sales for the period amount to" --> Click on the "+ Value" --> Type "Total Sales" beneath "How would you calculate this value?" --> Click on the dollar sign to format it to currency --> Click on Save.
At the end of the figure, type "and the Total Number of Transactions is" --> Click on the "+ Value" --> Type "Order ID Count Distinct" beneath "How would you calculate this value?" --> Click on Save.
Format the Text in the Text Box:

Press Ctrl + A --> Select 16 as Text Size --> Make it Bold --> Change the font color to White.
Change the Background of the Text Box:

Under "Format Text Box" --> Background --> Select #0e1a77 under Color.
Rename the Pages:

Rename the page to "Temp", duplicate the page, and rename the duplicated page to "Periodic Report."

- **Step 8**: Create a Line Chart at the top-left of the "Periodic Report" page.
Line charts are ideal for showing trends.
Create the Line Chart:

Go to the Visualizations Pane and select "Line Chart".
In the Data Pane, select "Sales" and "Month" (which is under Order Date).
Turn Off the X-Axis and Y-Axis Titles:

Under Visualizations, go to "Format Your Visual".
Click the "X-axis" dropdown --> Turn off the toggle next to "Title" --> Collapse the X-axis.
Click the "Y-axis" dropdown --> Turn off the toggle next to "Title".
Change the Line Color:

Go to Visualizations --> "Format Your Visual".
Click the "Lines" dropdown --> Navigate to the "Color" subsegment --> Under Color, select #0e1a77.
Edit the Chart Title:

Go to Visualizations --> "Format Your Visual" --> Click on "General".
Under the Title section, go to Text, and edit the input to "How Sales Trended Over the Months."
Add Shadows for Better Visual Separation:

Go to Visualizations --> "Format Your Visual" --> Click on "General".
Under the Effects section, go to Shadow, and turn on the toggle next to it.

Note: Adding shadows helps visually separate the chart from other elements on the canvas, making it easier to identify where the chart begins and ends.

- **Step 9**: Create a Ribbon Chart at the bottom-left of the "Periodic Report" page.
Ribbon charts are best used when we want to show the trends of categories of data that have more than 2-3 items, with the main objective of seeing how their ranking changed over that period of time.
Go to the visualizations pane and select "Ribbon Chart" → On the data pane, select "Sales" and "Month," which is under Order Date.

We want to break it down by "Segment" by dragging "Segment" under "Legend." The visualization now shows how the segment ranking changed over a period of time. For example, we can see that the Consumer segment has always been the highest-earning segment during all the months, except for the month of October, when the Corporate segment was the highest. Also, we see that the "Home Office" segment has been the lowest segment consistently.

Additionally, it is worth noting that the Ribbon chart shows two segments for each month, represented by a bright area and a dark area. For example, in January, we have the data, and the middle segment between January and February shows how January changes into February.

To change the title, go to visualizations → "Format Your Visual" → click on "General" → Under the Title section, go to "Text" and edit the input to "How Customer Segments Rank over the Months."

To add shadows, go to visualizations → "Format Your Visual" → click on "General" → Under the "Effects" section, go to "Shadow" and turn on the toggle next to it.

Turn off the Y-axis titles and values. Under visualizations, go to "Format Your Visual" → click the "Y-axis" dropdown → turn off the toggle next to "Title" → turn off the toggle next to "Value."

- **Step 10**: Create a Stacked Column Chart to show Average Sales by Day of Week.
Column charts are best used to display periodic data.
Go to the visualizations pane and select "Stacked Column Chart" → On the data pane, select "Sales" and "Day Name."
To change the Sales to average instead of Sum → right-click "Sum of Sales" and select "Average."

To make the chart follow the natural order (since it's the day of the week), instead of ascending order: click on the ellipsis at the top of the chart → Sort Axis → click "Day Name" and "Sort Ascending" → click on "Day Name" in the Data pane → On top, under "Column tools," select the dropdown next to "Sort by Column" → select "Day of Week."

Use the "Format Painter" to apply the same format from the line chart to the stacked column chart.

To change the title, go to visualizations → "Format Your Visual" → click on "General" → Under the Title section, go to "Text" and edit the input to "Average Sales by Day of Week."


- **Step 11**: Apply Gradient conditional Formatting to the Stacked Column Chart.
We want to create a gradient of colors that'd go from the lowest to the highest sales. The day of the week with higher sales would have darker colors and those with lower sales would have lighter colors.

 Under visualizations, go to "Format Your Visual" --> On the "Visual", click the "Columns" dropdown --> under "Color", select the fx next to "Color" --> choose "Gradient" as the Format Style --> choose "Sales" under "What Field Should we base this on?" --> Choose "Average" under "Summarization"--> choose #a0a7d8 for the minimum color and #Oe1a77 for the Maximum.

 Using this also helps us to see the range of average sales. Our average sales ranges from $216.3 to $259.68
 
- **Step 12**: Create a Stacked Column Chart to show the Number of Transactions by Day of Week

Copy the initial stacked column chart, and paste it at the bottom-right.
Change the item on the Y-axis from Sales to "Order ID". Ensure that the Order ID is Count (Distinct) by right-clicking on "Count of Order ID" and selecting "Count (Distinct")

 To change the title, go to visualizations --> "Format Your Visual" -->click on "General" --> Under the Title section, go to "Text" and edit the input to "No Transactions by Day of Week".

 Edit the gradient formatting in step 12 by replacing i) "What Field Should we base this on?" with "Order ID" and ii) "Summarization" with Count(Distinct)
 
 Change the title of the range --> go to visualizations --> "Format Your Visual" -->click on "Visual"-->Go the "Legend" and then "Title"--> Change text to "Range"

- **Step 13**: Add Slicers
Create the Year Slicer

Go to the visualizations pane and select "Slicer" --> On the data pane, select "Year" under the "Order Date" hierarchy. 
To change the type of slicer to a "Dropdown", go to visualizations --> "Format Your Visual" --> click on "Visual" --> under "Slicer Settings", go to "Options" and beneath the "Style", use the dropdown to select "Dropdown".

To enforce a selection and ensure that we can only select one year at a time, go to visualizations --> "Format Your Visual" --> click on "Visual" --> under "Slicer Settings", go to "Selection" and turn on the toggle next to "Single Select".

Format the slicer header by underlining it: go to visualizations --> "Format Your Visual" --> click on "Visual" --> under "Slicer Header" and the "Text" subsection, click on U to underline

Turn on Border: go to visualizations --> "Format Your Visual" --> click on "Visual" --> under "Slicer Header" and the "Border" subsection, click on "Bottom" to under the "Border Position".

Create the Region Slicer
copy and paste the "Year" slicer, replace the Year in the field with the "Region".

We don't want to enforce a selection for the Region slicer, so go to visualizations --> "Format Your Visual" --> click on "Visual" --> under "Slicer Settings", go to "Selection" and turn off the toggle next to "Single Select".

Create the Category slicer
copy and paste the "Region" slicer, replace the Region in the field with the "Categpry".

To ensure that the three slicers are well aligned, select first slicer, hold ctrl and select the other two, then go to "Format" and select "Align Left", then select "Distribute Vertically".

- **Step 14**: Create the second report page: Locations Report

Duplicate the "Temp" report page and rename it to "Locations Report"
Change the heading to "Sales and Trasactions Reports by Location"

We need to add the slicers from the Periodic Report to the Locations Report. We can simply copy and paste them, or select any of the slicers --> go to the View tab --> enable "Sync Slicers" --> Under the Sync Slicers pane, check the two boxes next to the Locations Report, to enable viewing and syncing the slicers with the Locations report page. This needs to be done for all the report pages.
        
 - **Step 15**: Create the top 10 and bottom 10 states by Sales visuals on Locations report
 
Go to the visualizations pane and select the "Stacked bar chart" --> resize it to the top-left quarter of the canvas-->On the data pane, select "Sales" and "State".

 To limit the display to the top 10 states: go to the Filters pane--> under State, change the filter type to "Top N" --> under Show Items, select Top, and then type 10 in the box next to it --> drag Sales from the Data pane to the box beneath "By Value" --> select "Apply Filter". Remove the X-axis and Y axis titles as described in step 9. Change the title to "Top 10 States by Sales"

 Copy and paste the top 10 sales chart to the bottom-left part of the canva--> change "Top" to "Bottom" under Show Items --> change title to "Bottom 10 States by Sales". Change the sort order to ascending, by clicking on the elipsis above the chart --> "Sort axis" --> "Sort ascending"

 - **Step 16**: Add a matrix visual to show frequently used Shipment methods
 We want to see in percentages the type of shipment modes we use for our sales transactions for the top 10 states.

Add a Matrix visual: Go to the visualizations pane and select the "Matrix" --> resize it to the top-right quarter of the canvas-->On the data pane, select "Ship Mode" and "State". Drag "Order ID" under the values. change the Summarization to Count (Distinct) by right-clicking "First Order ID" and choosing count(Distinct)

We are more interested in the percentages than in the count.

right-click "Count of Order ID" under the Values --> select "Show values as" --> select "Percent of row total".

Turn off the toggle next to "Row Subtotals" and "Column Subtotals" under visualizations and the "Visual" subsection.

Add the top 10 filter as done in step 16.
 Table heatmap help focus attention on where categories have high and low numbers 

Apply conditional formatting 
Visualizations--> Format Your Visual --> Visual --> Cell Elements --> Turn on the toggle next to "Background Color" --> click to fx--> ensure "What field should we base this on?" is "Order ID" and Summarization is "Count(Distinct)"--> set "minimum color to #a0a7d8 and maximum color to #717bc5 --> Turn on Title and set title to "Percentage of Transaction shipments of the top 10 States"

 To add shadows, go to visualizations --> "Format Your Visual" -->click on "General" --> Under the "Effects" section, go to "Shadow" and turn on the toggle next to it.

- **Step 17**: Add a map visual to show the grographical Location for all the states

Add a Map visual: Go to the visualizations pane and select the "Map" --> resize it to the buttom-right quarter of the canvas-->On the data pane, select "City". 

This gives an error that can be solved by going to to File--> Options and Settings --> Options --> Global --> Security --> tick "Use Map and Filled Map visuals" --> OK --> Remove and add "City" to the Location field

The map shows some cities within Europe, meanwhile the data is for the United States only. To solve that, we need to adjust the data by binding a city exclusively to the US.

go to the Table view--> select "New Column" under the "Column Tools" named City Country-->Type City Country = Orders[City]&",US". This adds the US to all the cities.

Replace "City" with "City Country

Under the data pane, click on the newly created column "City Country" and under "Data Category" at the top, choose "Place". This way all the data points/bubbles on the map show. 

To adjust the bubble sizes to make it reflect the states with larger sales, add Sales to the "Bubble Size" field under visualizations

To add shadows, go to visualizations --> "Format Your Visual" -->click on "General" --> Under the "Effects" section, go to "Shadow" and turn on the toggle next to it


Change the title to "Sales Distribution by Cities"

- **Step 18**: Design a Report Page tooltip

Create a new page named "Segment Tool Tip"
Turn on "Allow use as tooltip" by Visualizations-->"Format Your Report Page"--> Page information --> turn on the toggle next to "Allow use as tooltip"

We need to make the tooltip canvas smaller. Go to Visualizations-->"Format Your Report Page"--> "Canvas Settings"--> change "Type" to "Custom" -->Change the height to 210 and the width to 280 to a tooltip

Add a donut chart
Go to the visualizations pane and select "Donut Chart" -->On the data pane, select "Sales" and "Segment". 

Format the donut chart

Turn off Legend -->  Go to Visualizations-->"Format Your visual"--> "Legend"--> turn off toggle next to legend

Change the detail labels --> Go to Visualizations-->"Format Your visual"--> "Detail Lables"--> "Label Contents" --> select "Category, percent of total". 

Change Title-->  go to visualizations --> "Format Your Visual" -->click on "General" --> Under the Title section, go to "Text" and edit the input to "Customers Segment Shares" --> reduce the size to 10

To link the "Locations Report" to the "Segment Tool Tip"

Go to the "Locations Report" page --> select the first visual "Top 10 States by Sales"--> o to Visualizations-->"Format Your visual"--> click on "General"--> Under options, go to Page and select "Segment tooltip".

- **Step 19**: Enable Drillthrough 
Duplicate the "Locations Report" page and rename it to "Locations Report Drillthrough"

Add "Sales" to the column under Drill through. This way, when we rightclick on the months on the "Periodic Report" page, it takes you to the "Locations Report Drillthrough" page and presents the user with the details for that month.

To edit the title on the "Locations Report Drill Through" page, so that it can show the correct month selected on the "Periodic Report", edit title to "Sales and Transactions Reports by Location for the month of --> click on the "+Value" icon --> under "How would you calculate this value", type "Selected order month"--> click enter and then save.

Format to the month text to the same format as the rest of the text.

Hide the "Locations Report Drillthrough" by right-clickting on it and selecting "Hide Page"

- **Step 20**: Create the "Advanced Analysis" page
Duplicate the "Temp" page and rename it to "Advanced Analysis". Remove the slicers and the page divider and edit the title to ""Advanced Sales Exploration & Analysis"


Add the Decomposition Tree Visual
Go to the visualizations pane and select "Decomposition Tree" -->On the data pane, select "Sales" --> under the "Explain By" field, add "Category", "City","Year", "Quarter", "Month", "Region", "Segment", "Ship Mode", "State", "Sub-Category". 

To make the "Year" the default starting point for the Decomposition tree, click on + sign, and click on "Year". On the left hand side of Year, click on the lock.

Change the color of the bars by going to Format Your visual"--> click on "Visual"--> Under "Bars", go to "Colors" and select  #0e1a77 for the positive bar"Segment tooltip".

Add Key Influencer Visual

Go to the visualizations pane and select "Key Influencers Visual" -->On the data pane, select "Sales" --> under the "Explain By" field, add "Category", "City","Year", "Quarter", "Month", "Region", "Segment", "Ship Mode", "State", "Sub-Category".

- **Step 21**: Go to Insert --> click on the "Buttons" dropdown --> select "Blank" --> Drag to desired Location
To be able to add text, go to"Format Button"--> under Button, select "Style"--> turn on the toggle next to "Text" --> under "Text" type "Ask your own Question"--> change "Font color" to white--> collapse "Text" and go to expand "Border"--> under Color, select white.

to design the second view to be shown when a user clicks on "Ask your own question"

Enable "Selection" and "Bookmarks" pane by going to "View" tab--> click on "Bookmarks" and then click on "Selection"

Duplicate the "Ask your own question" button by copying and pasting it, and ensure they are perfectly aligned on each other

Under the "Selection" pane, rename the new Button (the one on top) to "Go back to default" and the od button to "Ask question button" to be able to differentiate.

Change the text in the new button by going to "Format Button"--> under Button, select "Style"--> turn on the toggle next to "Text" --> under "Text" type "Back to default"

Since we are still creating the second view, under the "Selection" pane, we need to hide "Ask question button", "Key Influencers" and "Decomposition tree" visuals.

Inset the "Q&A" visual by going to Visualizations--> selecting "Q&A" --> turn on shadows as previously done

Capture this page, by going to Bookmarks--> click Add and rename to "Q & A View"

When a user click on the "Back to default" button, the Q&A chart and "Back to default" button should be hidden, while the "Ask question button", "Key Influencers" and "Decomposition tree" visuals should show. We can reflect this under the Selection pane and then Capture this page, by going to Bookmarks--> click Add and rename to "Default View"

To activate the "Back to default" and "Ask your own Question" buttons, click on each button, go to "Format button"--> turn on the toggle next to Action --> using the dropdown next to action, choose "Bookmark" under type and under Bookmark, select "Default View" and "q & A View" respectively. Test using Ctrl+Click

 - **Step 22**: The report was then published to Power BI Service.
 

# Snapshot of Periodic Report page (Power BI DESKTOP)

<img width="707" alt="Image" src="https://github.com/user-attachments/assets/3b727d23-3d38-42aa-8e9c-42454658885e" />

# Snapshot of Locations Report page (Power BI DESKTOP)

<img width="707" alt="Image" src="https://github.com/user-attachments/assets/f5ecbda1-f504-44af-95bf-978d78c25564" />

# Snapshot of Advanced Analysis Default View (Power BI DESKTOP)

<img width="699" alt="Image" src="https://github.com/user-attachments/assets/150d8bc6-3cfb-4d5e-b9bf-5f1faf30e018" />

# Snapshot of Advanced Analysis Q & A View (Power BI DESKTOP)

<img width="708" alt="Image" src="https://github.com/user-attachments/assets/ce26d5ee-7aa2-4c4a-aa19-67ed9492b08e" />

 # Report Snapshot (Power BI Service)

 <img width="956" alt="Image" src="https://github.com/user-attachments/assets/9311c45f-efcc-4e0d-87e7-6a051b551567" />

 <img width="956" alt="Image" src="https://github.com/user-attachments/assets/e846c432-79c7-4d21-a4d9-d38a34f1fc84" />

 <img width="956" alt="Image" src="https://github.com/user-attachments/assets/3775f2cb-c5fc-4bdd-81ab-c9b793d00bd6" />
