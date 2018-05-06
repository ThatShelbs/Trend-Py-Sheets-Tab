# Trend-Py-Sheets-Tab
Google Trends + Python + Google Sheets API + Tableau Public = Full Automation

Highlights the process I used to use Python to pull Google Trends data & webscrape 
then push the data to my Google Sheets account so Tableau Public will auto-refresh daily. 
To complete full automation convert .ipynb to .py and schedule routine kickoff using Windows Scheduler or Cron.

End product: https://public.tableau.com/views/TheButterflyKneeffect/TheButterflyKneeffect?:showVizHome=no&:embed=y&:toolbar=n#5

Disclaimer: Right now I am more of a data visualization guy so I am just functional with Python. 

## Step 1: Python Packages & Docs
Install needed Python packages and use documentation in links provided:
··* import pandas as pd
··* import requests
··* import itertools
··* from random import randint
··* import pygsheets
[pygsheets GitHub](https://github.com/nithinmurali/pygsheets)

··* from bs4 import Beautiful Soup
[Beautiful Soup Doc](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

··* from pytrends.request import TrendReq
[pytrends pseduo api](https://github.com/GeneralMills/pytrends)

## Step 2: Authentication for API
Set up authentication with google
[Authentication](https://pygsheets.readthedocs.io/en/latest/authorizing.html)

## Step 3: Tableau
Set up [Tableau Public](https://public.tableau.com/s/) or Tableau Desktop

Note: College Students can get Tableau Desktop for free
[Tableau for Students](https://www.tableau.com/academic/students)

## Step 4: Jupyter Notebook
Use my Jupyter Notebook Trends project "Trend-Py-Sheets-Tab.ipynb" tweaking for your use case

## Step 5: Build Dashboard
Connect Tableau to Google Sheets and build dashboard

## Step 6: Publish to Tableau Public
Publish to Tableau public - When publishing it will let you check a box for routine refreshing off Google Sheets
Note: As of 5/5/18 Google Sheets is the only way to have automated refreshing on Tableu Public

## Step 7: Complete Automation with Scheduler
Save code as a .py and schedule on windows task scheduler or Cron.
[Scheduler Example](https://www.e-education.psu.edu/geog485/node/143)
