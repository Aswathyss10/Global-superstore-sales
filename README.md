*Global-superstore-sales*

The company operates in multiple countries, and this dashboard uses data from 2011 to 2014 to track revenue sources and key performance indicators across various dimensions such as region, product category, and customer segment. The insights support data-driven business decisions and help in identifying growth opportunities.

*Dataset*

The dataset includes

Product Details:Category,Sub-Category,Product ID,Product Name

Order Information:Order ID,Order Date,Ship Date,Ship Mode

Customer Information:Customer ID,Customer Name,Segment

Location Details:City,State,Country,Region,Market,Market2

Sales & Performance:Sales,Profit,Discount,Quantity,Shipping Cost

*Key Statistics:*

Total Records:51291

*Tools*

Tools:Power Bi

*Exploratory Data Analysis (EDA)*

The analysis involved:

Data Cleaning:
.Dropped the irrevelant coloumns and null values 
.Change the name for better readablity
.Change the data type to the original form
.Created a new column called Date using the CALENDAR() function


*Key insight*
Region: North America has the highest sales.
Top Selling Product: Apple's full-size smartphone is the top-selling product.
Category: Technology has the highest sales among other categories.
Time Period: November 2014 has the highest sales.
Product Shipment: Most products shipped are based on the standard class.
Segment: The number of products per segment is classified under Consumer

*Visualizations:*

Created four KPI cards showing:Total Revenue,Total Profit,Monthly Sales Growth (compared to previous month)

Developed two additional KPIs:Revenue vs. Target Revenue,Profit vs. Target Profit

Line Chart created to show the monthly sales trend over time.

Filled Map used to visualize sales distribution across countries.

Table included to display cumulative (YTD) sales for a quick overall summary

Donut Chart shows Product Count by Shipping Mode.

Bar Chart displays Top 10 Products by Sales.

Multi-row Card presents Total Sales by Product Category.

Treemap visualizes Sales by Sub-Category.

Funnel Chart shows the Number of Products per Customer Segment.

Comparison Tables highlight:Current Sales,Previous Period Sales,Sales Growth %

*Acknowledgments*

Dataset sourced from Kaggle.



