# Web Scraping Project: Cricket Statistics

## Overview
This project demonstrates web scraping techniques using Python to extract cricket statistics from various sports websites. The extracted data is processed and analyzed using Pandas for further insights.

## Data Sources
- **Cricbuzz**: Scraping highest runs data for the ICC Cricket World Cup 2023.
  
  ![cricbuzz_Stats](https://github.com/Dhruvbansal106/Web-Scraping-Project-Using-Python/blob/main/cricbuzz.png)

- **ESPN Cricinfo**: Scraping most wickets data for the ICC Cricket World Cup 2023.
  
 ![Espn Stats](https://github.com/Dhruvbansal106/Web-Scraping-Project-Using-Python/blob/main/espn%20Cricinfo%20.png)


## Technologies Used
- **Python**
- **BeautifulSoup** (for HTML parsing)
- **Requests** (for making HTTP requests)
- **Pandas** (for data manipulation and analysis)
- **Jupyter Notebook** (for interactive coding and visualization)

## Installation
Before running the project, install BeautifulSoup:
```bash
pip install beautifulsoup4
```

## Importing Libraries
Ensure the following libraries are imported at the beginning of your Jupyter Notebook:
```python
from bs4 import BeautifulSoup  # For parsing HTML content
import requests  # For making HTTP requests
import pandas as pd  # For data manipulation and analysis
```

## Project Structure
```
📂 WebScrapingProject
│-- 📜 HighestRuns.ipynb    # Jupyter Notebook for scraping highest runs
│-- 📜 MostWickets.ipynb    # Jupyter Notebook for scraping most wickets
│-- 📜 data/                # Folder containing generated CSV files
│   │-- highest_runs.csv    # CSV file with highest runs data
│   │-- most_wickets.csv    # CSV file with most wickets data
│-- 📜 README.md            # Project documentation
```

## How to Run
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open **HighestRuns.ipynb** or **MostWickets.ipynb** and run the cells step by step.
3. The extracted data will be saved as CSV files in the `data/` folder.

## Key Features
- Extracts real-time cricket statistics from popular sports websites.
- Uses BeautifulSoup for parsing HTML content.
- Stores and processes data using Pandas.
- Saves scraped data in CSV format for further analysis.
- Demonstrates web scraping best practices, including handling HTTP requests and headers.

## Legal Disclaimer
Web scraping may be subject to legal restrictions based on the website's terms of service. Ensure you review and comply with the policies of the websites being scraped.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

---
Happy Coding! 🚀

