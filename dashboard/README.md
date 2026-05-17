# Dashboard

This folder contains the Power BI dashboard file for the Shopify Customer and Sales Analysis Dashboard project.

## File

- `shopify_sales_dashboard.pbix` - Power BI dashboard file.

## Dashboard Pages

The dashboard contains two main pages:

- Shopify Analysis
- Details Tab

## Shopify Analysis Page

This page includes:

- Net Sales
- Total Quantity
- Net Average Order Value
- Total Customers
- Single Order Customers
- Repeat Customers
- Lifetime Value
- Repeat Rate
- Purchase Frequency
- Net Sales Trend Over Time
- Regional Overview by Province and City
- Net Sales by Gateway Payment Method
- Net Sales by Product Type

## Details Tab Page

This page includes transaction-level records such as:

- Order Number
- Customer Name
- Customer ID
- Province
- City
- Zip Code
- Product Type
- Gateway
- Net Sales
- Total Tax
- Total Price USD

## How to Open

Open the `.pbix` file using Microsoft Power BI Desktop.

If Power BI asks for the data source path, update the source path to:

```text
../data/shopify_sales.xlsx
