## Get Korean Stock Price from Naver Finance
Scrap Prices('Open', 'High', 'Low', 'Closing') and daily trading volume of Korean stocks from [NAVER Finance](https://finance.naver.com)


## Example
If you want to get the adjusted closing price of Samsung Electronics(005930.KR) for last 1,000 days,
  ```python
  Samsung = get_data('005930', 1000)['Close']
  ```
 
 If you want to get the daily trading volume of SK Hynix(000660.KR) for last 1,200 days,
  ```python
  SK = get_data('000660', 1200)['Volume']
  ```

## History of change
* First Commit, 06/29/2020
