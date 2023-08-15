# Sales-Data-Analysis-on-Jessie's-Superstore

# **Introduction**
This analysis is centered on the determination of Jessie's superstore product revenue across the united states, its regions, states and cities. Excel spreadsheet tools will be extensively used including pivot table functions and pivot chart to solve this analysis. 

# **Activity**
1. The total revenue yield across the category
2. The total profit generated across the regions
3. The Product with the highest revenue across the sub-category
4. The Product with highest profit yield across the sub-category
5. The frequently used ship mode for the transport of products sold.
6. The sales of products across the segment.
To determine the total revenue, total profit, total number of products sold and total discount issued, KPI's and Slicers where also created to streamline the visuals as desired.

# **Skills Demonstrated**
1. Data Processing
2. The use of Pivot Tables and Pivot Charts
3. The use of Slicers

# **Data Processing**
The superstore dataset was first processed by adjusting the column headers to fit appropriately into the column by highlighting the entire top column row, then double-clicking a section this automatically adjusted evenly to fit the column text properly. The entire data was later converted into a table format, by clicking a part of the cell, then pressing 'Ctrl A" to highlight all dataset then I pressed 'Ctrl T' to convert the data into a table set. The first row containing all the headers were also freezed by clicking on the 'Freeze panes' in the 'view ribbon' then I selected 'freeze top row' this kept all my headers static, when I scroll up or down. Then I pressed the 'Ctrl + Down key' buttons to get to the last data column, this visualized the total number of row filled with the dataset, while I changed the 'Ordered Date' and 'Ship Date' format to the 'DD/MM/YY' format. Below is a screenshot of the raw dataset and the cleaned dataset.

<img width="917" alt="Jessie Superstore Raw Dataet" src="https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/e4544273-b3f9-44b0-bcfd-62a4bdec5148">


<img width="951" alt="Jessie's Superstore Cleaned Data" src="https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/c3c73dd6-6e75-42a1-935e-06b7582ad8ff">


# **The use of Pivot Tables**

The first activity on my task was to determine the total revenue across the category sales column of the superstore data. This was calculated and visualized by the help of the Pivot Table tools. First I clicked on the 'insert ribbon', then selected 'Pivot tables' while one of the table cells were highlighted, this popped-up a prompt box in which I selected 'existing worksheet', as where I wanted the pivottable to be placed. Then a Pivottable fields box also popped-up with the title of all the column headers of my superstore data table, then I dragged the 'Category' column to the 'row' section and the 'sales' column to the value section, the pivot table was formed then I clicked the drop down arrow on the category column to filter the sales column from 'A to z Ascending', this arranged the category values in order of the ascending value. The pivot table can be visualized on the screenshot below. 
To create a Pivotchat for the first activity, I highlighted a cell on the pivot table formed, then clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the column chart, A pivot chart was formed representing the category data in bars,  I clicked on the 'chart elements' to edit the chart, by unchecking the 'primary verticals', the gridlines, the field buttons and the 'legends', I also edited the colours of the column bars, with the highest sales having a dark blue colour, while the lower values had light blue colours. This visualized the highest sales product in the category market. I also inserted a text-box to describe the chart. From this pivotchart it was deduced that the total revenue was generated mainly from the sales of Technology products. The pivotchart can be visualized below.

![Pivot Table 1](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/4afa67f8-af7e-46b5-919b-c11dd4688542)

![Total Revenue across Category](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/e8035a1b-5347-4bc8-904f-5ab3109958aa)


The Second activity this task was to determine the total profit yield across regions column of the superstore data. To carryout this task, I calculated the total profit using a pivottable. A cell on the cleaned superstore data table was highlighted, then I clicked on the 'insert ribbon', then selected 'Pivot tables', a prompt box popped-up, in which I selected 'existing worksheet', that is where I wanted the pivottable to be placed. Then a Pivottable fields box also popped-up with all headers of my superstore data table, then I dragged the 'region' column to the 'row' section and the 'profit' column to the value section, the pivot table was formed then I clicked the drop down arrow on the region column to filter the profit column from 'A to z Ascending', this arranged the profit generated by each region in the ascending order. The pivot table can be visualized on the screenshot below. 
After creating the pivot table, a Pivotchart was formed from the same pivot table by highlighting a cell on it, then I clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the column chart, A pivot chart was formed representing the region data in bars,  I right-clicked on the region axis to remove the field buttons, then I also right-clicked on 'chart elements' to edit the chart, by unchecking the 'primary verticals', the gridlines, and the 'legends', I also edited the colours of the column bars, with the highest profit having a dark blue while lower values are to have light blue colours. This visualized the region with the highest profit yield. I also inserted a text-box to describe the Chart. From this pivotchart we can visual the total profit across regions and the West region with the highest profit yield. See the screenshot below.

