## Risk Assessment & Forecast on Stock Returns
In my analysis of forecasting NYSE stocks, I utilized a multifactor model to examine the predictive power of various financial and economic indicators over 3 years. The factors included swings, shocks, closing prices, trading volume, and more. I applied regression analysis to determine the relationship between these factors and the future returns of a diverse set of stocks. The study investigates the complexities of returns predictions and the importance of considering a broad range of factors in investment strategies. Predictive models were then evaluated for their accuracy and robustness to unseen events.

## Research Questions:
1. Can share price and other stock attributes be forecasted into the next period in cadence with volatility?
2. Is the model sufficient for identifying the financial risks that occur for investors or do exogenous variables need inclusion?
3. When there is a time of uncertainty, can the risk associated to a specific company's market evaluation be weighed?

## Actionable & Business Insights:
1. Google's trading volume is extrapolated to have a swing range of ~2,000 for 2016. 500 in gains, 1500 in losses. Shareholders appear hesitant to sell. This is promising for a price hike.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/9402680d-3df4-450d-8131-d03b66c8dd7c)


2. Volatility in Google's share price is a range of (-40, 20). The price changes are of increasing amounts, seen at in 2015. The gradual upwards trend is evidence that holding shares is a low-risk investment.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/bc43114c-8a08-4a9e-af61-f29340cad702)


3. Newly antiquated investors can expect and an average daily return of 11.5% with an error of 113.5% - caused primarily by 2015's growth.

[![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/391f1dac-2aad-48ed-9cf0-2cb9de490a99)](https://gyazo.com/5dcfd7daaba7ea4333475cd98bf9656e)


4. In the event of say, a financial crisis, this Monte Carlo simulation depicts Google’s closing price. There's potential to swing 40 - 120 points dependent on the day’s price. Bootstrapping the scenario gave similir results.
*Note that these swings can be in either direction (pos or neg). The model outputs all as a pos from it's structure.*

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/7e6fcd5a-edaf-484d-bd76-96cac7ef5bd2)

  
5.  The overall NYSE volume and close prices for 2016 are predicted to extend current figures. Google is likely to benefit shareholders given the market and company performance.
