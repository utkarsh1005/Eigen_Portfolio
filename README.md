# Eigen_Portfolio 
- Developed portfolio from data of 30 US stocks fetched from 3rd party API.
- Applied PCA on splitted data to capture major variance (risk) of collection of stocks.
- Performed EDA of stocks data, each component of PCA and it's associated variance.
- Normalised top 5 components selected through EDA and judged each model based on the metric called Sharpe Ratio.
- Calculated Annualized Sharpe, volatility and returns & captured each stocks weightage in the same.
- Models were than backtested on the testing data and 2 models were finalised based on highest sharpe and highest returns respectively.

### Future Improvements:
- Use more advanced metric like Sortino Ratio to handle only negative return volatility.
- Use S&P500 data as benchmark index for comparing model performance with market.

