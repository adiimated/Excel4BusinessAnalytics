# Excel For Business Analytics

## Quality Sweater Company Financial Model
This project involves developing a dynamic financial model for the Quality Sweater Company to analyze the profitability of a direct mail campaign. The model incorporates various costs associated with printing and mailing catalogs, and it explores how changes in response rates affect overall profitability.

Let us take a look into the questions we would be answering and the information we have:

The Quality Sweater Company sells hand-knitted sweaters.  The company is planning to print a catalog of its products and undertake a direct mail campaign.  The cost of printing the catalog is $20,000 plus $.10 per catalog.  The cost of mailing each catalog (including postage, order forms, and buying names from a mail-order database) is $0.15. In addition, the company plans to include direct reply envelopes in its mailing and incurs a $.20 in extra costs for each direct mail envelope used by a respondent.  The average size of a customer order is $40, and the company’s variable cost per order (primarily due to labor and material costs) averages about 80% of the order’s value – that is $32.  The company plans to mail 100,000 catalogs.  It wants to develop a spreadsheet model to answer the following questions:

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

## Answers

1. How does a change in the response rate affect profit?

From the "WHAT IF ANALYSIS: Data Table" in the spreadsheet:

As the response rate increases, the profit also increases. The relationship between response rate and profit is direct; higher response rates lead to higher profits. This is evident in the shift from a negative profit at lower response rates (3% results in a loss of $21,600) to positive profits at higher response rates (10% yields a profit of $33,000).

2. For what response rate does the company break even?

The company breaks even at a response rate of approximately 5.77%. This is indicated in the "WHEN DOES THE COMPANY BREAK EVEN ?" section on the spreadsheet, which shows that at this response rate, the total costs and total revenue are equal, resulting in zero profit.

3. If the company estimates a response rate of 3%, should it proceed with the mailing?

Based on the data table in the spreadsheet, at a 3% response rate, the company faces a loss of $21,600. Therefore, it would not be advisable for the company to proceed with the mailing if a 3% response rate is the best estimate. Proceeding would lead to a financial loss rather than a profit.

4. How does the presence of uncertainty affect the usefulness of the model?

The presence of uncertainty, especially in estimating response rates and variable costs, can significantly affect the model’s accuracy and reliability. If the actual figures deviate from the estimates (such as actual response rates being lower than estimated), the company could end up with unexpected financial outcomes. Uncertainty in the model requires careful risk management and possibly creating more conservative estimates or running multiple scenarios to cover a range of possible outcomes. This allows the company to better prepare for fluctuations and uncertainties in the actual campaign results.
    
