# 12-1 L/S momentum strategy, implementation and enhancements
Ideas to improve the return-over-risk ratio of a momentum strategy

************************************************* INTRODUCTION *************************************************

Price momentum is one of the most well-known signals in quantitative investment, first reported by Jegadeesh and Titman in The Journal of Finance (1993). 
Assignement is to create and backtest the traditional 12-minus-1 (12-1) month price momentum strategy, based on the attached monthly return dataset to construct the 12-1 month momentum signals.

************************************************* INSTRUCTIONS *************************************************

1. Form a momentum strategy that is long the top 20% and short the bottom 20% of stocks based on the momentum signal rankings. Stocks within the long and short portfolios are equally weighted (1/n). The momentum portfolio should be rebalanced monthly assuming a one month holding period.
2. Report the annualized return and volatility for such a momentum strategy.
3. Think about possible enhancements that deliver a superior return over risk ratio than the 12-1 momentum.
4. Bonus: Implement the enhancements into MATLAB/Python.
5. Prepare a presentation which explains your method and results. Comment on the momentum strategy.

************************************************* DATA *************************************************

The data file contains monthly returns of stocks being included in the MSCI World index, in the period of January 1995 – October 2021. 
Missing data means that the stock was not included in the MSCI World Index, therefore should not be used to form the long-short strategy.
