# Rental Property Data Extraction

## Introduction
This project is a web scraper designed to collect valuable information from rental property listings on an apartment or real estate portal, such as location, rent, bedrooms, bathrooms, amenities, availability date, and property URL.

The primary motivation behind this project is to gather data from rental property listings for various data science and analytics purposes, such as determining average rent for different neighborhoods, discovering trends in available properties, and predicting future rental prices. This data can be useful for potential tenants, property investors, real estate agents, and policymakers to make informed decisions related to the rental market.

## Methodology
1. **URL Generation and Navigation**: Utilized Selenium to select the desired location from the dropdown menu, and navigate to the corresponding rental listing page.
2. **Extracting Property Details**: Extracted relevant information such as location, rent, number of bedrooms, number of bathrooms, amenities, available date, and URL for each property using Beautiful Soup.
3. **Data Storage and Format**: Converted the records list into a Pandas DataFrame and exported it to a CSV file for data manipulation and analysis.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies (Python, Selenium, Beautiful Soup, pandas, Chrome WebDriver).
3. Configure the desired location in the code.
4. Run the script, and it will scrape the rental property listings from the specified location.
5. The scraped data will be stored in a CSV file for further analysis and processing.

#### Disclaimer

Please note that this project is for educational and demonstrative purposes only. Web scraping should be done responsibly, following the website's terms of service. The author is not affiliated with the real estate portal and is not liable for any consequences resulting from using this script.
