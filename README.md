## Risk Assessment & Forecast on Stock Returns
In my analysis of forecasting NYSE stocks, I utilized a multifactor model to examine the predictive power of various financial and economic indicators over 3 years. The factors included swings, shocks, closing prices, trading volume, and more. I applied regression analysis to determine the relationship between these factors and the future returns of a diverse set of stocks. The study investigates the complexities of returns predictions and the importance of considering a broad range of factors in investment strategies. Predictive models were then evaluated for their accuracy and robustness to unseen events.

## Research Questions:
1. Can share price and other stock attributes be forecasted into the next period in cadence with volatility?
2. Is the model sufficient for identifying the financial risks that occur for investors or do exogenous variables need inclusion?
3. When there is a time of uncertainty, can the risk associated to a specific company's market evaluation be weighed?

## Actionable & Business Insights:
*Figures are in the millionths. 1,000 = 100,000. Data is forecasted in 2016 with records from 2013 - 2015.*
1. Google's trading volume is extrapolated to have a swing range of ~2,000 for 2016. 500 in gains, 1500 in losses. Shareholders appear hesitant to sell. This is promising for a price hike.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/9402680d-3df4-450d-8131-d03b66c8dd7c)

2. Volatility in Google's forecasted 2016 closing price is a range of (-20, 30). Holding shares is a low-risk investment, given the stability long-term; since for every positive there’s a lesser negative shock nearby.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/bc43114c-8a08-4a9e-af61-f29340cad702)

3. Average daily return is 11.5% with an error of 113.5%. 

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/391f1dac-2aad-48ed-9cf0-2cb9de490a99)

4. In the event of extreme circumstances, such as the financial crisis of 2008, a Monte Carlo simulation depicts Google’s closing price with potential to swing 40 - 120 points dependent on the day’s price. Bootstrapping the scenario gave a similar swing and average close.
5.  The overall NYSE volume and close prices for 2016 are predicted to extend current figures. Google is likely to benefit shareholders given the market and company performance.
