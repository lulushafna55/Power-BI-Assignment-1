# Power-BI-Assignment-1
Data transformation and Data modeling
Imported "list of orders" , "order details", and "sales target" to power BI and opened in "power query" from "transform data"
Restricted the "List of Orders" table to only the first 500 rows from "keep columns","keep first rows",
“Order Date” column in the “List of Orders” table is set to data type 'Date'from "Data type"
Changed the data type of “Amount” and “Target” columns to ‘Fixed Decimal Number’from "Data type"
Formated the "CustomerName" column into proper case, using capitalization for each word from "format"
Merged the "State" and "City" and created a new column named "Location" in the format ‘City, State’ from "merge columns" using "," as delimitter
Created a new custom column named "Profit Margin" by "Profit" divided by "Amount". and changed column format from decimal to "percentage"
Added a new "conditional column" named "Profit Status" from "add column" by the conditions as follows: if the profit is less than 0, the label should be "Loss"; if the profit equals 0, the label should be "Break-Even"; and if the profit is greater than 0, the label should be "Profit".
Merged the "List of Orders" and "Order Details" tables into a new single table named "Orders Data" based on the "Order ID" relationship from "merged queries" "merge queries as new"
Removed duplicates from "remove rows"
sorted the "order date" in "descending order" and filtered state column to only "tamil nadu"
Duplicate the “Order Details” table / "home"/"group by" (group by columns "order id" , "category","sub category") (new columns "order count" ,"avg profit", "total amount") ( operations "count rows" "average","sum") ( column "profit","amount")
dupilcate "sales target" select "order date" column "add column"/"date"/"month"/"name of month"| 
"home"/"group by" "month name" , new column "total target amount" ,operation "sum" ,column "target amount"
established relationship from "list of orders " and " order details" from 1...* and "order details" and " sales target" as *..*
