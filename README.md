# HTML-Webscraping-challenge

## Overview
In this challenge, the objective is to apply and consolidate the skills acquired in web scraping and data analysis. The focus lies on identifying HTML elements using attributes such as id and class, utilizing both automated browsing with Splinter and HTML parsing with Beautiful Soup. The challenge involves extracting diverse types of information from web pages, including data from HTML tables and recurring elements like multiple news articles. The project encompasses the entire data pipeline, from collecting information on web pages to organizing and storing the data, followed by thorough analysis.

## Purpose
The ultimate goal is to visually communicate insights derived from the scraped and analyzed data, emphasizing the practical application of core skills in data collection and analysis within a real-world context.
The core skills used for this project are: collecting data, organizing and storing data, analyzing data, and then visually communicating the insights.

![image](https://github.com/Ani2587/HTML-Webscraping-challenge/assets/17106097/d10dfa8a-619f-4a90-a438-2ce952410d34)


## Instructions
Follow the steps below to successfully run the code:
1. Clone the repository to your local machine.
2. My system is not recognizing the path of the chromedriver, causing the line "browser = Browser('chrome')" to fail in
   launching the Chrome browser. To address this issue, I have implemented the following workaround.
   This solution is expected to function seamlessly across all systems; however, if any issues arise, kindly consider commenting out these two lines of code
   
   executable_path = {'executable_path': ChromeDriverManager().install()}
   browser = Browser('chrome', **executable_path, headless=False)
   
   and uncommenting the line "browser = Browser('chrome')" in the code in both files part_1_mars_news.ipynb, part_2_mars_weather.ipynb.
   
4. The code will generate a "data" folder to store the output CSV file (scraped_data.csv).
   

