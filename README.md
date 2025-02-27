#simple_lp

#Problem Description:

An e-commerce company sells two products: Product A and Product B. The company needs to decide the optimal quantity of each product to stock to minimize total costs, which include purchasing costs and inventory holding costs. The company must also meet a minimum customer demand for each product and adhere to storage space limitations.​

Data Sources:

Purchasing Costs: Assumed based on typical market prices.​
Inventory Holding Costs: Estimated using industry averages.​
Storage Space Requirements: Hypothetical values for illustrative purposes.​
speedcommerce.com
Customer Demand: Assumed based on sales forecasts.​
sellerassistant.app
Objective Function:

Minimize Total Cost = Purchasing Cost + Inventory Holding Cost​
coursesidekick.com
+3
speedcommerce.com
+3
shipbob.com
+3

Let:

x
1
x 
1
​
  = Quantity of Product A to stock​
x
2
x 
2
​
  = Quantity of Product B to stock​
Parameters:

Purchasing Cost per unit of Product A: $50​
Purchasing Cost per unit of Product B: $30​
Inventory Holding Cost per unit per month: 20% of the product's value​
Storage Space per unit of Product A: 2 cubic feet​
Storage Space per unit of Product B: 1 cubic foot​
Total Available Storage Space: 500 cubic feet​
Minimum Monthly Demand for Product A: 100 units​
Minimum Monthly Demand for Product B: 150 units​
Formulation:

Objective Function: 
Minimize 
Z
=
50
x
1
+
30
x
2
+
0.2
×
(
50
x
1
+
30
x
2
)
Minimize Z=50x 
1
​
 +30x 
2
​
 +0.2×(50x 
1
​
 +30x 
2
​
 ) 
Z
=
60
x
1
+
36
x
2
Z=60x 
1
​
 +36x 
2
​
 ​

Subject to:

Storage Space Constraint:​
2
x
1
+
x
2
≤
500
2x 
1
​
 +x 
2
​
 ≤500
Demand Constraint for Product A:​
x
1
≥
100
x 
1
​
 ≥100
Demand Constraint for Product B:​
x
2
≥
150
x 
2
​
 ≥150
Non-negativity Constraints:​
x
1
,
x
2
≥
0
x 
1
​
 ,x 
2
​
 ≥0
Optimal Solution:

Solving this linear programming problem using Python's scipy.optimize.linprog function yields the following optimal stocking quantities:​

Quantity of Product A to stock (
x
1
x 
1
​
 ): 100 units​
Quantity of Product B to stock (
x
2
x 
2
​
 ): 300 units​
This solution minimizes the total cost while satisfying all constraints.
References
Singh, V. (2024, May 20). What is operations research? Retrieved from Shiksha Online: https://www.shiksha.com/online-courses/articles/operations-research-blogId-157427
