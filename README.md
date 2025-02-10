# Online_Retail_Customer-Segementation_Project

E-commerce businesses often face the challenge of tailoring their marketing strategies to a diverse customer base. To address this, customer segmentation using the Recency, Frequency, and Monetary (RFM) framework is a proven and efficient method.

This notebook demonstrates a step-by-step process for implementing RFM analysis using the Online Retail II dataset, which contains transactional data from December 2009 to December 2010. By analyzing customer behavior based on their last purchase date (Recency), the number of purchases (Frequency), and the total amount spent (Monetary), we classify customers into distinct segments.

These segments allow businesses to:

Identify their most loyal customers. Reactivate inactive or at-risk customers. Allocate marketing budgets effectively by targeting high-value groups.

This analysis provides actionable insights into customer behavior, enabling e-commerce businesses to develop tailored strategies for retention, reactivation, and growth. At the end of this project, you can explore detailed action plans designed for each customer segment to guide strategic decision-making effectively.

The Data set contains 541909 observations of transaction From Different walmart shops. Corresponding to each we have to identiy the loyal customers.

Libraries used
Pandas, plotly, datetime, matplotlib, seaborn sklearn and math.


|       Field Name      |    Data Type     | Description     |
| :------------:|:-------------:|:-----:|
|    InvoiceNo  |   Nominal   |  Invoice number, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.   |
|   StockCode    |   Nominal  |   Product code, a 5-digit integral number uniquely assigned to each distinct product.  |
|     Description    | Nominal |    Product (item) name.  |
|    Quantity    |  Numeric	 | The quantities of each product (item) per transaction.    |
|   InvoiceDate     |  Numeric	 |   Invoice Date and time, the day and time when each transaction was generated.  |
|     UnitPrice    | Numeric  |   Product price per unit in sterling.  |
|    CustomerID  |  Nominal |  Customer number, a 5-digit integral number uniquely assigned to each customer.  |
|    Country   | Nominal  |  Country name, the name of the country where each customer resides.  |



