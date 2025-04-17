# Supply Chain Analysis

## Overview
This project analyzes the DataCo Supply Chain Dataset to gain insights into supply chain performance, including shipping times, delivery status, and other key metrics. The dataset is processed and visualized using Python with libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset
The dataset used is `DataCoSupplyChainDataset.csv`, containing 180,519 records and 53 columns. It includes information about orders, customers, products, and shipping details.

### Key Columns
- **Type**: Payment type (e.g., DEBIT, TRANSFER, CASH, PAYMENT)
- **Days for shipping (real)**: Actual days taken for shipping
- **Days for shipment (scheduled)**: Scheduled days for shipping
- **Benefit per order**: Profit per order
- **Sales per customer**: Sales amount per customer
- **Delivery Status**: Status of delivery (e.g., Advance shipping, Late delivery, Shipping on time)
- **Late_delivery_risk**: Binary indicator (0 or 1) for late delivery risk
- **Category Name**: Product category (e.g., Sporting Goods)
- **Customer City**: City of the customer
- **Order Country**: Country of the order
- **Product Name**: Name of the product
- **Shipping Mode**: Mode of shipping (e.g., Standard Class)

### Dataset Statistics
- **Rows**: 180,519
- **Columns**: 53
- **Total Data Points**: 9,567,507
- **Numerical Features**: 29
- **Categorical Features**: 24
- **Missing Values**:
  - `Customer Lname`: 8 missing
  - `Customer Zipcode`: 3 missing
  - `Order Zipcode`: 155,679 missing
  - `Product Description`: All 180,519 missing

## Installation
To run the analysis, ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn
