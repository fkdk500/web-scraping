Web Scraping

It is full web-scraping and data analysis project. 

It is to apply the learned skill to  HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. It is also expected to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

The challenge also gives opportunity to strengthening the same core skills that have been aquired in the privious modules: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.eb-scraping.

This assignmnet consists of two technical products. 

    Deliverable 1: Scrape titles and preview text from Mars news articles.

    Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Part 1: Scrape Titles and Preview Text from Mars News
    -Inspect the page to identify which elements to scrape(Mars news site)
    -Create a Beautiful Soup object and use it to extract text elements from the website.
    -Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
    -Optionally, store the scraped data in a file (to ease sharing the data with others). 

Part 2: Scrape and Analyze Mars Weather Data
    -Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
    -Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
    -Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
    -Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types
    -Analyze your dataset by using Pandas functions to answer the specific questions:
        -How many months exist on Mars?
        -How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        -What are the coldest and the warmest months on Mars (at the location of Curiosity)
        -Which months have the lowest and the highest atmospheric pressure on Mars? 
        -About how many terrestrial (Earth) days exist in a Martian year?

    -Export the DataFrame to a CSV file.