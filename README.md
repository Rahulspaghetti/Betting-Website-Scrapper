# Betting Website Scraper

This is a Python script to grab data for betting odds from the site https://bet365.com/ using Selenium.

This project was done to improve my proficiency in Selenium and to provide an insight on how betting and its information can be used is upto the user's discretion.


The script uses geckodriver for Selenium. The path it expects to find it is 'C:\Program Files\geckodriver\geckodriver.exe'.

Run the SeleniumScraper.py file with three parameters (each exactly as they appear on the site):
1) The sport (e.g. "Basketball")
2) The market (e.g. "NBA Futures 2018/19")
3) The particular bet (e.g. "Regular Season MVP")

So for example,
``` python SeleniumScraper.py "Basketball" "NBA Futures 2018/19" "Regular Season MVP" ```
