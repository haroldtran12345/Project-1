# Project-1
## Project Name 
Impact of various factors on car manufacturers stock prices & car sales

## Project description 
This project is about statistically analyzing various car stocks  and see how inflation, unemployment, chip shortage, commodities like oil, metals like silver, gold, silicon affected the car stock prices between 2014 and 2021. This is an important step in our full-stack journey as we will now use our newly acquired skills and knowledge in this project.  

### APIs
Project framework initialized with multiple server-side API calls to  find data for analysis. We made API calls to 
* yahoofinance.com
* quandl.com
* bls.gov 
* goodcarbadcar.net

### Technologies used:
* Python Pandas 
* API calls
* JSON
* Matplotlib, plotly for graphing

## Table of Contents:
_______________________________________________________________________
1. [Statistical analysis of Unemployment & Car stocks, Unemployment & Car sales] https://github.com/MartaWoodkowski/Project-1/blob/main/CPJ_notebook.ipynb
     * Creating a dataframe with the acquired monthly data of stock prices from Api calls to yahoo finance of 10 car manufacturers. Also did an Api call to quandl to get the unemployment rates across the country from Jan 2014 to June 2021
     * Explored and analyzed the acquired data, and did a quick quality check.
     * Did calculations to get the monthly returns and cumulative returns of all the car stocks. 
     * Created plots with the analyzed data to visualize how unemployment affected car stocks with the monthly and cumulative returns of stocks.
     * Read the csv file to get the  total cars sold across US from Jan 2014 to June 2021. 
     * Plotted a graph to see how unemployment affected car sales across the country
     * Finally analyzing how car stocks, car sales, are correlated with unemployment.
     * Concluding my analysis with the observations and findings from the graphs. 
     * [Visualizations] https://github.com/MartaWoodkowski/Project-1/tree/main/output_data/unemployment_visuals 
2. [Statistical analysis of US Inflation vs Car manufacturers stock price change & US Car Sales] https://github.com/MartaWoodkowski/Project-1/blob/main/MW_notebook.ipynb
     * Collected monthly Consumer Price Index (CPI) data from the U.S Bureau of Labor Statistics (API calls/JSON) and monthly U.S car sales from U.S Bureau of Economic Analysis (table copy from GCBC) and stored values in respective DataFrames (timeframe: January 2014 to June 2021)
     * Calculated monthly percentage changes for each dataset (CPI, car sales, stock price) and derived corresponding R-values (correlation coefficient).  Also calculated how inflation latency impacts US car sales.
     * Created visuals (line chart, scatter plots, bar chart) to illustrate the correlation (e.g. linear regression) between stock price/car sales and CPI data.
     * Analyzed data and visuals and provided analysis of how inflation (based on CPI) affects car stock prices and US car sales.
     * [Visualizations] https://github.com/MartaWoodkowski/Project-1/tree/main/output_data/inflation_visuals
3. [Statistical analysis of carsales and car stocks with various commodities] https://github.com/MartaWoodkowski/Project-1/blob/main/HT_notebook.ipynb
     * Created a dataframe of 10 car automobile stocks and 4 commodities from yahoo finance API
     * Analyzed the data of 4 commodities against carsales by using monthly returns via price and percentage
     * Created a line graph with the anaylsis 
     * Analyzed the data of 10 car automobile stocks against 4 commodities by using monthly returns via price and percentage
     * Created a line graph for the total average percentage return of the car automobile stocks against the average percentage of each of the 4 commodities 
     * Analyzed the data to how each of them are correlated
     * [Visualizations] https://github.com/MartaWoodkowski/Project-1/tree/main/output_data/commoditiy%20visual
4. [Statistical analysis of chip and car stocks] https://github.com/MartaWoodkowski/Project-1/blob/main/ML_notebook.ipynb
     * Pull dataframe of 10 semicondictor companies we will be using
     * Clean up dataframe to match the car stock price dataframe
     * Create overviews for chip stocks and car stocks
     * Merge two dataframe for the analysis
     * Select the largest semiconductor manufacturer as our sample data to compare various car stocks
     * Plot scatter plots to find out if there's correlation between the largest chip manufactuer's stock and the car company's stock
     * Calculate avg chip stock vs avg car stock
     * Plot scatter plot to find out if avg chip stock is correlated with avg car stock
     * [Visualization]https://github.com/MartaWoodkowski/Project-1/tree/main/output_data/semiconductor_shortage_visuals
     
## Our Team
* Chithra Priya Janardhana / https://github.com/mriganv
* Marta Woodkowski / https://github.com/MartaWoodkowski
* Michael Liu / https://github.com/michaelliu710
* Harold Bao Hung Tran / https://github.com/haroldtran12345

