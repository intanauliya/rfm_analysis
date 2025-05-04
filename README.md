# RFM Analysis
Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests and spending habits.

Here are some of the main benefits of customer segmentation:
1. Targeted marketing messages to the right people
2. Focuses on the most profitable customers
3. It can improve customer service
   
In this project, I will go through step by step how to conduct RFM Analysis in order to segment our customers.

# Context
In the dynamic landscape of e-commerce, understanding customer behavior is crucial for maximizing sales and revenue. This project aims to analyze the sales and revenue data of an e-commerce platform and perform customer segmentation based on RFM (Recency, Frequency, Monetary) analysis. The goal is to extract valuable insights that can inform strategic decisions and enhance the overall performance of the platform. Therefore, try to build a supervised learning model to solve this problem.

# Content
This is a sales transaction data set of UK-based e-commerce (online retail). The data set contains 500K rows and 8 columns. The following is the description of each column.

1. InvoiceNo (categorical): a six-digit unique number that defines each transaction. The letter “C” in the code indicates a cancellation.
2. StockCode (categorical): a five unique character used to identify a specific product.
3. Description (categorical): product/item name.
4. Quantity (numeric): the quantity of each product per transaction. Negative values related to cancelled transactions.
5. InvoiceDate (date): the date when each transaction was generated.
6. UnitPrice (numeric): the price of each product per unit in pound sterling (£).
7. CustomerID (categorical): a five-digit unique number that defines each customer.
8. Country (categorical): name of the country where the customer resides.


