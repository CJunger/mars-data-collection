# mars-data-collection
Two Technical products have been requested, these are the deliverables.

## Tools Used:
Python, Jupyter Notebooks, BeautifulSoup, Splinter, Pandas

### Deliverable 1: Scrape titles and preview text from Mars news articles.
Using the starter code, use automated browsing to visit (https://static.bc-edx.com/data/web/mars_news/index.html)

After inspecting the page, Create a Beautiful Soup Object and extract the text elements from the website.

Extract the titles and preview text of the news articles that you scraped. 

Store the scraping results in Python data structures as follows:

  Store all the dictionaries in a Python list.
  Print the list in your notebook.


### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Use automated browsing to visit (https://static.bc-edx.com/data/web/mars_facts/temperature.html). 

Inspect the page to identify which elements to scrape.

Use BeautifulSoupe to create an object and scape the data in the HTML table.

Assemble the scraped data into a data frame using Pandas.

Examine the data types and covert if necessary.

Analyze the dataset using Pandas functions to answer these questions:
  
  - How many months exist on Mars?
  
  - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  
  - What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
  
  To answer this question:
  
  - Find the average minimum daily temperature for all of the months. (Plot the results)
  
  - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  
  - Find the average daily atmospheric pressure of all the months. (Plot the results)

  - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  
  - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  
  - Visually estimate the result by plotting the daily minimum temperature.


Export the DataFrame to a CSV (see MarsData.csv)



### Resources
https://github.com/Nerdosth/web-scraping-mars-news/blob/main/mars_data_scraping.ipynb

I used this to help understand how to store the lists and dictioaires in the first notebook.
