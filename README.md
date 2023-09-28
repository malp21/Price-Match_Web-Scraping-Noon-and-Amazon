#Price Match Code
Scrape product prices from various e-commerce websites using BeautifulSoup and Selenium . 
This tool is designed to help you complete regular or daily price matches with Amazon and Noon and updates them in an Excel file entitiled with "[run_date] Price Match]

Features
Dynamic Scraping: Selenium is employed for Noon as it deals with dynamically updated content. BeautifulSoup is used for Grazie and Amazon due to their lighter and less time-consuming page structures.

Background Operation: The code is designed to run in the background, allowing you to multitask efficiently while it collects the data you need.

Data Management: Price data is saved to an Excel file named with the current date, making it easy to organize and reference historical price information.

Usage
Clone this repository to your local machine.

Install the required Python packages using the following command:
Copy code into CMD:
    pip install requests
    pip install beautifulsoup4
    pip install selenium
    pip install pandas
--> if error: 'pip' is not recognized as an internal or external command,
operable program or batch file.
    use pip3 instead of pip
    e.g. pip install requests
--> check if pip is installed:
    pip --version
--> to install pip if it is not automatically present (my pip file got corrupted during this so I had to re-install pip):
    py -m ensurepip

Run the script, and it will automatically scrape the prices and update the Excel file.

Configuration
You can easily customize this tool by:

Adding or removing product URLs in the code to scrape prices for different items under the respective URL_List.

Modifying the scraping intervals to meet your requirements.

Adjusting the data storage format or filename as needed.

Dependencies
Beautiful Soup: A Python library for web scraping purposes.

Selenium: A Python library for automating web browser actions.

pandas: A powerful data manipulation and analysis library.
