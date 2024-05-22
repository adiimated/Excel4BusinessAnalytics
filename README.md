# Excel For Business Analytics

## Quality Sweater Company Financial Model
This project involves developing a dynamic financial model for the Quality Sweater Company to analyze the profitability of a direct mail campaign. The model incorporates various costs associated with printing and mailing catalogs, and it explores how changes in response rates affect overall profitability.

Let us take a look into the questions we would be answering and the information we have:

The Quality Sweater Company sells hand-knitted sweaters.  The company is planning to print a catalog of its products and undertake a direct mail campaign.  The cost of printing the catalog is $20,000 plus $.10 per catalog.  The cost of mailing each catalog (including postage, order forms, and buying names from a mail-order database) is $0.15. 

In addition, the company plans to include direct reply envelopes in its mailing and incurs a $.20 in extra costs for each direct mail envelope used by a respondent.  The average size of a customer order is $40, and the company’s variable cost per order (primarily due to labor and material costs) averages about 80% of the order’s value – that is $32. The company plans to mail 100,000 catalogs.  It wants to develop a spreadsheet model to answer the following questions:

* How does a change in the response rate affect profit?
* For what response rate does the company break even?
* If the company estimates a response rate of 3%, should it proceed with the mailing?
* How does the presence of uncertainty affect the usefulness of the model?  

### Model Setup

Inputs:
1. Printing Costs: $20,000 fixed cost, plus $0.10 per catalog.
2. Mailing Costs: $0.15 per catalog for postage, order forms, and purchasing names.
3. Reply Envelopes: An additional $0.20 cost per response received.
4. Labor and Materials: Variable costs of $32 per order, representing 80% of the average order size ($40).

Calculations:
1. Total Costs: Sum of fixed and variable costs based on the number of catalogs ordered and response rate.
2. Revenue: Calculated by multiplying the number of orders by the average order size.
3. Profit: Total revenue minus total costs.

Analysis Using Excel What-If Tools:
* Data Table: Used to explore how different response rates from 3% to 10% impact the total profit.
* Goal Seek: Applied to determine the break-even response rate where total profit equals $0.

![Quality Sweater Company](https://github.com/adiimated/Excel4BusinessAnalytics/blob/main/images/Quality%20Sweater%20Company.png)

### Answers

#### How does a change in the response rate affect profit?

As the response rate increases, the profit also increases. The relationship between response rate and profit is direct; higher response rates lead to higher profits. This is evident in the shift from a negative profit at lower response rates (3% results in a loss of $21,600) to positive profits at higher response rates (10% yields a profit of $33,000).

#### For what response rate does the company break even?

The company breaks even at a response rate of approximately 5.77%. (Goal Seek)

#### If the company estimates a response rate of 3%, should it proceed with the mailing?

Based on the data table in the spreadsheet, at a 3% response rate, the company faces a loss of $21,600. Therefore, it would not be advisable for the company to proceed with the mailing if a 3% response rate is the best estimate. Proceeding would lead to a financial loss rather than a profit.

#### How does the presence of uncertainty affect the usefulness of the model?

The presence of uncertainty, especially in estimating response rates and variable costs, can significantly affect the model’s accuracy and reliability. If the actual figures deviate from the estimates (such as actual response rates being lower than estimated), the company could end up with unexpected financial outcomes. Uncertainty in the model requires careful risk management and possibly creating more conservative estimates or running multiple scenarios to cover a range of possible outcomes. This allows the company to better prepare for fluctuations and uncertainties in the actual campaign results.


## The 19th Hole Golf Club Pricing Analysis
This project aims to analyze the pricing strategy for golf clubs sold by The 19th Hole, a golf outlet store in the US. By examining the relationship between price and demand, we will determine the optimal price to maximize profit while considering production costs.

The 19th Hole wants to understand how the demand for its golf clubs varies with price to determine the optimal selling price that maximizes profit. The company is also interested in understanding how the optimal price is affected by the unit cost of producing the golf clubs.

| Month | Price ($) | Demand (units in hundreds) |
|-------|-----------|----------------------------|
| 1     | 450       | 45                         |
| 2     | 300       | 103                        |
| 3     | 440       | 49                         |
| 4     | 360       | 86                         |
| 5     | 290       | 125                        |
| 6     | 450       | 52                         |
| 7     | 340       | 87                         |
| 8     | 370       | 68                         |
| 9     | 500       | 45                         |
| 10    | 490       | 44                         |
| 11    | 430       | 58                         |
| 12    | 390       | 68                         |


We are trying to answer these questions:

* Assuming the unit cost of producing a set of clubs is $250, and the price must be a multiple of $10, what price should the company charge to maximize its profit?
* How does the optimal price depend on the unit cost of producing a set of clubs?
* Is the model an accurate representation of reality?

We used Excel to insert trendlines into scatter plots of price vs. demand, testing three different models:

* Linear: \[ y = mx + b \]
* Power: \[ y = ax^b \]
* \[ y = ae^{bx} \]

From these, we determined that the Power model provided the best fit based on the average absolute percent error.

### Answers:

#### Assuming the unit cost of producing a set of clubs is $250, and the price must be a multiple of $10, what price should the company charge to maximize its profit?

From the data table in the spreadsheet, the optimal price for maximizing profit when the unit cost is $250 per set of clubs appears to be $400. At this price, the calculated profit is $955,163.26, which is the highest among the prices tested. This result comes from the one-way data table analysis, which assessed various potential selling prices against their corresponding profits.

#### How does the optimal price depend on the unit cost of producing a set of clubs?

The two-way data table in the spreadsheet provides insight into how the optimal price point shifts with varying unit costs. From the analysis, it is evident that as the unit cost increases, the optimal price also tends to increase. This is due to the need to cover higher costs while still trying to maximize profit. For example, if the unit cost rises from $250 to $300, $350, or even $400, the corresponding optimal selling price increases, demonstrating a direct dependence of the selling price on the unit cost. However, it's also clear that increasing the unit cost reduces the overall profit, as the highest profits are observed at lower unit costs.

#### Is the model an accurate representation of reality?

The model used here, specifically the Power model chosen based on lower average absolute percent error, provides a reasonable approximation of the relationship between price and demand. However, while it serves as a useful tool for simulation and estimation, several factors could impact its accuracy:

    Market Conditions: Changes in the economic environment, competition, or consumer preferences are not accounted for in the model.
    Data Limitations: The model is based solely on historical price and demand data, without consideration for potential outliers or unrecorded variables that could affect demand.
    Model Fit: Even though the Power model was the best among those tested, its average error rates (around 5.9%) suggest that there is still a significant margin of error.

In summary, while the model provides a useful framework for understanding and predicting the price-demand relationship, it should be interpreted with an understanding of its limitations and supplemented with market insights and additional data where possible.