![pivot table 2](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/d32ea2de-3f12-40d8-9bc4-132f85fc47a1)

![Total Profit across regions](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/518aaa55-4b21-4d32-b418-2efb06e14dfc)


To determine the product with highest revenue across sub-category, I calculated the total revenue using a pivottable. Firstly, I inserted a new Pivot tables from the 'Insert Ribbon', a prompt box popped-up, in which I selected 'existing worksheet', as where I wanted the pivottable to be placed. Then a Pivottable fields box popped-up with all headers of my superstore data table, then I dragged the 'sub-region' column to the 'row' section and the 'sales' column to the value section. This developed the summed values of all the products sold in the sub-category, then I filtered the summed sales value by right-clicked on the drop-down arrow on the sub-category section, and used the 'values filter' to produce only the 'top 5' sales values of the sub-category, I also filtered the sales column from 'A to z Ascending', this arranged the sales value of the sub-category column in an ascending order. The pivot table can be visualized on the screenshot below. 
After creating the pivot table, a Pivotchart was formed from the same pivot table by highlighting a cell on it, then I clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the bar chart, A pivot chart was formed representing the data in bars,  I right-clicked on the chart elements to remove the primary horizontal, the field buttons, the gridlines, and the 'legends', I also edited the colours of the bars. The top 1 value having a dark blue colour, while lower values are to have lighter blue colours. This visualized the sub-category product that made the highest sales to be 'phones'.I also inserted a text-box to describe the Chart. See the screenshot below.


![Pivot Table 3](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/c6ef61e9-b4d1-444c-ab93-44b348db421f)

![Product with highest revenue across sub-category](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/d05b41b4-b923-4703-a9f6-1321f5e1fc71)


To determine the product with highest profit across sub-category, I calculated the total profit by inserting a new Pivot tables from the 'Insert Ribbon, a prompt box popped-up, in which I selected 'existing worksheet', where I wanted the pivottable to be placed. Then a Pivottable fields box popped-up with all headers of my superstore data table, then I dragged the 'sub-region' column to the 'row' section and the 'profit' column to the value section. This developed the summed profit values generated in the sub-category, then I filtered the summed profit values by right-clicked on the drop-down arrow on the sub-category section, and used the 'values filter' to produce only the 'top 5' profit values of the sub-category, I also filtered the profit column from 'A to z Ascending', this arranged the profit values of the sub-category column in an ascending order. The pivot table can be visualized on the screenshot below. 
After creating the pivot table, a Pivotchart was formed from the same pivot table by highlighting a cell on it, then I clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the bar chart, A pivot chart was formed representing the data in bars,  I right-clicked on the chart elements to remove the primary horizontal, the field buttons, the gridlines, and the 'legends', I also edited the colours of the bars. The top 1 profit making product having a dark blue colour, while lower values are to have lighter blue colours. This visualized the product with highest profit yield in the sub-category to be 'copiers'. I also inserted a text-box to describe the Chart. See the screenshot below.

![Pivot Table 4](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/e2e7664b-52f3-4f17-a479-ee87bb591652)

![Product with highest profit yield across sub-category](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/b913c7b8-d610-45da-b548-2dd40b411228)


