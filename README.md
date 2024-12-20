# web-scraping-challenge

## Part 1: Scrape Titles and Preview Text from Mars News

1. Visit the Website

    Use automated browsing with the Splinter library to visit the Mars News site, which will load the page using Chrome.

2. Scrape the Website

    Create a BeautifulSoup object to parse the HTML content of the page.
    
    Extract the news article titles and preview text from the page.
    
3. Store the Results

    Store each title and preview pair in a dictionary with keys title and preview.
    
    Add all dictionaries to a list to hold the scraped data for further use or export.

## Part 2: Scrape and Analyze Mars Weather Data
1. Visit the Mars Temperature Data Site

    Automated Browsing: Use automated browsing to visit the Mars Temperature Data Site.

    Inspect the Page: Identify the table containing the weather data by inspecting the HTML structure.

2. Scrape the Website

    Create a BeautifulSoup Object: Use BeautifulSoup to parse the HTML and extract the weather data from the table.

    Extract Data: Store the following information in a Pandas DataFrame:

        id: Identification number of a single transmission from the Curiosity rover.

        terrestrial_date: Date on Earth.

        sol: Number of Martian days since Curiosity landed.

        ls: Solar longitude.

        month: Martian month.

        min_temp: Minimum temperature in Celsius.

        pressure: Atmospheric pressure at Curiosity's location.

3. Data Processing

    Examine Data Types: Ensure correct data types (e.g., datetime for terrestrial_date, float for min_temp and pressure).

4. Data Analysis

    1. How many months exist on Mars?
       Count the unique Martian months.

    2. How many Martian days worth of data?
       Count the number of rows (Martian days).

    3. Coldest and Warmest Months:
       Calculate the average minimum temperature for each month and plot the results.
    
    4. Lowest and Highest Atmospheric Pressure:
       Calculate average atmospheric pressure for each month and plot the results.
    
    5. How many terrestrial (Earth) days in a Martian year?
       Estimate the number of Earth days in a Martian year.
    
    6. Plot Daily Minimum Temperature:
       Visually compare daily minimum temperatures over time.

5. Export Data
    Export to CSV: Save the cleaned DataFrame as a CSV file for sharing or future use.


