# Bike Store Sales & Customer Performance Dashboard

An interactive **Power BI dashboard** built to explore retail bike-store performance across sales, orders, customers, products, inventory, categories, brands, and staff.

The report brings key business metrics and detailed breakdowns into one place so users can monitor performance, identify sales patterns, understand customer behaviour, and review stock levels.

## Project overview

This Power BI project contains a multi-section report with navigation for:

- **Sales** – overall sales performance and sales trends.
- **Orders** – order volume, order status, and order-level performance.
- **Customers** – customer activity and customer segmentation.
- **Products** – product-level sales performance.
- **Stocks** – inventory quantities and stock-level indicators.
- **Categories & Brands** – performance comparisons across product categories and brands.
- **Staffs** – staff-related sales performance.

The report includes KPI cards and interactive visual elements. The model references business entities such as orders, order items, customers/customer segments, products, categories, brands, stores, stocks, and staff.

## Key metrics and analysis areas

The report includes measures/fields for:

- Total Sales
- Total Orders
- Total Customers
- Active Customers
- Average Order Value
- Average Sales
- Sales by order date and month
- Sales by order status
- Sales by product and category
- Sales by brand
- Sales by store location (state and city)
- Stock quantity and low/normal stock indicators
- Customer Recency, Frequency, and Monetary (RFM-style) attributes
- Staff-related order/sales analysis

> **Note:** Metric values are intentionally not listed here because they depend on the data loaded in the Power BI report and may change when filters are applied.

## Tools and skills demonstrated

- Microsoft Power BI
- Data modelling and relationships
- DAX measures and aggregations
- KPI design and interactive report navigation
- Data analysis and visualisation
- Sales, customer, product, and inventory analysis

## Repository contents

```text
bike-store-sales-dashboard/
│
├── capstone.pbix
├── README.md
└── screenshots/
    └── (add dashboard screenshots here)
```

`capstone.pbix` is the Power BI report file. Add screenshots of the report pages to the `screenshots/` folder if you want visitors to preview the dashboard directly on GitHub.

## How to open the dashboard

1. Download or clone this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open `capstone.pbix` in Power BI Desktop.
4. Wait for the report and its data model to load.
5. Use the report navigation and filters to explore the different analysis sections.

## Suggested dashboard walkthrough

1. Start with **Sales** to review the headline performance indicators.
2. Explore **Orders** to understand order volume and order status.
3. Open **Customers** to review customer activity and RFM-style metrics.
4. Use **Products** and **Categories & Brands** to compare product performance.
5. Review **Stocks** to identify inventory levels that may need attention.
6. Explore **Staffs** to inspect staff-related performance.

## Business value

This dashboard can help a retail business:

- Monitor sales and order performance in one report.
- Identify products, categories, and brands contributing to sales.
- Understand customer activity and purchasing patterns.
- Review inventory quantities and spot low-stock items.
- Compare performance across store locations and staff.

## Data and privacy

The `.pbix` file may contain an imported dataset or connection details. Review the report and remove confidential, personal, or commercially sensitive information before making the repository public. If the source dataset is not included in this repository, users may need access to the original data source to refresh the report.

## Future improvements

- Add a dedicated date/calendar table and clearly documented time-intelligence measures.
- Include sales growth, month-over-month, and year-over-year comparisons.
- Add drill-through pages for product, customer, and store-level investigation.
- Document important DAX measures and data relationships.
- Add dashboard screenshots and a short demo video.

---

**Project type:** Data Analytics / Business Intelligence  
**File format:** Power BI (`.pbix`)  
**Author:** Venkatraman S
