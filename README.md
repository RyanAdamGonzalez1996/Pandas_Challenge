# Pandas_Challenge
Homework for the fourth week of class. 

Choosing the Heroes of Pymoli challange:
Will need to read data froma  csv file and set up a code on jupyter notebook to intepret the data into meaningful table to determine insights based on the data obtained.

Instructions: 

Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

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
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must submit a link to your Jupyter Notebook with the viewable Data Frames.
* You must include a written description of three observable trends based on the data.
* See [Example Solution](HeroesOfPymoli/HeroesOfPymoli_starter.ipynb) for a reference on expected format.


Trends found in Data:

Observable Trends in Heroes of Pymoli
1.	The target audience that provides the best business is the Age Group of 20-24 year olds.
This Demographic is not only the most active player base, they are also spending the most money on items. Despite not having the highest average purchase price per item, this demographic boasts the highest quantity of sales. Indicating that this age group is more willing to spend money on smaller items, but at a much higher frequency than any other age group.

2.	An item’s price that not directly correlate with how well it sells.	
Based off the top 5 best selling items and the most profitable, the actual price of the item doesn’t seem to matter as much. Both dataframes both show a much higher reliance on quantity of sales, rather than the amount the item goes for. This could indicate that the popular items can be based on in game value more than monetary, whether it be for fashion or function.

3.	Players don’t seem that likely to want to spend a lot of money on this game.
Although the data shows that players are willing to spend money on the game, no player ever goes above $20. With this information, we can infer that the best practice to continue to make money is to focus on smaller, cheaper items that the players are happy to buy in mass quantities, rather than any individual item priced for more than $20.
