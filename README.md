**OVERVIEW**
This project started as an intiative to practise web scraping. On succeeding at this, I realized several operations could be applied on the dataset and so I did.

The dataset includes fundraising statistics of Wikipedia since 2003 to 2022.It initially had fields such as:

          1. Total_assets
          
          2.Revenues
          
          3.Expenses
          
          4.Asset_rise
          
          5.Year
          
          6.Source
          
Meaningless fields like Source were dropped, and the other fields except Year were converted to data type int for mathematical operation purposes.

Then meaningful fields are introduced such as:

          1.ROI- the return on investment from the principal capital.
          
          2.Profit/Expense ratio- what proportion of the revenues goes into profits and expenses.

          3.Profits- what profit did wikipedia make out of the revenues. That is expenses deducted from revenues.

Several graphs are plotted to visualize trends in: total_assets rise, profits, correlations and ROI.

Correlations are also performed to establish relationships between fields such as profits and total_assets are plotted for visualization

The CAGR is finally performed to answer the question at what rate does their asset worth compound annualy?

**INSIGHTS**

1. From the average, Wikipedia is more likely to have an ROI of 1.52 on the principal investment.

2. Profits have slowly been increasing since financial year 2003/04 but they sharply rose in 2020/21 and surged the following year.This makes  2020/21 an outlier needing further analysis

3. From the average, it's very likely 29.68% of revenues will be profit and 70.32% expenses.

4. Total_assets and profits are positively correlated, a correlation of 0.76, thus if Total_assets increase so do profits.

5. Wikipedia's assets have been annualy compounding at a rate of 55%

6. Wikipedia's ROI has been declining since 2003/04

**CONCLUSIONS**

1. At a cagr of 55%, wikipedia's assets have steadily compounded,an indicator of consistency and good enevironment for investing.

2. Wikipedia may strategize on how to increase profit ratio by cutting some costs if possible.

3. Further analysis should be done on year 2020/21

4. Wikipedia should continue investing on assets as they have positively contributed to increased profits.

5. Wikipedia can invest and predict outcome by using an ROI of 1.52 on the principal.

6. Wikipedia should probe why the ROI has been declining
