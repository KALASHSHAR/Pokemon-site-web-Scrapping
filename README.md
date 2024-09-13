# Web Scraping Using Python (BeautifulSoup)


## Introduction: What is Web Scraping?
Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort. <br>

In this project we are going to use amazon product (ps5) search result link as the source of our raw data [link](https://pokemondb.net/pokedex/all).


## Prerequisites
1. Python 3.6+
2. install BeautifulSoup **```pip install beautifulsoup4```**
3. install Requests **```pip install requests```**
4. install Pandas **```pip install pandas```**
5. the user-agent of your browser. To get the user-agent, just search for "my user agent" on Google and copy the user-agent string.
6. product search url from amazon


## Process of Web Scraping
1. Importing the required libraries
2. Specifying the URL containing the dataset and passing it to **`requests.get()`** to get the HTML content of the page.
3. Using BeautifulSoup to parse the HTML content
4. Extracting the required information from the data
5. Saving the pandas dataframe as a CSV file called **`Pokemon_list.csv`**


## Project Specifications

1. It contains a jupyter notebook file **`pokemon.ipynb`** which contains the final codes to be used in the project.
    * function to Extract Product Title
    * function to Extract Product Price
    * function to Extract Product Rating
    * function to Extract Number of User Reviews
    * function to Extract Product Availability
2. It contains a csv file **`Pokemon_list.csv`** which contains the final data extracted from the website.


## About me
I am Kalash Shar, and currently, I am pursuing B-Tech from GCOEY. 
- [Kalash Shar](https://www.linkedin.com/in/kalashshar/)


## Feedback
