# Movie Transcript Web Scraper

This Python script scrapes movie transcripts from `https://subslikescript.com/`. It uses BeautifulSoup to parse HTML and extract data from web pages.

## Installation

This script requires the following packages to be installed:
- `BeautifulSoup4`
- `requests`

You can install them using pip:

```
pip install beautifulsoup4
pip install requests
```

## Usage

You can run this script using any Python IDE or using the terminal. To run the script, simply execute the following command in your terminal:

```
python script_name.py
```

The script will start scraping movie transcripts and will save each transcript as a separate text file in the same directory as the script. If any link fails to load, the script will skip it and continue scraping other links. 

Note: The script is currently set to scrape only the first 2 pages of movie transcripts. You can change this by modifying the `[:2]` slice on line 14. 

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.
