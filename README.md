# glassdoor-scraper
Given an input of a company, scrapes Glassdoor to get information about that company

=== Description ===

Current version: 1.1.0

This program takes in an input from the terminal and returns a dictionary of information from glassdoor, as well as stock information if applicable. 
Stock information is obtained from Alpha Vantage, https://www.alphavantage.co

=== Pre-Requisites ===

**Download and install Python(https://www.python.org/downloads/). This does not have to be in the same directory as the other files.

Download and install ChromeDriver(https://chromedriver.chromium.org/downloads). You will need to check your version of Chrome beforehand to download the respective version. To do so, go to Chrome and click on the 3 dots in the top-right of the screen. Select 'Settings', then 'About Chrome'. Put the executable into the same file/directory as everything else. If not, you will get the error message: selenium.common.exceptions.WebDriverException: Message: 'chromedriver' executable needs to be in PATH. Please see https://chromedriver.chromium.org/home

Have the library selenium installed. 

=== To Run ===

Go to the filepath with the code. 

Type python3 glassdoor_scrape.py.

You should get a prompt for a company name.

=== Changes ===

You will require your own API key for Alpha Vantage, which can be obtained from their website https://www.alphavantage.co. 
