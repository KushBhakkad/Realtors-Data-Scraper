# Realtors-Data-Scraper

## Project Overview
This project automates the scraping of realtor information from Realtor.ca as a freelance project. The script extracts details such as realtor names, company names, contact numbers, addresses, and website links, navigating through multiple pages efficiently.

## Features
- **Realtor Information Extraction:** Scrapes realtor details like names, companies, phone numbers, addresses, and websites.
- **Pagination Handling:** Dynamically navigates through multiple pages of results.
- **Real-Time Logging:** Logs progress and errors to a file for monitoring.
- **Scalable Design:** Can handle large datasets efficiently.

## Technologies Used
- **Programming Language:** Python
- **Tools and Libraries:**
  - Selenium for browser automation
  - ChromeDriver for controlling Chrome browser
  - `webdriver_manager` for managing ChromeDriver
  - Python libraries such as `time` and `logging` for delays and progress tracking

## Installation
### Prerequisites
- Python 3.8 or higher
- Chrome browser installed
- ChromeDriver installed (or managed via `webdriver_manager`)

## Usage
1. Run the script:
   ```bash
   python realtors_scraper.ipynb
   ```
2. Follow these steps during execution:
   - Monitor the logs for progress and errors.
   - View the extracted data printed to the console.

## Key Files
- `realtors_scraper.ipynb`: Main script for scraping realtor data.
- `scraper.log`: Log file containing detailed activities and errors.

## Example Output

![Output](https://github.com/user-attachments/assets/0816db23-2e53-48af-903a-9bf2faf19ad9)

## Future Enhancements
- **Data Export:** Save the results to a CSV or database.
- **Error Handling:** Enhance handling of network errors and missing fields.
- **Headless Mode:** Add headless browser support for faster and undetected scraping.
