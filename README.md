# Module 11: Scraping Challenge

-----------------
Table of Contents
-----------------

  - part_1_mars_new.ipynb file which contains the script for scraping titles and previewing text from Mars news articles.

  - part_2_mars_weather.ipynb file which contains the script for scraping and analyzing Mars weather data, which exists in a table.

  - mars_articles.json file which contains the titles and preview text of the news articles in a list of dictionaries in json that was generated in part 1.
    
  - mars_table.csv file which contains the DataFrame from the table scraped in part 2.

   
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-------------------
Challenge Objective
-------------------

The goal of this challenge is to scrape information from and analyze data available online. Part 1 is to scrape titles and preview text from Mars news articles, and Part 2 is to scrape and analyze Mars weather data, which exists in a table.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-----------
References
-----------

https://static.bc-edx.com/data/web/mars_news/index.html

https://static.bc-edx.com/data/web/mars_facts/temperature.html

The following link was used to learn how to write a json file in python: https://www.geeksforgeeks.org/reading-and-writing-json-to-a-file-in-python/

Code referenced:

with open('mars_articles.json', 'w', encoding='utf-8') as f:
    
  json.dump(article_list, f, ensure_ascii=False, indent=4)
    

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
