Total Sales =
SUM(SalesData[Sales])

Total Profit =
SUM(SalesData[Profit])

Total Quantity =
SUM(SalesData[Quantity])

Total Orders =
DISTINCTCOUNT(SalesData[Order_ID])

Average Order Value =
DIVIDE([Total Sales], [Total Orders])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales])
