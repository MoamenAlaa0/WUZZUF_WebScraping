# :pick: WUZZUF Web Scraping 
Scraping [Wuzzuf](https://wuzzuf.net/jobs/egypt) website by applying two different web scraper versions. The first version was my first time doing web scraping, and after two weeks with hard working by reading in web scraping and applying some small projects like [YouTube comments](https://github.com/MoamenAlaa0/YouTube_Comments_WebScraping) and [Amazon reviews](https://github.com/MoamenAlaa0/Amazon_WebScraping) scraping, 
I have returned to implement the second version.

### Version :one: using: [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) and [Selenium](https://selenium-python.readthedocs.io/getting-started.html)

| Library | Description |
| --- | --- |
| requests | provides us with the capabilities of sending an HTTP request to a server |
| BeautifulSoup | pull the data out of HTML and XML files |
| urljoin | parse module to join a base URL with another URLs |
| time.sleep | add delay in the execution of a program |
| selenium | automation testing tool used to scrape dynamic javascript websites |


I have used requests library that provides us with the capabilities of sending an HTTP request to a server

sending a get HTTP request to retrieve the data 
```python
response = requests.get(base_url, headers = headers, timeout = 5)

```


-----
### Version :two: using: [Requests-HTML](https://requests.readthedocs.io/projects/requests-html/en/latest/)