To determine the most frequently used shipping mode for the transport of products sold, I inserted a new Pivot tables from the 'Insert Ribbon, a prompt box popped-up, in which I selected 'existing worksheet', where I wanted the pivottable to be placed. Then a Pivottable fields box popped-up with all headers of my superstore data table, then I dragged the 'ship mode' column to the 'row' section and the 'sales' column to the value section. This developed summed sales values, I changed the 'sum' function to 'count' function, then I filtered the Number of sales values by right-clicked on the drop-down arrow on the 'ship mode' column, then I filtered the 'number of sales' column from 'A to z Ascending', this arranged the number of sales values of the ship mode column in an ascending order. The pivot table can be visualized on the screenshot below. 
After creating the pivot table, a Pivotchart was formed from the same pivot table by highlighting a cell on it, then I clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the column chart, A pivot chart was formed representing the data in column bars, I right-clicked on the chart elements to remove the primary vertical, the chart title, the field buttons, the gridlines, and the 'legends', I also edited the colours of the column bars with the frequently used shipping mode having a dark blue colour, while other shipping mode had lighter blue colours. This visualized the frequently used shipping mode as the standard class. I also inserted a text-box to describe the Chart. See the screenshot below.

![Pivot table for Frequently used mode for the tranport of products](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/00d0cf75-2a7b-46cd-9acc-edd1bb7f3360)
![Most Used Shipping Mode](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/ef31b762-eb94-412a-a226-227547a18d5e)


To determine the sales of products across the segment I inserted a new Pivot tables from the 'Insert Ribbon, a prompt box popped-up, in which I selected 'exist worksheet', where I wanted the pivottable to be placed. Then a Pivottable fields box popped-up with all headers of my superstore data table, then I dragged the 'segment' column to the 'row' section and the 'sales' column to the value section. This developed summed sales values, then I filtered the sales values by right-clicked on the drop-down arrow on the 'segment' column, to appear in 'A to z Ascending' order, this arranged the sales values of the segment column in an ascending order. The pivot table can be visualized on the screenshot below. 
After creating the pivot table, a Pivotchart was formed from the same pivot table by highlighting a cell on it, then I clicked on 'pivotchart' on the 'insert ribbon' this provided a drop-down box with different chart tables, then I selected the pie chart, then a 'doughnut' chart, A pivot chart was formed representing the data in doughnut chart, I right-clicked on the chart elements to remove the chart title and the 'legends', I also edited the colours of the doughnut chart with the highest sales value by segment, having a dark blue colour, while other segment had lighter blue colours. It can be visualized that the segment with the highest sales, is the customer segment. I edited the labels of the doughnut chart showing the market values by each segment and their individual percentage. See the screenshot below.

![Pivot table for Sales by segment](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/de65bf42-2596-4fb9-9a3b-0acb80289ee5)
![Pivotchart for sales by segment](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/b7c79676-ea31-4c8d-87f3-92037819ee42)

I developed Key Performance Indicatiors using the calculated total revenue values, total profit values, total number of products sold and total discount issued on each product. The individual KPI was created using the 'insert ribbon' to insert a rectangular shape, then I inserted a text-box into the rectangular shape. I clicked on the shape, to aligned the text to the bottom-right, then on the formula bar I type '=', then went to the worksheet where my KPI values where formed then clicked on the result for total revenue, then I clicked 'enter', this automatically inserted the total revenue value into the shape. Then I editted the text-box to have the 'Total Revenue' tag. I also created KPI for the total profit, total number of products sold and the total discount usinig the procedure. See the below screenshot.

![Screenshot 2023-08-15 135621](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/d6133c78-aceb-4ae7-9a15-048c336f9116)
![Screenshot 2023-08-15 135647](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/2fd941b9-f009-4956-8dd5-dd768949e9cc)


I introduced slicers in my report to streamline my visuals in the category section and the segment section. I clicked on a cell in my cleaned superstore data then I went to the 'insert ribbon' to click on 'insert slicer', then a dropdown box popped up containing all titles of my table column headers, then I checked 'category' and 'segment', this auntomatically brought out two slicers of the columns I selected. The slicer helped me to easily filter my pivottable and my pivotchart.

![Slicers](https://github.com/Jessie-Watt/Sales-Data-Analysis-on-Jessie-s-Superstore/assets/140435577/da401e11-7016-45f1-931a-cf08ac3e67d6)

# **Conclusion**

This project broadened my personnal practice on how to make use of slicers in my report and how to introduce key perfomance keys in my report. 
