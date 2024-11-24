
# Project Description
In this project, I am scraping data from the website "Books to Scrape" because the site states that *"We love being scraped!"*. However, it is not that straightforward. Without further ado, let's dive into more details about the project.

I used two main libraries: 'requests' and 'BeautifulSoup', along with additional libraries such as 'pandas' and 'NumPy'.

First, I used custom headers to make the request appear as though it's coming from a real browser. Then, I sent a GET request to fetch the HTML content of the "Books to Scrape" website. I used BeautifulSoup to parse the webpage content with the 'lxml' parser.

After inspecting the website, I found that the data I wanted to extract about books is within the 'product_pod' class. I extracted the data through a loop, and after extracting all the data, I stored it in a CSV file.



You Can use this Data Set for your Data Science or Data Analytics Project ; ) 

# Thank You

