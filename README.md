# WebScraper
This webscraper is written to scrape github topics

Web Scraping : Is a Techniques to get or fetch data from website through HTML get request in a policy compliant manner.

Installs needed:
A). Requests : Run pip install requests  . The requests module allows us to send http requests to the website we want to scrape.
B) pandas : import pandas as pd. To save the read data into csv files
C). BeautifulSOAP : Run pip install beautifulsoap4 . Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.

Preparation:
A).  Find the URL that you want to scrape
For this example, we are going scrape topics from github website to extract the topics, description and urls. The URL for this page is githhub.com/topics

B).  Inspecting the Page
The data is usually nested in tags. So, we inspect the page to see, under which tag the data we want to scrape is nested. To inspect the page, just right click on the element and click on “Inspect”.


Here's an outline of the steps we'll follow:
1. Download the webpage using requests
2. Parse the HTML source code using beautiful soup
3. Extract topic names, descriptions and URLs from page
4. Compile extracted information into Python lists and dictionaries
5. Extract and combine data from multiple pages
6. Save the extracted information to a CSV file.
