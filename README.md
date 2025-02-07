## BIKE-project
# My First Project: This project is an exhibition of some of the skills that I have acquired during my self-teaching journey of Data Analytics.
# Objective
The following were my objectives for this project:
1. Practice on the skills acquired about data analysis
2. Conduct data wrangling to clean data and deal with any data inconsistencies for further analysis
3. Perform Analysis on the data so as to compare relationships between variables.
4. Visualize the relationships between variables for easy understanding and interpretation of results.
5. Interpret results and derive insights and conclusions
# Exploratory Data Analysis
Performed analysis to find the relationship between the following variables:
1. Bike Quantity by store location
2. Price vs Bike Model
3. Quantity of bikes vs Age
4. Model Preference vs Age group
5. Payment method preference
   **Findings**
   1.Bike Quantity By Store location:
   The Dataset comprises the data representing a few cities in the USA. These cities are:
> New York  14515     
> Phoenix   14385   
> Philadelphia  14330 
> San Antonio  14300 
> Chicago  14207
> Houston  14149
> Los Angeles  14114
New York sold the highest number of bikes. What could probably contribute to the high number of bikes in NY? To answer that question, New York City is a densely populated city with many live pedestrians, and the population is estimated at 8.1 million. With the high movement of people in the city from one point to another especially those visiting Central Park or Times Square, it is more convenient to move using bikes than cars. Furthermore, the city has made substantial investments in bike infrastructure including bike lanes, bike trails, and the Citi Bike Sharing program that has contributed to the high bike commuting rate.
However, the numbers of bikes across all these cities have very slight differences. Therefore, it is safe to conclude that bikes are more convenient to use in the busy streets of the cities.

  2. Price vs Bike Model
The models of the bikes that the data represent are:
  Bike_Model        Price
Folding Bike  2590.196490
Mountain Bike  2591.29947
Cruiser  2596.130548
Electric Bike  2598.046912
Road Bike  2600.953834
Hybrid Bike  2601.903076
BMX  2608.601366
On average, BMX bikes are more expensive while the Folding Bike is the most affordable. BMX Bikes are designed for durability and strength, customized with special features to offer the best performance. It has a higher demand and is competitive with many high-end options.
On the other hand, Folding Bikes are basic, made with simple features, and designed for convenience and portability thus their affordability.

  3. Bike Sales by Age
I categorized the age into groups for better analysis and classification.
Young Adults: 35 years and below
Mature: 35-55 years
Old: 55 years and above.
  Customer_Age  Quantity
0       Mature    113345
1          Old     84952
2        Young    101414

  4. Model Preference by Age groups
     1. Young Adults vs bike model
        The Old Age group prefer: Bike_Model
BMX              4133
Cruiser          4129
Hybrid Bike      4122
Road Bike        4061
Mountain Bike    4025
Electric Bike    3996
Folding Bike     3993

The Young Age group prefer Bike_Model
Cruiser          4981
Folding Bike     4835
Road Bike        4833
Hybrid Bike      4830
BMX              4830
Electric Bike    4800
Mountain Bike    4783

The Mature Age group prefer Bike_Model
Folding Bike     5501
Road Bike        5469
BMX              5414
Electric Bike    5373
Hybrid Bike      5367
Mountain Bike    5303
Cruiser          5222

  5. Payment Method Preference
     Payment_Method
Apple Pay         16751
Debit Card        16738
Cash              16692
Credit Card       16653
Google Pay        16613
PayPal            16553

# Conclusion
The Analysis provides insights into the sales of bikes. It becomes easier to make decisions that will affect the market and strategies implementation that will be significant to the sales of the bikes by location, price, age, and much more.
The Jupyter notebook includes the processes that I took and visual representations of the results discussed above.

  
