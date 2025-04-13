# Sales_Project_VindraStore

## Table of Content
- [Project Objectives](#project-objectives)
- [Columns Details](#columns-details)

## Project Objectives

Vindra store wants to create an annual sales report for 2022. So that Vindra can understand their customers and grow more sales in 2023.
Project Aims- to create a dynamic and interative Excel dashboard

I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze the 
data.This process involved several stages, including data preprocessing, data cleaning and data visualization.

## Data Sources
Sales Data: The primary dataset used for this analysis is the "Vindra Store Data Analysis.csv", containing
detailed information about each sales made by the store.

## DATASET DESCRIPTION

### Dataset structure
- Number of Records(Rows):  31048
- Number of Attributes(Columns): 18

### Columns Details
![image](https://github.com/user-attachments/assets/91aebcc6-8394-4f25-a3f0-ab24eaf32dba)
-	Order ID: unique identifier to distinguish individual orders in a dataset
-	Cust ID: unique identifier assigned to each customer
-	Gender: gender identity of individuals (Men or Women)
-	Age: numerical value of an individual's age
- Date: specific day a transaction occurred or was recorded
-	Status: current state of a transaction, such as "Delivered” or "Returned."
-	Channel: medium or platform through which a sale was made
-	SKU: (Stock Keeping Unit) is a unique code assigned to tracking 
-	Category: grouping of products based on shared characteristics
-	Size: measurements of a garment, such as "S," "M," "L.
-	Qty: number of units of a product sold in a transaction.
-	Currency: type of monetary unit used, such as "USD," "EUR," or "INR."
-	Amount: total monetary value of a transaction
-	Ship-city:
-	refers to the city where a product is delivered or shipped
-	Ship-state: state or region where a product is delivered or shipped
-	Ship-post-code: postal code or ZIP code of the delivery address




###	Explorary Data Analysis

EDA involves exploring sales data to answer key questions, such as

- Compare the sales and orders using single chart.
-	Which month got the highest sales and orders?
-	Who purchased more men or women in 2022?
-	What are different order status in 2022?
-	List top 5 states contributing to the sales?
-	Relation between age and gender based on number of orders
-	Which channel is contributing to maximum sales?

### Excel Tools Used

#### 1.Data Analysis Tools
These tools help summarize and analyze data:
#### 1.Formulas: Essential for calculations and data analysis. Commonly used formulas include:
-	SUM, AVERAGE, COUNT: For basic calculations.
-	IF, IFS: For conditional logic.
-	VLOOKUP, HLOOKUP, XLOOKUP, INDEX-MATCH: For finding data in tables.
-	TEXT, CONCATENATE: For text manipulation.
-	ROUND, TRUNC: For controlling numerical precision.
#### 2.PivotTables: Summarizes large datasets with dynamic filtering and grouping capabilities.
![image](https://github.com/user-attachments/assets/138df384-c903-40ff-84f5-96f72e7f9096)


#### 3. Visualization Tools
To create the graphical elements of the dashboard:
-	Charts: Displays data visually. Common types include:
-	Bar/Column Charts: For comparisons across categories.
-	Line Charts: For trend analysis over time.
-	Pie Charts: For proportions.
-	Scatter Plots: For identifying correlations.
![image](https://github.com/user-attachments/assets/00e7520f-5f2a-4550-b8a8-46a5037c2b53)
![image](https://github.com/user-attachments/assets/9c91c3c3-09b7-4bb1-8049-50b97ec9637d)


#### 4. Interactivity Features
These features make the dashboard user-friendly:
-	Slicers: Filter PivotTables and PivotCharts interactively.
-	Dropdown Menus: Created using Data Validation for user selection.
-	Buttons and Hyperlinks: Add navigation between sheets or sections of the dashboard.
-	Checkboxes/Toggle Buttons: Adds functionality for turning features on/off.

#### 5. Advanced Tools for Professional Dashboards
For more sophisticated dashboards:
-	Power Pivot: Handles large datasets and builds complex data models with relationships.
-	Dynamic Arrays: Functions like FILTER, UNIQUE, SORT enable real-time updates.

#### 6. Layout and Design Features
To make the dashboard visually appealing and intuitive:
-	Grid Layouts: Align elements like charts and tables neatly.
-	Grouping and Hiding Rows/Columns: Reduces clutter by hiding unnecessary details.
-	Cell Formatting: Enhances readability with font styles, borders, and alignment.


## DASHBOARD OVERVIEW 
Dashboards are essential tools in data analysis, serving as a centralized platform for visualizing, monitoring, and interpreting key data insights.

![image](https://github.com/user-attachments/assets/0282bb3c-cbd6-44a8-90f3-e12ade3025ff)


## Result/Findings
The analysis result is summarized as follow:-
-	Women are more likely to buy than compared to men (~65%)
- Maharashtra, Karnataka and Utter Pradesh are the top 3
-	Adult age group (30-49 yrs) is max contributing (~50%)
-	Amazon, Flipkart and Myntra are max contributing.

## Recommandation
Target women customers of age group(30-49 yrs) living in Maharashtra, Karnataka and Utter Pradesh by showing Ads/Coupens/Offers on Amazon, Flipkart and Myntra 
