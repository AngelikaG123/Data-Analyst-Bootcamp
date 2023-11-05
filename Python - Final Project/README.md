# NoFluffJobs Web Scraping and Data Analysis Project

This repository contains a Python project that serves as a culmination of the skills and knowledge gained during a Python module in a bootcamp. The project focuses on web scraping, data manipulation with pandas, data visualization with Matplotlib, and web automation with Beautiful Soup and Selenium.

## Overview

The main goal of this project is to scrape job listings from [NoFluffJobs](https://nofluffjobs.com) and perform in-depth data analysis on job offers related to three distinct roles: 'Data Analyst', 'Data Scientist', and 'Data Engineer'. The project is organized into three primary folders: `data`, `drivers`, and `notebooks`.

## Folders

### Data
The `data` folder is further divided into three subfolders:

- **Raw**: This folder stores the raw HTML files downloaded from NoFluffJobs, representing the initial state of the job listings.
- **Interim**: The 'Interim' folder contains partially modified HTML files after processing with Beautiful Soup and Selenium.
- **Processed**: In the 'Processed' folder, you'll find CSV files that contain structured data in the form of Pandas DataFrames, making it suitable for in-depth analysis. Additionally, this folder includes the results of Matplotlib-based visualizations for a more comprehensive understanding of the job market.

### Drivers
The `drivers` folder holds the Chromedriver executable necessary for Selenium to interact with web pages and scrape data.

### Notebooks
The `notebooks` folder contains four key Jupyter Notebook files:

- **01-NoFluffDownloader.ipynb**: This notebook focuses on downloading the HTML files from NoFluffJobs and saving them in the 'Raw' folder.
- **02-JobOfferScrapper.ipynb**: In this notebook, the HTML files are converted into structured DataFrames, making them more amenable to analysis.
- **03-DataProcessing.ipynb**: This notebook tackles the process of modifying the data to enhance its accuracy and usefulness for in-depth analysis.
- **04-DataAnalysis.ipynb**: This is where the real analysis happens. It contains the exploration and visualization of the job market data for the 'Data Analyst', 'Data Scientist', and 'Data Engineer' roles.

## Usage

The project provides a comprehensive hands-on example of how to use Python for web scraping, data manipulation, and data analysis in the context of job listings. Each Jupyter Notebook serves as a step in the pipeline, showcasing the application of different Python libraries and techniques.

## Acknowledgements

This project was developed by Angelika Gruda as part of the Python module at Data Analyst Bootcamp. It's a testament to the practical skills and knowledge acquired during the course.
