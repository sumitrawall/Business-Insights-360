# Business-Insights-360
## About AtliQ Hardware
AtliQ Hardware manufactures and sells hardware like PC, Mouse, Printers etc to multiple companies across the world. AtliQ’s customers are companies like Croma, Amazon, Neptune, Staples, Walmart etc.
These customers are of two types – Physical Stores and E-commerce platforms.

## Problem Statement
AtliQ Hardware is struggling to do good business in Latin America.
So far all the decisions that AtliQ took have been based on some surveys and intuitions.

The company was doing some analysis using MS Excel files because of limited data. Now that the company has grown and has plenty of data to analyse, the management has decided to hire a Data Analyst. The management wants Data Analysts to utilise this data to make accurate and informed decisions.

## Management’s Dashboard Requirements
The management wants to see these reports in the Power BI Dashboard:

**Finance View** – This will show the profit and loss statements across different products, markets, customers etc.

**Sales View** – To display the top-performing and bottom-performing customers with different key metrics.

**Marketing View** – Similar data as of Sales View but product based instead of customers.

## Project Execution
### Step – 1
The first step was to load the data into MySQL Database and connect it to the Power BI.

### Step 2
Review and deleted the Database relationship created by Power BI by default.
Also, creating the required dimension table in Power Query.

### Step – 3
Data validation using some tables in Power BI and matching the values with the data provided.

### Step – 4
Data Transformation. For example, creating a Last Sales Month Reference table. So the last sales month reference table will be dynamic and will change after every sale.

### Step – 5
Created calculated columns in Power Query like fiscal_year and merged the tables.

### Step – 6
Data Modelling – Data modelling is a connection between different tables using a common table between them. In this project, Start Schema is used for Data Modelling where all the dimension tables were connected with Fact tables.

### Step – 7
Created calculated columns using more than 40 DAX formulas (Formulas listed at the bottom). After the columns were created, verified them in either MySQL or Excel file.

### Step – 8
This was the last step before start creating the design work and building the dashboards. This step was to optimize the report to reduce the report/file size. This is an important step which helps in reducing the file size so that is easy to share and access by users.

## Building The Dashboard
I have created 5 different report views in this report which serves the need of various stakeholders. Let’s have a look at each of them.

The first page of the report is a home page with the navigation to all other views and a summary of each page so a user can directly access the report they need to look at.

### Finance View
The Finance View shows the P & L statements. The Top Performing and Bottom Performing products and customers. Different product segment performances in different regions. The most important metric here is it shows the Year on Year comparison of P & L in a single view.



### Sales View
The sales view is for the sales team to drill down the performance of each product and customer in individual regions. Similar to the finance view it does have the same filters to provide in-depth analysis of sales performance.

### Marketing View
Marketing View contains Gross Margin %, Net Profit %, Operational Expenses and Cost Of Goods Sold which are important financial stats that marketing should be aware of. This helps in deciding the marketing budget for each product in a particular market. Marketing will also be aware of the potential customers and potential market and whether there is a scope for business or not.
