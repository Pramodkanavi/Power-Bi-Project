# Power-Bi-Project
   This project provides a comprehensive analysis of the operational and sales data from ShopNest Store, a leading e-commerce marketplace in Portugal, covering Q3 2016 to Q3 2018. The analysis focuses on key performance metrics, including sales trends, delayed orders, payment methods, product ratings, and state-wise performance, using a structured Power BI dashboard.

### Data Sources:
- To ensure seamless operations and optimize customer satisfaction, the store has maintained a comprehensive transaction data sheet, containing detailed information from third quarter 2016 to third quarter 2018.

### Tools and Technique:
Microsoft PowerBi was the tool used for the data cleaning, data processing, data modelling, data analysis, data visualization.

### General Approach Followed for all Datasets:
- Open the PowerBi Deskop application in the laptop.
- Import Customers,Geolocation,Order_items, Order_payments, Order_reviews, Orders, Products, Sellers, Product Categories datasets to the application.
- To clean the data, we need to click on transform in home tab which will take us to the Power pivot.
####	In Power pivot for each Datasets: -
- First and foremost is to check for heading or else promote headers.
- Check the Datatype of the columns then specify the datatype of each column, specially check with the date columns and change the type according to the need.
- Identify the Primary keys for each dataset and then remove the duplicate, error, empty rows in the primary key column.
- Click on close and apply so the changed dataset it will load to PowerBi Desktop.
- In PowerBi desktop in data pane we can see the loaded datasets click on the column of the datasets then we can see the column tools ribbon, in which we can define Datatype, Format, Summarization, Data Categories for the columns repeat the same function to all the datasets to clearly define which type of data it is specially for the zip code, latitude, longitude, state, country etc.
- In Powerbi desktop we need to establish a connection between datasets that contain Primary key of one table to the Foreign Key that is present in another table in a snowflake schema.
- To get a desired result we should make sure that relationship we are establishing is one to many or one to one, not many to many connections. We can see the details of the relationships in the Model view.

### Key Insights:
#### Top-Selling Categories:
Health & Beauty products lead sales consistently, followed by Watches & Gifts and Bed & Bath products.
#### Delayed Orders Analysis:
Bed & Bath products experienced the highest delays, with delays peaking in March and August.
#### Monthly Order Trends:
August sees the highest order volumes with timely deliveries, while March has the most delays.
#### Payment Method Trends:
Credit cards dominate payments (73.9%), followed by boleto (19%).
#### Product Ratings:
Top-rated: Fashion for children, CDs/DVDs, and sports apparel.
Lowest-rated: Security services, office furniture, and home comfort products.
#### State-Wise Sales Performance:
SP leads in sales, with states like PR, MG, and RJ following.
#### Seasonal Patterns:
Health & Beauty products consistently drive sales across all quarters.
#### Revenue Trends:
Revenue peaked in Q2 2018 at €2.97M but dipped in Q3 2018 to €1.84M.


