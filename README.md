# CadetX – Heavy Supplier, Inventory & Warehouse Analytics

## Project Overview

This is a 12-week Data Analytics Virtual Work Experience project under the CadetX programme.

The project focuses on analysing supplier performance, inventory management, warehouse operations, customer behaviour and order transactions to identify business insights and support better supply chain decisions.

## Project Objectives

- Analyse supplier and procurement performance.
- Understand inventory levels and stock movements.
- Evaluate warehouse and branch performance.
- Analyse customer purchasing behaviour.
- Identify data-quality issues and inconsistencies.
- Develop meaningful business KPIs and recommendations.
- Support data-driven supply chain optimisation.

## Dataset Information

The project contains 12 CSV datasets with approximately **605,141 records and 134 columns**.

| Dataset | Description |
|---|---|
| branches.csv | Branch and warehouse information |
| customers.csv | Customer information |
| inventory_master.csv | Inventory and stock details |
| invoices.csv | Invoice transactions |
| payments.csv | Payment records |
| products.csv | Product information |
| purchase_orders_header.csv | Purchase order details |
| purchase_orders_lines.csv | Purchase order line items |
| sales_orders_header.csv | Sales order details |
| sales_orders_lines.csv | Sales order line items |
| stock_ledger.csv | Stock movement records |
| suppliers.csv | Supplier information |

## Tools & Technologies

- **Python** – Data analysis and validation
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Jupyter Notebook** – Analysis and documentation
- **GitHub** – Project version control and portfolio management

## Project Progress

### Week 1 – Foundation & Exploration

Work completed and documented:

- Loaded and explored all 12 datasets.
- Analysed dataset structures and data types.
- Checked missing values and complete duplicate records.
- Investigated duplicate identifiers.
- Validated foreign key relationships.
- Converted date columns and warehouse capacity values.
- Validated sales and purchase order calculations.
- Performed customer data analysis.
- Performed supplier data validation.
- Performed branch data analysis.
- Started warehouse and inventory master analysis.

## Key Findings – Week 1

### Data Quality
- No complete duplicate rows were identified across the 12 datasets.
- 2,370 missing received dates were associated with cancelled purchase orders.
- Nine foreign key relationships were checked, with zero unmatched records.

### Customer Analysis
- Analysed 500 customer records.
- Government customers recorded the highest total purchase value.
- Identified customer credit utilisation patterns.

### Supplier Analysis
- Analysed 8 supplier records.
- Supplier reliability scores were within the expected range of 1–5.

### Branch Analysis
- Analysed 6 branches.
- Delhi recorded the highest average monthly revenue.
- Chennai recorded the highest estimated operating profit margin.

### Inventory Analysis
- Analysed 180 inventory records.
- Identified 30 unique products and 6 branches.
- Identified 95 unique warehouse bins.
- All 180 inventory records were above their recorded maximum stock limits, requiring further investigation.

## Repository Contents

The repository includes:

- Week 1 Jupyter Notebook
- Project overview and documentation
- Data quality findings
- Customer analysis report
- Supplier validation report
- Branch analysis report
- Invoice and payment validation
- Sales and purchase order calculation validation
- Warehouse and inventory analysis report
- Week 1 progress report

## Project Timeline

| Phase | Weeks | Focus |
|---|---|---|
| Foundation & Exploration | 1–3 | Data profiling, cleaning and integration |
| Product, Inventory & Warehouse Analytics | 4–6 | Stock and warehouse performance |
| Supplier, Customer & Predictive Analytics | 7–9 | Supplier and customer insights |
| BI, Strategy & Final Delivery | 10–12 | Dashboards and business recommendations |

## Expected Project Outcome

The overall objective is to transform raw operational datasets into meaningful business insights that can help improve:

- Inventory control
- Warehouse efficiency
- Supplier performance
- Customer understanding
- Procurement decisions
- Supply chain operations

## Author

**Pranav Nikate**

GitHub: [Pranav-Nikate](https://github.com/Pranav-Nikate)

---

*Project developed as part of the CadetX Virtual Work Experience Programme.*
