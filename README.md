# Google Ads Scraping Project

## Description

The Google Ads Scraping Project is a Python-based web scraping tool that allows users to extract data from Google Ads based on a specific search term. The tool utilizes the Selenium library to automate web browsing and data extraction.

With this project, users can input a search term of their choice, and the script will launch a Chrome browser, perform the search on Google, and scrape relevant data from the Google Ads displayed on the search results page. The extracted data includes information such as ad names, prices, addresses, and images.

The scraped data is then saved in a CSV file, making it easy to analyze, manipulate, and further process the data using other data analysis tools or frameworks.

## Features

- Scrapes Google Ads data based on user-provided search term.
- Extracts ad names, prices, addresses, and images.
- Saves scraped data in a CSV file for further analysis.
- Utilizes Selenium for automated web browsing and data extraction.
- Provides a user-friendly command-line interface.
- 
## Prerequisites

To run the project, make sure you have the following installed:

- Python (version 3.7 or above)
- Selenium library (`pip install selenium`)
- ChromeDriver (compatible with your Chrome browser version)

##Download and configure the ChromeDriver:

- Visit the official ChromeDriver downloads page: [https://sites.google.com/a/chromium.org/chromedriver/downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)
- Download the appropriate version of ChromeDriver for your Chrome browser version.
- Place the downloaded ChromeDriver executable in the project directory.

## Usage

1. Run the script:

python scrape_ads.py

2. Enter the search term when prompted.

3. The script will launch a Chrome browser window, perform the search, and scrape the Google Ads data.

4. The scraped data will be saved in a CSV file named `<search_term>_<timestamp>.csv` in the project directory.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.


## Acknowledgements

- This project utilizes the Selenium library for web scraping.
- Special thanks to the contributors and maintainers of the ChromeDriver project.


