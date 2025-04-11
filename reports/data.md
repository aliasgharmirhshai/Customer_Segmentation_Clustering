
# Overview

- **Number of Columns in the Data:**  8
- **Number of Rows in the Data:**  541909

## Columns 

- **InvoiceNo** (object): Unique identifier for each invoice.
- **StockCode** (object): Code for the item purchased.
- **Description** (object): Description of the purchased item (some missing values).
- **Quantity** (int64): Number of items purchased.
- **InvoiceDate** (datetime64): Date and time when the invoice was issued.
- **UnitPrice** (float64): Price of a single unit of the item.
- **CustomerID** (float64): Unique identifier for the customer (missing values for some entries).
- **Country** (Object): Country where the transaction took place.


## Missing Value 

| Column       | Missing Values |
|--------------|----------------|
| **InvoiceNo** | 0              |
| **StockCode** | 0              |
| **Description** | 1454         |
| **Quantity**  | 0              |
| **InvoiceDate** | 0            |
| **UnitPrice** | 0              |
| **CustomerID** | 135080        |
| **Country**   | 0              |


## Duplicated Value

- **Duplicate data sets:** 5268

