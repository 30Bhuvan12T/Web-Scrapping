# Flipkart Mobile Data Web Scraping 📱

## Project Overview

This project extracts mobile phone data from Flipkart using Python web scraping techniques. The data includes product name, price, description, and reviews.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook

## Features

* Scrapes multiple pages automatically
* Extracts:

  * Product Name
  * Price
  * Description
  * Reviews
* Stores data in structured format (DataFrame)

## Libraries Used

```python
import pandas as pd
import requests
from bs4 import BeautifulSoup
```

## How it Works

1. Sends request to Flipkart website
2. Parses HTML using BeautifulSoup
3. Extracts required product information
4. Stores data into Pandas DataFrame

## Output

Structured dataset of mobile phones under ₹50,000.

## Learning Outcomes

* Web scraping fundamentals
* HTML parsing
* Data extraction
* Data handling using Pandas

## Author

Bhuvan T
Aspiring Data Analyst
