## Web Scraping Project
This project is done as a final assessment project for the class Web Scraping for Data Science and Business Analytics program at WNE, University of Warsaw.
Our project aims to create a comprehensive mobile phone dataset by scraping data from the popular e-commerce website Flipkart.com. We will be utilizing the power of web scraping using three different tools: BeautifulSoup, Selenium, and Scrapy. We will save it in a structured format, such as CSV or Text for each of the methods used. The information that is extracted is the same in each case and for each method, there are 2 files saved. One file contains the links of each webpage for each phone. The second file contains useful information from each webpage to gather phone specifications.

## Project Description
https://docs.google.com/document/d/15_6DpmbG29Iv1Ttwfo_zGYjj6Xtns6keppAzZzXaVD0/edit?fbclid=IwAR1cM_bS0ElPo-OVLZ4HyDnxeIvxUToLaiEJ9EadI4Ch7yRPohdJl7nUKKg

## Project Presentation-video about how to run these 3 scrapers


## How to run？（text version）
### BeautifulSoup

### Scrapy

To run Scrapy using the command line, follow these steps:

1. Open a terminal or command prompt on your system.

2. Navigate to the directory where your Scrapy project is located. This is the directory that contains the scrapy.cfg file.

3. Use the scrapy crawl command followed by the spider name to run the spider. For example, if your spider's name is "myspider", run the following command: scrapy crawl myspider

4. Scrapy will start executing the spider, sending requests, and processing the responses. You will see the log messages and output in the terminal/command prompt.

5. You can also use additional options with the "scrapy crawl" command to customize the behavior of the spider:

    "-o output.json" or "-o output.csv" : Use these options to specify the output format for the scraped data. You can choose to save the data in JSON  or CSV format. For example:  "scrapy crawl myspider -o output.csv"

### Selenium

1. Install Selenium: Use pip to install the Selenium package by running the following command:pip install selenium

2. Download a WebDriver: Chrome: ChromeDriver (https://sites.google.com/a/chromium.org/chromedriver/downloads)

3. Running existed Selenium script in project (process include :Create a WebDriver instance,Interact with web elements,Perform actions: Use the WebDriver's methods to perform actions,Close the WebDriver)

4. Finally the output will be a .csv document.

5. ###Ensure that the WebDriver executable is accessible and the necessary browser is installed on your system. also you have install package  selenium,time,csv###

   
