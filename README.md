# Beverage Sales Dataset

## Overview
This repository contains a synthesized dataset derived from *Heritage Spirits* retail operations. The data provides insights into inventory management, purchases, and sales activities, structured into multiple sheets for ease of analysis and exploration.

---

## File Details

### File Name
`Data - pROJECT.xlsx`

### Number of Sheets
5

---

## Sheet Metadata

### 1. **BegInvFINAL12312016**
   - **Description**: This sheet represents the beginning inventory as of December 31, 2016.
   - **Key Columns**:
     - `InventoryId`: Unique identifier for inventory items.
     - `Store`: Store ID where the inventory is located.
     - `City`: City name of the store.
     - `Brand`: Brand identification number.
     - `Description`: Product description.
     - `Size`: Product size (e.g., 750mL, Liter).
     - `onHand`: Number of units available in stock.
     - `Price`: Price per unit of the product.
     - `startDate`: Date when the inventory tracking started.

---

### 2. **EndInvFINAL12312016**
   - **Description**: This sheet tracks the ending inventory as of December 31, 2016.
   - **Key Columns**:
     - Similar to the `BegInvFINAL12312016` sheet, but also includes:
     - `endDate`: Date marking the end of inventory tracking for the year.

---

### 3. **2017PurchasePricesDec**
   - **Description**: This sheet captures the purchase prices and vendor details for products purchased in December 2017.
   - **Key Columns**:
     - `Brand`: Brand identification number.
     - `Description`: Product description.
     - `Price`: Retail price of the product.
     - `Size`: Product size (e.g., 750mL, Liter).
     - `Volume`: Volume of the product.
     - `Classification`: Product classification (e.g., category or type).
     - `PurchasePrice`: Cost price of the product for the store.
     - `VendorNumber`: Unique ID of the vendor.
     - `VendorName`: Vendor's name.

---

### 4. **InvoicePurchases12312016**
   - **Description**: This sheet records invoice details for purchases made up to December 31, 2016.
   - **Key Columns**:
     - `VendorNumber`: Vendor's unique identification number.
     - `VendorName`: Vendor's name.
     - `InvoiceDate`: Date when the invoice was issued.
     - `PONumber`: Purchase order number.
     - `Quantity`: Quantity of items purchased.
     - `Dollars`: Total dollar amount for the purchase.
     - `Freight`: Freight charges for the shipment.
     - `Approval`: Approval status for the invoice.

---

### 5. **SalesFINAL12312016**
   - **Description**: This sheet provides sales details for products sold up to December 31, 2016.
   - **Key Columns**:
     - `InventoryId`: Unique identifier for the inventory item.
     - `Store`: Store ID.
     - `Brand`: Brand identification number.
     - `Description`: Product description.
     - `Size`: Product size (e.g., 750mL, Liter).
     - `SalesQuantity`: Number of units sold.
     - `SalesDollars`: Total revenue generated from sales.
     - `SalesPrice`: Selling price per unit.
     - `SalesDate`: Date of the sale.
     - `Volume`: Volume sold.
     - `ExciseTax`: Applicable excise tax.
     - `VendorNo`: Vendor number.
     - `VendorName`: Vendor name.

---

## Usage Instructions
1. **Data Analysis**: Use this dataset for inventory management, sales analysis, and vendor performance evaluation.
2. **Integration**: The structured format allows easy integration into data analysis pipelines using Python, R, or other tools.
3. **Visualization**: Generate insights by creating visualizations for trends in inventory, sales, and vendor activities.

---

## Contributors
- Maintained by **D-devhub** and contributors.

---

## Contact
For questions or suggestions, please contact:
- **Email**: [work.vram@gmail.com]
- **GitHub Profile**: [D-devhub](https://github.com/D-devhub)

---
