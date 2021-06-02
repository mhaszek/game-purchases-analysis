# Game purchases analysis with Pandas
Pandas project for Monash Data Analytics Boot Camp

The purpose of this project was to analyse the purchasing data for the fictitious fantasy game Heroes of Pymoli.

# Data

There is one key source of data used:

* [purchase_data.csv](HeroesOfPymoli/Resources//purchase_data.csv) - .csv dataset composed of seven columns: `Purchase ID`, `SN`, `Age`, `Gender`, `Item ID`,	`Item Name` and `Price`

# Analysis

### Player Count

* Total Number of Players

![players_count](Images/players_count.JPG)

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

![purchasing_analysis](Images/purchasing_analysis.JPG)

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

![gender](Images/gender.JPG)

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

![gender_pa](Images/gender_pa.JPG)

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

![age](Images/age.JPG)

![age_pa](Images/age_pa.JPG)

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

![top_spenders](Images/top_spenders.JPG)

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

![popular_items](Images/popular_items.JPG)

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

![profitable_items](Images/profitable_items.JPG)

## Three Observable Trends
* Majority of the players are male - 84.03% of players and they generate 82.68% of the total revenue.
* Majority of the players are young - 76.74% of playes are aged between 15 and 29.
* Users aged between 20 and 24 make the most purchases and generate 46.81% of the total revenue.

# Demo

To run the example locally run `main.ipynb` file in Jupyter Notebook.


# Used Tools
 * Jupyter Notebook 
 * Pandas


#

#### Contact: mil.haszek@gmail.com
