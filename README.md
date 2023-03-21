# Web scraper CWMS data 網路爬蟲獲取CWMS監測資料
Web scraping is the automated gathering of content and data from a website or any other resource available on the internet.
This tool allows you to scrape Continuous Waste Water Monitoring Open Data System (CWMS) hourly data.

## 重大點源放流水自動連續監測資訊公開查詢系統 CWMS
🔎 Website: https://cwms.tp.gov.taipei/public/History/Opr_History_TrendDay.aspx

## Before running the script
In order to run the script perfectly, please make sure you have installed ***Selenium*** and ***Beautiful Soup***.
### Selenium
Web Scraping with Selenium allows you to gather all the required data using Selenium Webdriver Browser Automation. Selenium crawls the target URL webpage and gathers data at scale.
```Python
$ pip install selenium
$ conda install selenium
```
### Beautiful Soup
Beautiful Soup is a Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
```Python
$ pip install beautifulsoup4
$ conda install beautifulsoup4
```

For further information
https://blog.51cto.com/feishujun/5513713

## Inputs
```Python
# insert the start date and end date as you need
start_date_str = "2023/1/1"
end_date_str = "2023/3/16"
```

## Outputs
Making sure there is a file named data in the same folder as the script
```Python
../data
```

:bug:
