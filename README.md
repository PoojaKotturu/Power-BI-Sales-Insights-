# Power BI Sales Insights

## Project Description

This project provides insights into sales data using Power BI. It includes data visualizations and dashboards that help in understanding sales performance, trends, and key metrics. The project aims to enable data-driven decision-making for sales teams and stakeholders.

## Project Links

- [Project on NovyPro](https://project.novypro.com/NPz06V)

## Table of Contents

- [Project Description](#project-description)
- [Project Links](#project-links)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Skills Enhanced](#skills-enhanced)
- [Dashboards Overview](#dashboards-overview)
  - [Basic Measures](#basic-measures)
  - [Time Intelligence Part 1](#time-intelligence-part-1)
  - [Time Intelligence Part 2](#time-intelligence-part-2)
  - [Time Intelligence Part 3](#time-intelligence-part-3)
  - [Ranking](#ranking)
  - [Total Scenario Sales](#total-scenario-sales)
  - [Top Clients](#top-clients)
  - [DAX or No DAX](#dax-or-no-dax)
  - [Customer Classification](#customer-classification)
  - [Variables and Weekdays](#variables-and-weekdays)
  - [Final Report](#final-report)
  - [Navigation](#navigation)
  - [Best and Worst Customer Sales Thresholds](#best-and-worst-customer-sales-thresholds)
  - [Data Model](#data-model)
    
- [Business Related Terms](#business-related-terms)
- [Major Power BI Skills Learned and Applied](#major-power-bi-skills-learned-and-applied)
- [Dashboard Highlights](#dashboard-highlights)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Installation

To view and interact with the Power BI dashboards locally, follow these steps:

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone this repository to your local machine using:
   ```bash
   git clone <repository-url>
   ```
3. Open the `.pbix` file in Power BI Desktop.

## Usage

The dashboards in this project can be used to:

- Analyze sales performance over different periods.
- Identify top-performing products and regions.
- Track sales trends and make data-driven decisions.
- Monitor key sales metrics and KPIs.

## Data Sources

The data used in this project comes from various sources, including:

- CSV files containing sales data.
- Excel sheets with additional sales information.
- Online databases and APIs.

## Data Cleaning and Preparation

In the initial data preparation phase, the following tasks were performed:

- Data loading and inspection
- Handling missing/null values
- Data cleaning and formatting

## Skills Enhanced

Throughout this project, the following skills were enhanced:

- Power Query (Basic and Advanced Operations)
- Basic and complex DAX formulas
- Data modeling involving 10+ tables
- Choosing the right visuals and formatting
- Dashboard designing principles
- Using bookmarks
- Deploying in Power BI service
- Stakeholder Feedback Implementation

## Dashboards Overview

### Basic Measures

This dashboard provides key metrics like Total Sales and Profit over different fiscal years. It allows stakeholders to quickly understand the overall performance.

![Basic Measures](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Basic%20Measures)

### Time Intelligence Part 1

This dashboard provides a month-by-month breakdown of sales, comparing current period sales to previous periods to identify trends and patterns.

![Time Intelligence](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Time%20Intelligence%201)

### Time Intelligence Part 2

This dashboard continues the month-by-month breakdown of sales, adding cumulative sales and comparisons with previous periods.

![Time Intelligence Part 2](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Time%20Intelligence%20Part%202)

### Time Intelligence Part 3

This dashboard further explores time-based sales data, showing rolling 30-day sales and daily sales performance.

![Time Intelligence Part 3](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Time%20Intelligence%20Part%203)

### Ranking

This dashboard ranks sales by different categories, such as products or regions, to identify top and bottom performers.

![Ranking](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Ranking)

### Total Scenario Sales

This dashboard uses scenario analysis to project potential future sales based on different variables and assumptions.

![Total Scenario Sales](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Total%20Scenario%20Sales)

### Top Clients

This dashboard identifies the top clients by sales, providing insights into customer performance and profitability.

![Top 10 Clients](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Top%2010%20Clients)

### DAX or No DAX

This dashboard demonstrates the use of DAX calculations versus no DAX to show different ways of achieving the same results in Power BI.

![DAX or No DAX](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/DAX%20or%20No%20DAX)

### Customer Classification

This dashboard classifies customers based on their purchasing behavior and other metrics to tailor marketing and sales strategies.

![Customer Classification](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Customer%20Classification.png)

### Variables and Weekdays

This dashboard compares sales performance on weekdays versus weekends to identify patterns and optimize operations.

![Variables and Weekdays](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Variables%20and%20Weekdays)

### Final Report

The final report consolidates all key metrics and insights from the different dashboards into one comprehensive overview. It includes total sales by category, customer classification over the years, and total profit trends.

![Final Dashboard](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Final%20Report)

### Navigation

This navigation page includes buttons to easily access different parts of the report, making the user experience more intuitive and efficient.

![Navigation Buttons](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Navigation%20Buttons)

### Best and Worst Customer Sales Thresholds

This dashboard shows the best and worst-performing customers based on sales thresholds. It allows for setting dynamic thresholds to analyze customer performance.

![Best and Worst Customer Sales Threshold](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Best%20and%20Worst%20Customers%20Sales%20Threshold)

## Data Model

![Data Model](https://github.com/PoojaKotturu/Power-BI-Sales-Insights-/blob/main/Data%20Model.png)


## Business Related Terms

- Gross Sales, Net sales, Net profit, Gross Margin
- Pre & Post -invoice deductions, Net Invoice sales
- COGS - cost of goods sold
- Forecast Accuracy, Net Error, ABS Error
- Year to Date, Year to Go
- Consumer vs Customer
- Platform: Brick & Mortar and Ecommerce
- Channel: Retailer, Direct, Distributors

## Major Power BI Skills Learned and Applied

1. Connecting diverse data sources: MYSQL, Excel with Power BI
2. Transforming Data for analysis using Power Query
3. Creating a Custom Date table using M language
4. Creating Conditional and Custom columns
5. Using Merged/Append Queries to combine data from two or more tables/queries
6. Power Query query folding
7. Data Modeling
8. Creating Calculated Columns and Measures
9. Filtering data using Row Context and Filter context
10. Decision Matrix to determine when to use Power Query and DAX
11. Leveraging the CALCULATE function for modifying filter context
12. Visualizations: Slicers, Tables, Matrix, Line chart visuals and many more
13. Conditional Formatting to highlight data based on criteria
14. Bookmarks & Buttons for changing visuals/navigating pages
15. Dynamic slicers for flexible filtering/highlighting
16. Switching measures using a toggle button
17. Tooltips for interactive insights
18. Publishing reports
19. User roles and access control
20. Automatic data refresh with gateway setup

## Dashboard Highlights

- **Basic Measures**: Key metrics overview such as Total Sales and Profit.
- **Time Intelligence Part 1**: Month-by-month sales breakdown and comparison with previous periods.
- **Time Intelligence Part 2**: Cumulative sales and comparisons with previous periods.
- **Time Intelligence Part 3**: Rolling 30-day sales and daily sales performance.
- **Ranking**: Identifying top and bottom performers by various categories.
- **Total Scenario Sales**: Projecting potential future sales based on different scenarios.
- **Top Clients**: Insights into the top-performing clients.
- **DAX or No DAX**: Demonstrating different ways of achieving the same results with or without DAX.
- **Customer Classification**: Classifying customers based on purchasing behavior.
- **Variables and Weekdays**: Analyzing sales performance on weekdays versus weekends.
- **Final Report**: Consolidated overview of key metrics and insights.
- **Navigation**: Intuitive navigation for easy access to different parts of the report.
- **Best and Worst Customer Sales Thresholds**: Analyzing customer performance based on dynamic sales thresholds.

## Conclusion

The Power BI Sales Insights project provides comprehensive tools for sales, marketing, finance, and supply chain analysis. It enables data-driven decision-making and helps in identifying trends, opportunities, and areas for improvement.

## Contact

For any questions or feedback, please contact:

- Pooja Kotturu
- Email: [poojakotturu1999@gmail.com]
- LinkedIn: [Pooja Kotturu](https://www.linkedin.com/in/pooja-kotturu/)
