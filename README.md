# # Unit 12 Homework: Mission to Mars
## Background
You’re now ready to take on the full web-scraping and data analysis project for the mission to Mars. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## What You're Creating
### This new assignment consists of two technical products. You will submit the following deliverables:
* ### Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

    1. Use automated browsing to visit the Mars NASA news site Links to an external site.. Inspect the page to identify which elements to scrape.
    2. Create a Beautiful Soup object and use it to extract text elements from the website.
    3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
        - Store each title-and-preview pair in a Python dictionary. And, give each dictionary two keys: title and preview. An example is the following:
        - Store all the dictionaries in a Python list.
        - Print the list in your notebook.
    4. Optionally, store the scraped data in a file or database (to ease sharing the data with others). To do so, export the scraped data to either a JSON file or a MongoDB database.
---
* ### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
    1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.
    2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
    3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
    4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
    5. Analyze your dataset by using Pandas functions to answer the following questions:
        - How many months exist on Mars?
        - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    6. Export the DataFrame to a CSV file.
