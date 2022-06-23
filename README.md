# Time-series-analysis
- Renewable energy prediction using time series analysis 
  - The main agenda here is to forecast the load usage of renewable energy sources, we have preferred considering the load usage of major energy sources like “Solar” and “Wind” along with the total load used. We have received the dynamic data source which updates daily from PJM.
  - As we have decided to work on the ‘PJM Energy dataset’, we get data from a dynamic website, which changes every.
  - So, we choose the PJM dataset as the main resource to work on our project.So, we choose the PJM dataset as the main resource to work on our project.​
 ### From PJM we have various features to consider are as follows:

- Evaluated At UTC: Evaluating megawatts in Universal time.
- Evaluated At EPT: Evaluating megawatts in eastern prevailing time.
- Datetime Beginning UTC: Beginning of energy consumption in Universal time.
- Datetime Beginning EPT: Beginning of energy consumption in eastern prevailing time.
- Datetime Ending EPT: Ending of energy consumption in eastern prevailing time.
- Datetime Ending UTC: Ending of energy consumption in Universal time.
- Forecast Area: Region in which forecasting is done.
- Forecast MW: How much energy (mw) is used.
- We do forecast on this data; hence we must take time series from features. And region is an important concern to show usage in respective areas.
 ### Our important features are:
- Datetime Beginning EPT/UTC, Datetime Ending EPT/UTC, Forecast Region and Forecast time.*
