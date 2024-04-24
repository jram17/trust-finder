# trust-finder
Trust Finder Web Crawler
This Python script serves as a web crawler and web scraper to collect information about trusts in India, organized statewise, from the NGO Darpan website. 
The collected data is stored in an Excel file (trustInfoIndia.xlsx) for easy access and analysis.

Objective:
The objective of this project is to gather comprehensive information about trusts in India, including their names and registration numbers, to facilitate better understanding 
and analysis of the trust landscape in the country.

Implementation:
-The script utilizes the requests library to fetch HTML content from the NGO Darpan website.
-HTML parsing and data extraction are performed using the BeautifulSoup library.
-Regular expressions are employed to extract additional information, such as VO (Voluntary Organization) numbers, from JavaScript onclick attributes.
-Trust information is stored in an Excel spreadsheet (trustInfoIndia.xlsx) using the openpyxl library for easy access and organization.
Functionality:
-Data Collection: The script iterates over each state listed on the NGO Darpan website, collecting trust information from each state page.


Comprehensive Information: 
Trust details such as name and registration number are extracted from the HTML content of each page.

Automation: 
The script automatically navigates through multiple pages of trust listings for each state, ensuring comprehensive data collection.

Scalability: 
It is designed to handle a large volume of trust data and can be easily scaled to accommodate future additions or modifications.

Usage:
Ensure that the necessary Python libraries (requests, BeautifulSoup, and openpyxl) are installed.

Run the Python script scrapeTrust.py.
The collected trust information will be stored in the Excel file trustInfoIndia.xlsx.

Benefits:
-Provides a valuable resource for accessing comprehensive information about trusts in India.
-Facilitates analysis and understanding of the trust landscape in the country.
-Enables users to stay informed and up-to-date on trust-related matters.

Disclaimer:
Please use this script responsibly and in compliance with the terms of use of the NGO Darpan website. The script is intended for educational and research purposes only.

Feel free to customize and enhance the script as needed to suit your specific requirements. Contributions and feedback are welcome!
