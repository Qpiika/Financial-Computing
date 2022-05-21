# Financial-Computing

## Part 2: Data preprocessing
data preparation.ipynb
By using the stock.csv file 

## Part 3: Portfolio analysis
Analysis of portfolio.ipynb
The code of deep learning may run seconds.

## Part 4: Time Series
TimeSeries.ipynb
You should do "pip install pandas_datareader" if you don't have this package.

## Part 5: Generalize our model
This is a project that you can get the cumulative return of each portfolio, you have 2 choices to generate the cumulative return image and get the corresponding weights.
Portfolio_monte.py
main.ipynb
Run in main.ipynb and can call the function in Portfolio_monte.py
When run main.ipynb:
you can choose : A: select random n stocks
                 B: give the stock list
If you choose A, you should input an integer then the code will give you random n stocks from tushare and get the cumulative return and corresponding weights.
But if the code choose a null stock, it will change the random stocks until there is no null stock.
And if you choose B, you should input all stocks you want to get a portfolio of them and push Enter to the end. Then it will be shown.
But if you input a stock which is not include in tushare or wrong stock code, it will be warning and you should choose again.
