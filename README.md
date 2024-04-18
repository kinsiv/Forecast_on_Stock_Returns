# Risk Assessment & Forecast on Stock Returns, Data Wrangled from the NYSE
I utilized a multifactor model to examine the predictive power of various financial and economic indicators over 3 years. The factors included swings, shocks, conditional volatility, residual variances, and more. I applied regression analysis to determine the relationship between these factors and the future returns of a diverse set of stocks, as well Google specifically. The study investigates the complexities of returns predictions and the importance of considering a broad range of factors in investment strategies. Predictive models were then evaluated for their accuracy and robustness to unseen events.

## Research Questions:
1. Can share price and other stock attributes be forecasted into the next period in cadence with volatility?
2. Is the model sufficient for identifying the financial risks that occur for investors or do exogenous variables need inclusion?
3. When there is a time of uncertainty, can the risk associated to a specific company's market evaluation be weighed?

## Actionable & Business Insights:
1. Google's trading volume is extrapolated to have a swing range of ~2,000 for 2016. 500 in gains, 1500 in losses. Shareholders appear hesitant to sell. This is promising for a price hike.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/9402680d-3df4-450d-8131-d03b66c8dd7c)

<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

2. Volatility in Google's share price is a range of (-30, 30). The price changes are of increasing amounts, seen at in 2015 Q3. The gradual upwards trend is evidence that holding shares is a low-risk investment.

[![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/96dd06e9-478d-488d-9a0d-eb2faf9425d7)](https://gyazo.com/3d48c449cd0ee1e872895a388cf4680f)


<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

3. Newly antiquated investors can expect an average daily return of 11.5% with an error of 113.5% - caused primarily by 2015's growth.

[![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/391f1dac-2aad-48ed-9cf0-2cb9de490a99)](https://gyazo.com/5dcfd7daaba7ea4333475cd98bf9656e)

<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

4. In the event of say, a financial crisis, this Monte Carlo simulation depicts Google’s closing price. There's potential to swing 40-120 points, depending on the day’s price. Bootstrapping the scenario gave similar results.
* *Note that the below swings can be in either direction (pos or neg). The model outputs all as a pos from its residual-variance based structure. The underlying white forecast identifies which direction.*

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/7e6fcd5a-edaf-484d-bd76-96cac7ef5bd2)

<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

5.  The demand for shares throughout all companies listed on the NYSE is expected to rise. The continuation of this can yield lucrative sells for holders.

![image](https://github.com/kinsiv/RiskAssessment_Forecast_Stocks/assets/89998643/8350ef09-3d61-4486-994b-f757225b4b44)
