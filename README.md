# Mars Data Scraping and Analysis
### Overview
This repository contains Python notebooks that scrape and analyze data from Mars-related sources. The project is divided into multiple deliverables, each focusing on a different aspect of data collection and processing using web scraping techniques and data visualization.

### Technologies Used
* Python
* Splinter
* BeautifulSoup
* pandas
* matplotlib
* Jupyter Notebook

### Deliverables
#### Deliverable 1: Scrape Titles and Preview Text from Mars News
##### Objective
Automate the process of scraping news article titles and preview text from a Mars news website.
##### Code Summary
* Import necessary libraries splinter, BeautifulSoup).
* Use Splinter's Browser to load the Mars news page.
* Create a BeautifulSoup object to parse the HTML.
* Extract article titles and preview text from the page.
* Store the extracted data in a list of dictionaries.
* Print the results to verify successful scraping.
* Close the browser session.

#### Deliverable 2: Scrape and Analyze Mars Weather Data
##### Objective
Automate the process of scraping Mars weather data and erform analysis on the collected dataset.
##### Code Summary
* Import necessary libraries (splinter, BeautifulSoup, matplotlib, pandas).
* Use Splinter's Browser to visit the Mars temperature data site.
* Create a BeautifulSoup object to parse the HTML.
* Extract the weather data from the table.
* Store the data in a pandas DataFrame.
* Clean and convert data types for analysis.
* Analyze the data (e.g., find the coldest and warmest months, calculate average pressure, etc.).
* Plot visualizations for temperature and pressure by month.
* Estimate the number of Earth days in a Martian year.
* Export the cleaned data to a CSV file.
* Close the browser session.