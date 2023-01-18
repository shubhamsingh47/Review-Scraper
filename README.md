# Review-Scraper
This is a Python script for scraping reviews from flipkart. It uses the requests and beautifulsoup4 libraries to send HTTP requests to a website and parse the HTML response.

## Usage
* Install the required libraries by running pip install -r requirements.txt
* Modify the url variable in the script to the desired website you want to scrape reviews from.
* Run the script with python review_scraper.py

## Output
The script will output the reviews it has scraped in a CSV file named reviews.csv in the same directory. The CSV file will have the following columns:

review_text: the text of the review
review_date: the date the review was posted (if available)
review_rating: the rating of the review (if available)

# Note
This script is for educational purposes only and should not be used to scrape data without the website owner's permission. It is important to follow the website's terms of service and any applicable laws when scraping data.
