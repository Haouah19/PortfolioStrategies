# ProtfolioStrategies
***

The project is based on the Excel file *sbf120_as_of_end_2018.xlsx* that contains prices of SBF 120 components (as of end 2018) over the period 2011-now.

We consider an investment universe of 10 stocks corresponding to those having the highest market capitalization as
of end 2018.

The notebook compares, in terms of Sharpe ratio and maximum drawdown, the respective performance of the three following portfolios over the year 2019 :
<ul>
<li><b>An equally-weighted portfolio</b> with the above 10 stocks (weights are considered on a daily basis). </li>

<li><b>A Markowitz minimum-variance portfolio</b> (with the above 10 stocks), the covariance matrix being computed over
2017-2018 and not updated – using the empirical covariance matrix is enough for the assessment. </li>

<li><b>An ERC portfolio</b> (with the above 10 stocks), the covariance matrix being computed over 2017-2018 and not
updated – using the empirical covariance matrix. </li>

</ul>

The last cell of the notebook plot a graph with the three PnL trajectories (with an initial wealth of 1 million
euros).
