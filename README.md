# Premier League Scores and Fixtures

This script scrapes the Premier League scores and fixtures from fbref.com and saves them in a CSV file named "fixture_results.csv".However, it
is not suitable for leagues with play-offs (Knock-Out matches). It can be used for leagues in every country and season available in FBref.
Knockout matches can also be included with slight modifications.

The CSV file contains the following columns:
- Round
- Date
- Team 1
- FT (Full Time)
- Team 2

PS: There is There is lots of room for further optimizations 🚀🚀.
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
python fixture_results.py


## Usage
The script will create a CSV file named "fixture_results.csv" in the same directory as the script.
