# DAX Measures

## Total Sales

```DAX
Total Sales = SUM(SalesData[Sales])
```

## Total Profit

```DAX
Total Profit = SUM(SalesData[Profit])
```

## Total Orders

```DAX
Total Orders = DISTINCTCOUNT(SalesData[Order_ID])
```

## Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Sales],[Total Orders])
```

## Profit Margin %

```DAX
Profit Margin =
DIVIDE([Total Profit],[Total Sales])
```
