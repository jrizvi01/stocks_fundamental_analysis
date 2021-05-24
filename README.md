# Stocks_fundamental_analysis

## Brief Background
This application utilizes publicly traded companies' financial data such as Equity (ROE), Free Cash flow over equity, Forward growth rate, and valuation in order to access the viability of an investment in a publicly traded company.

## Who it is for?
Any investor who is interested in learning the fundaments of a company including Return on Equity (ROE), Free Cash flow over equity, Forward growth rate, and valuation.

## Benefits
Currently, there are not many applications available which look at all the elements required to do the valuation without involving manual work. This application will automate fetching the data from public sources and the calculations hence eliminating the need for manual calculations.

## Approach of the Project - Code Structure

1. Make ticker list from csv file with user input
2. Use “for loop” for the ticker list
3. Define dataframes and specify columns
4. Extract data from databases using API
5. Prompt user input where needed
6. Calculate data output
7. Insert data into dataframes
8. Display dataframes and charts

## Technology

Before Execute the Python Code in 'stocks_analysis.ipynb' Please install new library in your environment.
[fundamentalAnalysis](https://pypi.org/project/FundamentalAnalysis/) - FundamentalAnalysis

Pip install fundamental analysis
Functions included
- Detials of companies
- financial Statement
- ratios
- Stock Data

pTools utilized:
* API & .env
* Pandas
* Hvplot
* User Input
* CSV file interaction


## Example
![Plot](https://github.com/jrizvi01/stocks_fundamental_analysis/blob/main/Resources/FreeCashoutput.png)
![Plot](https://github.com/jrizvi01/stocks_fundamental_analysis/blob/main/Resources/ROEoutput.png)
![Plot](https://github.com/jrizvi01/stocks_fundamental_analysis/blob/main/Resources/Valoutput.png)
![Plot](https://github.com/jrizvi01/stocks_fundamental_analysis/blob/main/Resources/TTMgrowth.png)
![Plot](https://github.com/jrizvi01/stocks_fundamental_analysis/blob/main/Resources/Comparison.png)


