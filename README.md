# Problem:
Storage costs can quickly accumulate for many businesses, and many companies wind up putting on a big sale simply because they over-ordered certain items to make storage more manageable. It’s important to keep track of exactly how many of each item you have in stock, along with how much you have on order.

# Introduction:
The inventory management system here, tracks inventory from purchase to the sale of goods.
It manages the goods for the small scale shops using the power of python and json. Furthermore, it saves a lot of time and efforts of the shopkeepers and facilitates them in the tedious task of managing inventory and sales.

# Working:
This project is mainly divided into two files:

1. Product insertion in Inventory: In this part, We create a records.json file which contains all the Inventories with details like product id (barcode), name, quantity, price, isAvailable, Expiry date. Here we can add new goods in the inventory and the records will be stored in records.json file.

2. Inventory_Purchase: In this part, 
a) We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer. 
b) If the purchased items are available in inventory, then Bill is generated. 
c) The detailes of the transactions are then stored in sales.json file with attributes like total transactions,transactio id,date,time, product name,total amount of purchase, customer name and customer mobile number.

# Tools required:
1) python - 3.7
2) json

