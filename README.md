# # Unit 12 Homework: Mission to Mars
## Background
You’re now ready to take on the full web-scraping and data analysis project for the mission to Mars. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## What You're Creating
### This new assignment consists of two technical products. You will submit the following deliverables:
* ### Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

    1. Use automated browsing to visit the Mars NASA news site Links to an external site.. Inspect the page to identify which elements to scrape.
    ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_1_i.PNG)
    ---
    2. Create a Beautiful Soup object and use it to extract text elements from the website.
    ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_1_ii.PNG)
    ---
    3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
        - Store each title-and-preview pair in a Python dictionary. And, give each dictionary two keys: title and preview. An example is the following:
        - Store all the dictionaries in a Python list.
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_1_iii.PNG)
        - Print the list in your notebook.
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_1_iii_pt2.PNG)
        ---
    4. Optionally, store the scraped data in a file or database (to ease sharing the data with others). To do so, export the scraped data to either a JSON file or a MongoDB database.
    ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_1_iiii.PNG)
---
* ### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
    1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.
    ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_i.PNG)
    ---
    2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
     ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_ii.PNG)
    ---
    3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
     ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_iii.PNG)
      ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_iii_pt2.PNG)
     ---
    4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
    
     ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_iv.PNG)
    ---
    5. Analyze your dataset by using Pandas functions to answer the following questions:
        - How many months exist on Mars?
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_v_pt_i.PNG)
        - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_v_pt_ii.PNG)
        - What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/mars_monthly_avg_min_temp.png)
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/mars_monthly_avg_min_temp_asc.png)
        - Which months have the lowest and the highest atmospheric pressure on Mars? 
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/mars_monthly_avg_pressure.png)
        - About how many terrestrial (Earth) days exist in a Martian year? 
        
        ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/mars_mintemp_daily.png)
        
    6. Export the DataFrame to a CSV file.
    ![](https://github.com/acboi0824/Module-12-Web-Scrape-Challenge/blob/main/Starter_Code/Resources/deliverable_2_v_pt_vi.PNG)
