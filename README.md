# Web-Scraping-Using-Python
This repository contains a Python project focused on extracting, processing, and visualizing financial data, specifically stock prices and company revenue. It demonstrates practical skills in web scraping, data manipulation, and interactive data visualization, crucial for any aspiring data analyst.

## Project Overview
The primary goal of this project is to collect financial data from different sources (Yahoo Finance and a web page), combine it, and then present it through interactive visualizations. This allows for a comprehensive view of a company's financial performance over time, enabling better insights into its historical trends.

## Key Features
* Automated Stock Data Extraction: Efficiently retrieves historical stock data using a dedicated financial library.
* Web-Based Revenue Data Collection: Utilizes web scraping techniques to extract revenue information directly from a specified URL.
* Data Integration: Combines disparate datasets (stock prices and revenue) into a unified structure for analysis.
* Interactive Visualizations: Generates dynamic and interactive plots, allowing users to explore trends and patterns in financial data.

## Technologies Used
This project leverages the following Python libraries:
* yfinance: A powerful and convenient library for downloading historical market data from Yahoo Finance
* requests: Used to send HTTP requests to web pages, enabling the retrieval of HTML content for scraping.
* BeautifulSoup: A library for parsing HTML and XML documents, making it easy to extract specific data from web pages.
* pandas: An essential library for data manipulation and analysis, providing data structures like DataFrames to efficiently handle and process the extracted information.
* plotly.graph_objects: A module from the Plotly library used for creating highly customizable and interactive statistical graphics.
* make_subplots (from plotly.subplots): Enables the creation of subplots within a single figure, ideal for displaying multiple related financial metrics simultaneously.

## Project Steps
The project workflow is structured into the following key steps:

### Step 1: Extract Stock Data from Yahoo Finance
This step involves using the yfinance library to programmatically fetch historical stock data for a specified ticker symbol. This data typically includes opening price, closing price, high, low, and volume over a defined period.

### Step 2: Extract Revenue Data from a Website
Here, requests is used to get the HTML content of a financial website. BeautifulSoup then parses this HTML, allowing for the identification and extraction of specific elements containing revenue data. Finally, pandas is employed to structure this extracted data into a clean and usable DataFrame.

### Step 3: Build Interactive Plots
The final step focuses on data visualization. Using plotly.graph_objects and make_subplots, the extracted and cleaned stock and revenue data are combined to create interactive charts. These plots can display trends over time, allowing users to zoom, pan, and hover for detailed information, providing a dynamic and insightful view of the financial performance.
