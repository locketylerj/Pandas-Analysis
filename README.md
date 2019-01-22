

## Heroes of Pymoli

![Fantasy](Images/Fantasy.jpg)

Using mock data of a fantasy game Heroes of Pymoli, this python script generates a report of the following:

### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Normalized Totals

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Normalized Totals

### Top Spenders

* Identifies the the top 5 spenders in the game by total purchase value, then lists (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identifies the 5 most popular items by purchase count, then lists (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identifies the 5 most profitable items by total purchase value, then lists (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value


## Additional Notes

* These are challenging activities for a number of reasons. For one, these activities will require analyzing thousands of records. Hacking through the data to look for obvious trends in Excel is just not a feasible option. The data size is large, but pandas can efficiently parse through it.

## Copyright

Data Boot Camp © 2018. All Rights Reserved.
