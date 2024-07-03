# Stock Data Extraction and Visualization Project:

This project involves extracting and visualizing stock data using Python. The tasks include utilizing the `yfinance` library to extract stock information, historical share price data, and historical dividends data. Additionally, web scraping is employed to extract revenue data for Tesla and GameStop. The extracted data is then visualized in graphs using the `matplotlib` library..

![AI-in-Stock-Market](https://github.com/Ayushmi-Adh/Extracting-Stock-Data-Using-a-Web-Scraping/assets/132826306/6900ddb7-ab50-4aa1-adc6-43a446a9f989)

## TABLE OF CONTENTS:

1. [Introduction](#introduction)
2. [Steps for Extracting Data](#steps-for-extracting-data)
3. [Data Extraction and Visualization](#data-extraction-and-visualization)
4. [Define a Function for Making Graphs](#define-a-function-for-making-graphs)
5. [Questions](#questions)
   - [Question 1: Use yfinance to Extract Stock Data](#question-1-use-yfinance-to-extract-stock-data)
   - [Question 2: Use Webscraping to Extract Tesla Revenue Data](#question-2-use-webscraping-to-extract-tesla-revenue-data)
   - [Question 3: Use yfinance to Extract Stock Data](#question-3-use-yfinance-to-extract-stock-data)
   - [Question 4: Use Webscraping to Extract GME Revenue Data](#question-4-use-webscraping-to-extract-gme-revenue-data)
   - [Question 5: Plot Tesla Stock Graph](#question-5-plot-tesla-stock-graph)
   - [Question 6: Plot GameStop Stock Graph](#question-6-plot-gamestop-stock-graph)
6. [Instructions for Running the Code](#instructions-for-running-the-code)
7. [Screenshots](#screenshots)
8. [Dependencies](#dependencies)


## Introduction:

As a data scientist working for a hedge fund, the task is to extract and analyze stock data using Python. The project involves using the `yfinance` library for stock data extraction and web scraping for revenue data extraction. The extracted data is then visualized through graphs to facilitate better decision-making..

## Steps for Extracting Data:

The following steps are followed for extracting stock data:

1. Send an HTTP request to the web page using the `requests` library.
2. Parse the HTML content of the web page using `BeautifulSoup`.
3. Identify the HTML tags containing the data to extract.
4. Utilize `BeautifulSoup` methods to extract the data.
5. Print the extracted data.

## Data Extraction and Visualization:

The project includes the extraction of essential stock data using `yfinance` and web scraping techniques. The extracted data is then visualized through graphs for better analysis.

## Define a Function for Making Graphs:

A function is defined to facilitate the creation of graphs based on the extracted data..

## Questions

The project addresses the following questions:

- [Question 1: Use yfinance to Extract Stock Data](#question-1-use-yfinance-to-extract-stock-data)
- [Question 2: Use Web scraping to Extract Tesla Revenue Data](#question-2-use-webscraping-to-extract-tesla-revenue-data)
- [Question 3: Use yfinance to Extract Stock Data](#question-3-use-yfinance-to-extract-stock-data)
- [Question 4: Use Webscraping to Extract GME Revenue Data](#question-4-use-webscraping-to-extract-gme-revenue-data)
- [Question 5: Plot Tesla Stock Graph](#question-5-plot-tesla-stock-graph)
- [Question 6: Plot GameStop Stock Graph](#question-6-plot-gamestop-stock-graph)


## Dependencies

- Python 3.x
- `yfinance`
- `pandas`
- `requests`
- `BeautifulSoup`
- `matplotlib`

## Screenshots
<img width="610" alt="Screenshot 2024-02-06 223801" src="https://github.com/Ayushmi-Adh/Extracting-Stock-Data-Using-a-Web-Scraping/assets/132826306/c086e851-0ff7-4af9-8804-1d101244a587">
<img width="593" alt="Screenshot 2024-02-06 223823" src="https://github.com/Ayushmi-Adh/Extracting-Stock-Data-Using-a-Web-Scraping/assets/132826306/4edbba34-f5f0-448f-b660-5b8c6d38c77e">
<img width="573" alt="Screenshot 2024-02-06 223845" src="https://github.com/Ayushmi-Adh/Extracting-Stock-Data-Using-a-Web-Scraping/assets/132826306/f3fe3619-a632-48ac-aa4b-a682b77c44e8">
<img width="566" alt="Screenshot 2024-02-06 223858" src="https://github.com/Ayushmi-Adh/Extracting-Stock-Data-Using-a-Web-Scraping/assets/132826306/12613790-fd7a-488c-a38f-84dce4295deb">

