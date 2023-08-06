Pricing Model for a Smartwatch Company

Experience working as a Business Analyst in a Analytics Industry

Problem Statement

Help NuWave, a startup dealing in a wide range of electronic gadgets and accessories, enter the 
smartwatch market by launching their own flagship smartwatch. 
They plan to launch the watch with an OLED display which they'll acquire from Samsung.
Build a spreadsheet model to calculate a suitable selling price for their smartwatch, so they make a 
profit margin of at least 2% and sell not less than 1800 smartwatches a day, to gain 5% market 
share.

Situation

NuWave wants to launch a new smartwatch, which will be one of their flagship products. They 
plan to launch the watch with an OLED display.
They intend to first enter the market and gain at least 5% of the market share.
As a new player in the smartwatch market, they want to price the watch lower than their 
competition (selling at ₹ 7,799).
The demand in such a market is elastic, meaning a small price change can cause a significant 
change in demand.
To achieve 5% of the market share, NuWave needs to sell at least 1,800 units per day. Assume 
NuWave can completely fulfill the demand for the day.

Complication

For NuWave to sell 1,800 smartwatches daily, they need to have a certain inventory level.
Each smartwatch requires one OLED panel. For smooth production, they need to have stock as 
well.
NuWave approached Samsung to acquire the panels. Samsung quoted the price at ₹ 1,475 for
one unit. The price will decrease as the order quantity increases.
NuWave can store only 2000 OLED panels in its own facility. They need a warehouse to store more
warehouse, which will cost them ₹ 12,000/day. They can store 10,000 OLED panel units in one
warehouse.
The warehouse should be utilized effectively.


Now, as a business analyst at NuWave, your job is to find out:

1. At what price should they sell one unit to gain a 5% market share and earn at least 
a 2% profit margin?
2. Minimum order quantity of panels at that price point so NuWave doesn't make a loss.
Dataset for Experience
Great! Before you begin, here is the data required for the experience. Please click on the button 
below and download it from the Google Sheets tab that opens.
It's an Excel workbook file with four sheets.
Dataset=
https://docs.google.com/spreadsheets/d/1dK0tOJhvqK24_njxj9rImN7P5mRZ3-
PB/edit?amp;ouid=105322884775240278558&amp;rtpof=true&amp;sd=true#gid=1844
655244

Worksheets Description

1. First_Submission: Has a mini-case that you'll be solving next. 🏆
2. Cost-Supply: Contains price quote from Samsung for acquiring OLED panels. Here, 
you'll model the relationship between order quantity and cost per panel unit.
3. Price-Demand: Contains selling prices and their corresponding demand per day, which 
NuWave found out while testing the watch in the Market. You'll be modeling the 
relationship between selling price and demand per day here.
4. Model: This is the sheet where you'll finally create your model.
How NuWave Can Control Cost


To calculate the selling price of one smartwatch, we need to know its cost. Also, NuWave should 
be able to generate a profit margin of at least 2%. We know,
Profit = Selling Price - Cost
In the above equation, we can control the cost to some degree.
Why some, you might ask? It depends on the suppliers' rates (Samsung is one of them).
How can NuWave control costs? By changing the order quantity.
In Samsung's quote (given below), the price changes depending on the order quantity.
Order Quantity Panel Cost/Unit

1                   ₹ 1,475

5000                ₹ 1,425

20000               ₹ 1,250

50000               ₹ 450 (lower limit)

Now NuWave can store only 12,000 units (2,000 in their facility and 10,000 in the warehouse).
What would the unit cost be if they ordered 10,000 units? From the above quote, it will 
be between ₹ 1,250 and ₹ 1,425.
But we need to know the exact cost. To do that, we need to model the relationship between order 
quantity and price.

Modeling Relationship Between Order Quantity (Supply) and Price

Now, looking at Samsung's quote, the relationship would appear to you as non-linear (which it 
might be!).
To keep things simple, assume the relationship to be piecewise linear (multiple straight lines).
For this milestone, your job is to create an equation that outputs the cost per unit for a given
order quantity, as per Samsung's quote.
You can create three equations for each line. Depending on the order quantity, you can switch 
which sequence should be used to calculate the per-unit cost. The image below shows the slope & 
intercept of the first line.
Check out the Cost-Supply sheet.

Expected Output

Could you complete your Model sheet as shown below? The Panel Cost/Unit will come from the CostSupply sheet.
Calculating Total Cost
In the previous milestone, we calculated the cost of one smartwatch for different order quantities.
In this milestone, we'll calculate the total cost for different order quantities, including the warehouse storage
quantities.

Storage Cost

NuWave can store 2,000 units in its facility free of charge. To keep more teams, they will 
require a warehouse.
The cost of keeping inventory in the warehouse is ₹ 12,000/day. The total number of units that can 
be stored in the warehouse is 10,000.
So, if NuWave orders 5,000 units of OLED panels, they have to store 3,000 in the warehouse. If 
they sell 1,800 units/day; they must keep these 3,000 units for two days!
Cost of storage for 2 days = 2 * ₹ 12,000 = ₹ 24,000

Total Cost

Say the unit cost for ordering 5,000 panels is ₹ 1,000, and other components cost ₹ 6,000,
total cost for 5,000 smartwatches = (₹ 1,000 + ₹ 6,000) * 5,000 = ₹ 3,50,00,000
total cost = ₹ 3,50,00,000 + ₹ 24,000 = ₹ 3,50,24,000
You have to implement the same logic in the Model sheet. Depending on the quantity ordered, 
calculate the total cost.

Expected Output

Calculate the total cost in the Model sheet.

Calculating Selling Price

Well, it was done up to now! We have calculated the total cost.
Let's now find the selling price of one smartwatch.
Modeling Relationship Between Selling Price and Demand per Day
During the testing phase, NuWave found that the demand is relatively elastic.
1. If they sell one smartwatch for 5,000, they can sell 10,500 units daily.
2. When they increased the price to ₹ 8,000, they could only sell 175 units a day.
First, you need to model the relationship between demand per day and selling price 
in the Price-Demand sheet. Assume a linear relationship.
Model the equation such that you can input the selling price and get demand per day as an output.

Calculating Selling Price

Assume any selling price and calculate total revenue based on it. After calculating the income, 
you can calculate the profit margin.
Now, you need to tune the selling price such that the following conditions are fulfilled:
1. NuWave must sell at least 1,800 units daily to gain a 5% market share.
2. They need to generate at least a 2% profit margin.
3. They also need to keep the price lower than their competition (₹ 7,799).
4. Warehouse utilization should be 100%.
5. The selling price has to be a multiple of 25.

Expected Output

Calculate the model in the Model sheet

Deliverables

Deliverable D1: The file where you created the model will serve as the deliverable for this 
MicroExperience.
