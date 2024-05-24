# Web Scraping and Data Analysis Project

## Project Overview

This project involves web scraping and data analysis using Python, BeautifulSoup, Splinter, and Pandas. The aim is to scrape data from two Mars-related websites and analyze the data to extract meaningful insights. The project is divided into two main deliverables.

## Deliverables

### Deliverable 1: Scrape Titles and Preview Text from Mars News

1. **Objective**: Scrape the titles and preview text from Mars news articles.
2. **Tools Used**: Splinter for automated browsing and BeautifulSoup for HTML parsing.
3. **Steps**:
   - Use Splinter to visit the Mars news site.
   - Extract the HTML code using BeautifulSoup.
   - Parse the titles and preview text of news articles.
   - Store the extracted data in a list of dictionaries with `title` and `preview` as keys.
   - Optionally, export the scraped data to a JSON file.
4. **Output**: A list of dictionaries containing the titles and preview text of Mars news articles.

### Deliverable 2: Scrape and Analyze Mars Weather Data

1. **Objective**: Scrape and analyze Mars weather data from an HTML table.
2. **Tools Used**: BeautifulSoup for HTML parsing and Pandas for data analysis.
3. **Steps**:
   - Use Splinter to visit the Mars Temperature Data Site.
   - Extract the HTML table using BeautifulSoup.
   - Assemble the scraped data into a Pandas DataFrame with appropriate column headings.
   - Cast the data to appropriate data types (datetime, int, float).
   - Analyze the dataset to answer specific questions:
     - Number of months on Mars.
     - Number of Martian days of data available.
     - Coldest and warmest months on Mars.
     - Months with the lowest and highest atmospheric pressure.
     - Number of terrestrial days in a Martian year.
   - Visualize the results using bar charts.
   - Export the DataFrame to a CSV file.
4. **Output**: A Pandas DataFrame containing the Mars weather data and visualizations of the analysis.

## Repository Structure

- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news titles and preview text.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `mars_news.json` (optional): JSON file containing the scraped Mars news data.
- `mars_weather.csv`: CSV file containing the Mars weather data.

## Instructions

### Part 1: Scrape Mars News

1. Open `part_1_mars_news.ipynb`.
2. Use Splinter to visit the Mars news site.
3. Extract and parse the titles and preview text using BeautifulSoup.
4. Store the data in a list of dictionaries.
5. Print the list of dictionaries or export to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data

1. Open `part_2_mars_weather.ipynb`.
2. Use Splinter to visit the Mars Temperature Data Site.
3. Extract the HTML table using BeautifulSoup.
4. Assemble the data into a Pandas DataFrame.
5. Cast data to appropriate types and perform analysis.
6. Visualize the results and export the DataFrame to a CSV file.

## Submission

Submit the URL of your GitHub repository containing the Jupyter notebooks and output files for grading.

## References

- Mars News website: [NASA's Mars News](https://mars.nasa.gov/)
- Mars Temperature Data Site: [Mars Facts](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

---

## Author

Kevin Ngala

© 2024 edX Boot Camps LLC
