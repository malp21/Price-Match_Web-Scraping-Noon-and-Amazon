# Price Match Code

Scrape product prices from various e-commerce websites using BeautifulSoup and Selenium. This tool is designed to help you perform regular or daily price matches with Amazon and Noon, updating them in an Excel file entitled with "[run_date] Price Match."

## Features

- **Dynamic Scraping:** Selenium is employed for Noon as it deals with dynamically updated content. BeautifulSoup is used for Grazie and Amazon due to their lighter and less time-consuming page structures.

- **Background Operation:** The code is designed to run in the background, allowing you to multitask efficiently while it collects the data you need.

- **Data Management:** Price data is saved to an Excel file named with the current date, making it easy to organize and reference historical price information.

## Usage

1. Clone this repository to your local machine.

2. **Create and Manage Excel File:**
   - To store the scraped product prices, this script creates an Excel file with three columns: 'Grazie Price,' 'Amazon Price,' and 'Noon Price.' You can easily manage this file's name, location, and column titles as per your preferences.
  
   - **File Location:** Save this file in the same directory as your Python script.

   - **File Name:** The file name is set in the script at Line 13, adjust accordingly so it matches.

3. **Install Dependencies:**
   - Run the following command in CMD:
     ```bash
     pip install requests beautifulsoup4 selenium pandas
     ```
     If you encounter an error, use `pip3` instead of `pip`.

4. **Run the Script:**
   - Execute the script, and it will automatically scrape the prices and update the Excel file.

## Configuration

You can easily customize this tool by:

- Adding or removing product URLs in the code to scrape prices for different items under the respective URL_List.

- Modifying the scraping intervals to meet your requirements.

- Adjusting the data storage format or filename as needed.

## Dependencies

- **Beautiful Soup:** A Python library for web scraping purposes.

- **Selenium:** A Python library for automating web browser actions.

- **pandas:** A powerful data manipulation and analysis library.

---
