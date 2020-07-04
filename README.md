## Get Korean Stock Price from Naver Finance
Scrap prices('Open', 'High', 'Low', 'Closing') or daily trading volume of Korean stocks from [NAVER Finance](https://finance.naver.com)


## Parameteres
**Company ticker symbol**: a string or a list of strings <br>
**lookback period**: an integer


## Example
get_data('Company ticker symbol', 'lookback period')

* If you want to get the adjusted closing price of Samsung Electronics(005930.KR) for last 1,000 days,
  ```python
  Samsung = get_data('005930', 1000)['Close']
  ```
 
* If you want to get the daily trading volume of SK Hynix(000660.KR) for last 1,200 days,
  ```python
  SK = get_data('000660', 1200)['Volume']
  ```
