# Vrinda Store Annual Report 2022 – Excel Data Analysis Project

This project analyzes Vrinda Store’s 2022 sales data using Excel.
It includes data cleaning, data processing, pivot table analysis, and a fully interactive dashboard.

## Dataset used 
- <a href = "https://github.com/komalsatpute/Excel-Projects/blob/main/Vrinda%20Store%20Data%20Analysis.xlsx">Dataset View</a>

## Dashboard Preview
### Dashboard 
- <a href = "https://github.com/komalsatpute/Excel-Projects/blob/main/dashboard%20screenshot.PNG">Dashboard View</a>

### Project Workflow
#### 1. Data Cleaning

Performed thorough cleaning to prepare the dataset:
Checked Order ID, Customer ID, SKU, Amount, Quantity for:
Duplicates , Null values , Incorrect formats

Standardized inconsistent values:
Gender: M, Men → Men and W, Women → Women
Quantity: Converted values like one, two, 1, 2 → numeric only

Verified:
Age contains only numeric values
Date column has correct date format
Category, Channel, Size fields contain valid non-null values

After cleaning, the dataset was consistent and ready for further processing.

#### 2. Data Processing

Created new columns to support business analysis.
i. Age Group
Categorized customers into Teenager, Adult, and Senior

ii. Month Extraction
Extracted month name from the full date

#### 3. Data Analysis (Pivot Tables)

Used Pivot Tables to answer business questions:

i. Monthly Orders vs Sales 
SUM of Amount,
COUNT of Order ID,
Combo chart using monthly data,
Converted values to millions using format

ii. Men vs Women Purchases
Pie chart showing total sales contribution
Women: 64%, Men: 36%

iii. Order Status Distribution
Delivered, Returned, Cancelled, Refunded
Visualized using Pie Chart

iv. Top 5 States by Sales
Used “Top 10 Filter” → customized to Top 5
Maharashtra ranked highest

v. Age vs Gender (Order Count)
Compared teenagers, adults, and seniors by gender

vi. Channel Contribution
Converted to % of grand total
Amazon contributed the highest sales

#### 4. Interactive Dashboard

Designed the final dashboard sheet with:
a) Orders vs Sales chart
b) Men vs Women pie chart
c) Order Status pie chart
d) Top 5 States bar chart
e) Channel Contribution pie chart
f) Age vs Gender bar graph

Added Slicers:
Month , Category , Channel

### Key Insights

A. March had the highest sales and order volume.

B. Women (64%) purchased more than Men.

C. Amazon is the top-performing channel.

D. Adults made the highest number of purchases.

E. Maharashtra contributed the most to total sales.

F. 92% orders were successfully delivered.


<img width="1314" height="438" alt="dashboard screenshot" src="https://github.com/user-attachments/assets/bcd9dbc6-141e-4f76-9605-9251b6728933" />
