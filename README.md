Sales Performance Analysis using Tableau
Domain: - Ecommerce
Description: -
The head of Product Management of a retail products company, is responsible for determining
which products his company should continue to offer for sale and which products should be
discontinued from the company’s product catalogue.
Objective: -
To build a dashboard that will present monthly sales performance by product segment and product
category to help client identifying the segments and categories that have met or exceeded their
sales targets, as well as those that have not met their sales targets.
We will use the datasets provided to us for completing the following analysis tasks
using Tableau: -
1. Create a bullet chart with Category and Segment dimensions and Sales measures.
2. Blend the data with the Saved Sample - Sales Target data set to bring in the Sales Target
measure.
3. Colour code the chart to identify Categories and Segments that are above or below target.
4. Add the year of sales to the view to identify trends and outliers.
5. Add a filter so that the user can select one, more than one, or all years.
Steps: -
1. First, we will upload the Sample_Superstore excel file to tableau and select the Orders sheet
from it for visualization.
2. Then, we connect a new data file to tableau i.e., Sales_Target, both the files will be blended.
3. Now, category, segment, order date (in month format), sales measure from sample superstore
dataset and sales target from sales target dataset, these two measures are selected, then from
show me option, we create a bullet chart.
4. A bullet chart will be created that will show, sales, sales target and also 60% to 80% of
average sales values.
5. But, the axis will represent Sales Target, but we need to se Sales on the axis, so right click on
the below axis and select Swap Reference Line Fields which will give us sales on the below
axis.
6. We need to differentiate the fields that are meeting the sales target and that are lacking, so we
can do this by adding a calculated field. The calculation will give us the information whether the
sales target is achieved or not by simple visual representation. So, go to analysis dropdown
and select create calculated field and enter the following formula
Sales Target Achieved or Not
SUM ([Sales Target (Sales Target)])<SUM([Orders (SampleP - Superstore)].[Sales]
7. We will see a Legend on the top right part of the visualization with two colours stating whether
the target is achieved or not and also the bullet chart will have the graphical representation
according to these colours.
8. As we need to see sales year wise also, we will drag the order date to the filters option and
then select years>all>apply>OK.
9. Right click on the Order Date capsule in the filter card and select show filter.
10. A filter will be displayed on the top right side with option to toggle between different years.
11. Our required visualization is completed and we can use it to analyse the sales performance.# Tableau
Tableau Projects
