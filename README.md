# Tata Motors EV Analytics Platform

An interactive **Electric Vehicle (EV) Sales and Business Intelligence Platform** built using Microsoft Power BI and a structured dataset of Tata Motors EV sales. This project explores sales performance, revenue trends, customer segments, regional demand, vehicle specifications, market share, inventory, and customer satisfaction to support data-driven business decisions.

## Project Overview

The Tata Motors EV Analytics Platform transforms EV sales and customer data into actionable business insights through data analysis and interactive Power BI dashboards.

The project analyzes 18,000 records containing 44 attributes, including vehicle models, sales, revenue, battery performance, customer demographics, geographical information, market share, inventory, and customer feedback.

## Objectives

- Analyze EV sales and revenue performance over time.
- Identify top-performing vehicle models and categories.
- Compare sales across states, cities, and regions.
- Understand customer demographics and purchasing behavior.
- Evaluate EV market share and adoption trends.
- Monitor inventory availability, production capacity, and delivery timelines.
- Analyze battery specifications and vehicle performance.
- Measure customer ratings and service satisfaction.
- Support strategic decision-making using interactive dashboards.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboards and data visualization |
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures and business KPIs |
| CSV / Excel | Dataset storage and data inspection |
| Data Analytics | Trend analysis and business insights |

## Dataset Information

**Dataset file:** `Tata_Motors_EV_Dataset.csv`

- **Total records:** 18,000
- **Total columns:** 44
- **Format:** CSV
- **Domain:** Electric vehicle sales and business analytics

### Key data categories

| Category | Example attributes |
|---|---|
| Time and Date | Date, Year, Month, Quarter, Financial Year |
| Vehicle Information | Brand, Vehicle Model, Vehicle Category |
| Technical Specifications | Battery Capacity, Range, Charging Type, Motor Power |
| Sales and Revenue | Units Sold, Average Selling Price, Revenue |
| Customer Information | Customer Type, Customer Age Group, Customer Segment |
| Geographic Analysis | State, City, Region |
| EV Adoption | Market Share, Competitor EV Market Share, EV Adoption Rate |
| Operations | Production Capacity, Inventory Available, Delivery Days |
| Customer Experience | Customer Rating, Service Satisfaction Score |
| Pricing and Incentives | Final Customer Price, Government Subsidy Amount, GST Rate |

## Key Business KPIs

The following KPIs can be implemented in Power BI using DAX measures:

- **Total Units Sold:** Total quantity of EVs sold.
- **Total Revenue:** Total sales revenue generated.
- **Average Selling Price:** Average selling price across records.
- **Total Vehicle Models:** Number of distinct vehicle models.
- **Average Customer Rating:** Mean customer rating.
- **Average Delivery Days:** Average time taken to deliver vehicles.
- **Average Service Satisfaction:** Average service satisfaction score.
- **Average Market Share:** Average market share across the selected records.

*Note:* Confirm the appropriate aggregation for each KPI. For example, market share and adoption rates should generally not be summed, and revenue should be summed only after checking the dataset's grain and calculation logic.

## Dashboard Analysis

The Power BI report can be organized into the following analytical areas:

### 1. Executive Overview
- Overall sales and revenue KPIs
- Sales and revenue trends
- Vehicle model performance
- Regional performance overview

### 2. Sales and Revenue Analysis
- Monthly, quarterly, and yearly sales trends
- Revenue by vehicle model and category
- Sales channel comparison
- Customer type and purchase mode analysis

### 3. Regional and Market Analysis
- Sales by state, city, and region
- Market share comparison
- EV adoption trends
- Competitor market share analysis

### 4. Customer Insights
- Customer age group and segment analysis
- Individual versus fleet purchasing behavior
- Customer ratings
- Service satisfaction analysis

### 5. Operations and Vehicle Analysis
- Inventory availability and production capacity
- Delivery time analysis
- Battery capacity and driving range
- Charging type and charging time comparisons

*These are suggested analytical sections; the actual pages and visuals depend on the contents of the included Power BI report.*

## Repository Structure

```text
Tata-Motors-EV-Analytics-Platform/
│
├── Tata_Motors_EV_Dataset.csv
├── Tata-Motors-EV-Analytics-Platform.pbix
└── README.md
```

## Getting Started

### Prerequisites

- Microsoft Power BI Desktop
- A spreadsheet application or text editor for inspecting CSV data

### Steps to Run the Project

1. Clone or download this repository.
2. Open `Tata-Motors-EV-Analytics-Platform.pbix` using Power BI Desktop.
3. If Power BI asks for the dataset location, select `Tata_Motors_EV_Dataset.csv`.
4. Refresh the data and verify that all queries load successfully.
5. Explore the report using its available visuals, filters, slicers, and drill-down options.

## Business Value

This project demonstrates how business intelligence can help an EV business:

- Identify sales trends and high-performing vehicle models.
- Understand regional demand and customer preferences.
- Monitor revenue and sales-channel performance.
- Evaluate inventory and delivery efficiency.
- Track customer experience and service quality.
- Make more informed decisions about sales, operations, and market expansion.

## Future Enhancements

- Integrate regularly updated sales data.
- Build EV sales forecasting models using Python.
- Add profitability and cost analysis.
- Develop advanced customer segmentation.
- Create a web-based dashboard for broader accessibility.
- Automate data refresh and reporting workflows.

## Skills Demonstrated

`Power BI` · `DAX` · `Power Query` · `Data Cleaning` · `Data Modeling` · `Data Visualization` · `Business Intelligence` · `KPI Analysis` · `Exploratory Data Analysis`

## Author

**Parth Varute**

GitHub: [@parthvarute09](https://github.com/parthvarute09)

Project Repository: [Tata Motors EV Analytics Platform](https://github.com/parthvarute09/Tata-Motors-EV-Analytics-Platform)

---

*Disclaimer: This is an independent analytics project for educational and portfolio purposes. The dataset should not be interpreted as verified official Tata Motors sales data unless independently validated.*
