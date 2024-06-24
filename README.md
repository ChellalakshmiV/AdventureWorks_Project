# AdventureWorks Project

### Project Overview:

AdventureWorks, a leading global manufacturer specializing in cycling equipment and accessories, has onboarded a Business Intelligence Analyst to bolster their decision-making processes. The primary objective is to monitor Key Performance Indicators (KPIs), including sales, revenue, profit, and returns. This entails a comprehensive analysis of regional performance, product-level trends, and the identification of high-value customers. By leveraging data-driven insights, the management team aims to optimize strategic initiatives, enhance operational efficiency, and sustain competitive advantage in the dynamic marketplace.

### Exploring links:
View Presentation video : [Presentation video](https://www.youtube.com/embed/QQOof5Ru6dQ?si=BvjKm6BhlTAZDmpE)

View Linkedin Engagement  : [LinkedIn engagement](https://www.linkedin.com/posts/chellalakshmi_hello-connections-excited-to-unveil-activity-7194694781392883713-E9u0?utm_source=share&utm_medium=member_desktop)

### Data Sources:

This dashboard seamlessly collects and utilizes data from CSV Files. Dimension Tables Data includes Calendar Lookup, Customer Lookup, Product Categories Lookup, Product Lookup, Product Subcategories Lookup and Territory Lookup. Fact Tables Data which includes Sales data and Returns Data.

### Project Tools:
- Power BI Desktop
- Microsoft Excel
- DAX language

### Steps involved in the data analysis:
1. **Data Extraction:** Gathering all the raw datasets to Power Query.
2. **Data Cleaning:** Checked for duplicate values, errors, null values that were to be removed for proper analysis.
3. **Data Transformation:** Involved addition of extra columns in dataset table in order to calculate certain measures such as “Start of the Week”, “Month”, “Year”, “Average Retail Price” and so on. It also involved steps like rounding off values, fixing data type of various columns.
4. **Data Modelling:** Building one – to – many relationships between the data tables.
5. **Data Processing/Manipulation:** Creating new calculated columns and measures with the help of DAX (Data Analysis Expressions) such as Total Orders, Total Revenue, Total Profit, Total Returns, Return Rate, Revenue Targets, Order Target, etc.
6. **Data Visualization:** Building an interactive dashboard with KPIs, line trend graphs, charts, and a matrix visual.

### A quick overview of the dashboard:
- **Executive View:** Showcased trends in significant KPIs such as Revenue, Profit, Orders & Returns.
- **Geographic View:** Displays the regional performance based on the total orders placed by customers worldwide.
- **Product Details:** Shows product-level trends.
- **Customer Details:** Provides insights on high-value customers.
- **Q & A:** Explored and visualized data using intuitive, natural language prompts.
- **Decomposition Tree:** Visualised data distribution across multiple dimensions which is helpful for root cause analysis.
- **Key Influencers:** Analysed and understood the factors that drive specific metrics or outcomes.
- **Category Tooltip**

### Notable features in my dashboard:

- The bottom left navigation bar facilitates movement across all four report pages.
- The filter icon located at the top left corner of the navigation bar activates a custom slicer panel enabling users to apply high-level filters based on year and region to the Executive View. The arrow at the top of the panel clears all filters.
- Users can drill through to the Product Detail page to access comprehensive information on a specific product.
- Bookmarks are used for clearing all filters both in Executive View and Customer Details pages. Additionally, they are employed to display insights specific to individual customers.
-	Custom Tooltips displaying bunch of KPI’s with area chart for orders.
-	Parameters are applied to enhance interactivity and dynamism in these charts.
-	Smart narrative to show more information about the filtered metric selection.
- Anomaly detection is applied to track revenue trends.
- Q & A visuals offer exploration and visualization of data concerning orders by month and return rate by category.
- Decomposition trees are employed to visualize the distribution of total orders data across multiple dimensions such as category, subcategory, and product names.
- Key Influencers to show categorical and continuous outcomes related to homeownership, alongside customer segmentation and the impact of product cost.

### A few insights from this dashboard:
**Executive Insights:**
- Bikes drive the most revenue, but their return rate is noteworthy.
- Accessories are in high demand.
- Water Bottle 30 Oz is a crowd favourite product.
- Most ordered product type: Tires and Tubes.
- Most returned product type: Shorts.
- A January 2022 revenue fall grabbed attention, followed by stabilization.
- Current month revenue saw a 3.31% increase, with a lower return rate, but total orders dipped slightly.
  
**Geographic Findings:**
- The United States leads in orders.

**Product Findings:**
- It’s a drillthrough page and now I found details about the most ordered product Water Bottle – 30 oz which has 404 current month orders. 
- A 10% price bump in June 2022 led to peak revenue, driven by original profit, which is easily noticeable with the help of numeric range parameters.
- From June 2021 to June 2022 showcased a consistent uptrend in total profit that is from 13-09-2021 to 06-06-2022, profit rose by $178.

**Customer Findings:**
- Shan is the top customer who orders, which is responsible for the company's most revenue.
- Working professionals placed the majority of orders.
- From 2020 to 2022, the average revenue per customer declined by $1560.
- The second half of 2021 witnessed a surge in total number of customers.

**Actionable Steps:**
1. **Optimize Bike Returns:**
- **_Issue:_** Bikes drive the most revenue but have a noteworthy return rate.
- **_Recommendation:_** Implement a more rigorous quality check and improve customer support for bikes. Offer detailed assembly guides or professional assembly services.
- **_Impact:_** Reduced bike return rate by 5-10%, resulting in a net revenue increase from bikes by up to 7%.

2. **Capitalize on Accessory Demand:**
- **_Issue:_** Accessories are in high demand.
- **_Recommendation:_** Expand the range of accessories and bundle them with popular products.
- **_Impact:_** Increased accessory sales by 10-15%, boosting overall revenue.

3. **Address Revenue Dips:**
- **_Issue:_** January 2022 saw a revenue fall.
- **_Recommendation:_** Launch targeted promotions or discounts in January to counteract the seasonal dip.
- **_Impact:_** Stabilized January revenue with a potential increase of 5%, ensuring consistent monthly revenue.

4. **Enhance Customer Relationships:**
- **_Issue:_** Shan is the top customer.
- **_Recommendation:_** Implement a VIP program for top customers to increase retention and average order value.
- **_Impact:_** Increased revenue from top customers by 10%, improving customer loyalty and lifetime value.

5. **Strategic Price Adjustments:**
- **_Issue:_** A 10% price bump in June 2022 led to peak revenue for Water Bottle – 30 oz.
- **_Recommendation:_** Regularly review and adjust prices based on market demand and cost analysis.
- **_Impact:_** Optimized pricing strategy leading to balanced revenue growth and maintaining profit margins.

In summary, the company should focus on tackling bike return rates, studying the December 2021 revenue spike, optimizing products and pricing, retaining high-revenue customers, exploring The United States expansion, and maintaining KPI-driven performance.

Below are the data model and all other views of my dashboard report.

### Data model:
![Data model](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/f22dbd5b-67a2-4bfb-8356-235482aff6c1)

### Executive View:
![Executive View](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/76d8e9a0-d7e3-49c3-b82d-732e25b66659)

### Geographic View: 
![Geographic View](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/fe44e0c9-7fc1-4366-aa51-029961cc450d)

### Product Details:
![Product Details](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/866cc55c-b5ef-4e19-a199-073048ce405f)

### Customer Details:
![Customer Details](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/1c6920a0-6f0a-449c-bbc4-ddb4f0dcb271)

### Q & A:
![Q   A](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/b5811b84-3159-43fc-ba95-c0cb102bc246)

### Decomposition Tree:
![Decomposition Tree](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/c36031bc-ad66-441f-83c2-40e9a4316df5)

### Key Influencers:
![Key Influencers](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/4d35ba75-ed43-406c-9739-aa083e6ebf64)

### Category Tooltip:
![Category Tooltip](https://github.com/ChellalakshmiV/AdventureWorks_Report/assets/162456368/b2b40f65-dec4-4a39-9202-54fdce79e37e)




