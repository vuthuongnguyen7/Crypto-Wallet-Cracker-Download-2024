# Premier League Scores and Fixtures

This script scrapes the Premier League scores and fixtures from fbref.com and saves them in a CSV file named "fixture_results.csv". The CSV file contains the following columns:
- Round
- Date
- Team 1
- FT (Full Time)
- Team 2

The same code with a few tweaks can also scrape other Leagues from fbref.com
## Requirements
- Python 3.x
- requests
- csv
- datetime
- BeautifulSoup

## Installation
1. Clone this repository.
2. Install the required packages using pip:
pip install -r requirements.txt

3. Run the script:
python fbref_scraping.py


## Usage
The script will create a CSV file named "fixture_results.csv" in the same directory as the script.
