# Econometrics

# The tasks completed by submission 1

"Context: On October 30th, 2019, the US Federal Reserve voted to reduce the benchmark interest rate 25 basis points.  Assume you are a Portfolio Manager of a Gold ETF, and then assume you are a Portfolio Manager of an Equity ETF."	Pts	45.0		Version: June 2021																		
"Steps 1 through 8 must be done using Python in a Jupyter notebook or R knitted file. See the ""Submission Checklist"" tab for more details."																						

0	Selecting a data set<br />																				
"Discuss with your group members the data sets you want to select from the ""Data Sources"" tab. "	<br />																					
0.1	Select a gold Exchange Traded Fund.	0		

0.2	Select an equity ETF from outside the US.	0		

# 1	Data Importing	

1.1	"Import closing daily interest rates of the 6 active benchmarks of US Treasury yields, for the months of October 2019 and November 2019 (approximately 40 - 45 data points).
You will likely use 2-year, 3-year, 5-year, 7-year, 10-year, and 30-year maturities."	1	

1.2	Import your gold ETF prices for the months of October 2019 and November 2019	0.5				

1.3	Import your equity ETF price for the months of October 2019 and November 2019	0.5				

# 2	Data Processing			

2.1	Compute the daily returns of your Gold ETF	0.5				

2.2	Compute the daily returns your Equity ETF	0.5		

# 3	Data Summaries					

3.1	"For the month of October 2019, compute the average yield for each benchmark security.  Repeat the average calculation for November 2019."	0.5					

3.2	"For the month of October 2019, compute the average price the Gold ETF.  Repeat the average calculation for November 2019."	0.5									

3.3	"For the month of October 2019, compute the average price the Equity ETF.  Repeat the average calculation for November 2019."	0.5							

3.4	"For the month of October 2019, compute the standard deviation for each benchmark security.  Repeat the average calculation for November 2019."	0.5			

3.5	"For the month of October 2019, compute the standard deviation of the Gold ETF.  Repeat the average calculation for November 2019."	0.5						

3.6	"For the month of October 2019, compute the standard deviation of the Equity ETF.  Repeat the average calculation for November 2019."	0.5		

# 4	Graphing				

4.1	Graph the 6 benchmark securities for the 2 months on 1 plot.  That means the 6 yield series are overlaid on the same area.  Add a legend	1				

4.2	"On a separate graph, plot the gold ETF prices (not returns!) for the 2 months.  Use the left-side axis for the price label"	1								

4.3	"On the same graph, plot the equity ETF prices (not returns!) for the 2 months.  Be sure to use a separate scale, and the right-side axis for the price label"	1																					
	"Therefore, each series will show variation, even though they may be on very different price scales."				
  
# 5	Fitting the Yield Curve				

5.1	"Use either Nelson-Siegel, or Nelson-Siegel-Svensson to fit the Yield Curve.  Write out the equation."	0						

5.2	Fit the yield curve each day using the 6 benchmark yields for the October data	2									

5.3	Fit the yield curve each day using the 6 benchmark yields for the November data	2									

5.4	"What are the significant changes, if any?  Be specific with regards to the values of the parameters! ---  Discuss as a group and include the answer in the html document for this question."	1																					

# 6	Modeling Prices					

6.1	"Using the October gold ETF prices, run an ARMA model with your choice of parameters."	2				

6.2	"Using the November gold ETF prices, run an ARMA model with your choice of parameters."	2				

6.3	"Using the October equity ETF prices, run an ARMA model with your choice of parameters."	2				

6.4	"Using the November equity ETF prices, run an ARMA model with your choice of parameters."	2			

6.4	"In each case, justify which model is best."	1			

6.5	"What are the significant changes, if any?  Be specific with regards to the values of the parameters! --- Discuss as a group and include the answer in the html document for this question."	1																					

# 7	Modelling Volatility								

7.1	"Using gold ETF prices, find the daily high minus low for each month.  Compute the average for October.  Compute the average for November."	0.5						

7.2	"Using the gold ETF returns, find the standard deviation for October.  Repeat for November"	0.5												

7.3	"Using the October gold ETF returns, find a GARCH(1,1) model.  Repeat for November (3 points)"	3			

7.4	"What are the significant changes, if any?  Be specific with regards to the values of the parameters! --- Discuss as a group and include the answer in the html document for this question."	1																					

7.5	"Using equity ETF prices, find the daily high minus low for each month.  Compute the average for October.  Compute the average for November."	0.5				

7.6	"Using equity ETF returns, find the standard deviation for October.  Repeat for November"	0.5													

7.7	"Using October equity ETF returns, find a GARCH(1,1) model.  Repeat for November (3 points)"	3									

7.8	"What are the significant changes, if any?  Be specific with regards to the values of the parameters! --- Discuss as a group and include the answer in the html document for this question."	1																					

# 8	Correlation				

8.1	"Compute the Pearson correlation between the gold and equity returns in October 2019.  Repeat for November 2019. --- Interpret the results as a group and include the answer in the html document for this question.  The interpretation should discuss the degree of correlation, and if it is affected by extreme returns."	1																					
