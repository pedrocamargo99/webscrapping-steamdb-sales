 **Webscrapping SteamDB Sales** 🤖

This repository consists of a Webscrapping project using Python, that extracts every game deal from the website https://steamdb.info/sales/ and loads into a Google BigQuery Table.

### 🎯 Libraries Used:

- from pandas_gbq import to_gbq
- from google.oauth2 import service_account
- from bs4 import BeautifulSoup
- from selenium import webdriver
- from selenium.webdriver.common.by import By
- from selenium.webdriver.support import expected_conditions as EC
- from selenium.webdriver.support.ui import WebDriverWait
- from selenium.webdriver.common.keys import Keys
- from selenium.webdriver.common.action_chains import ActionChains
- import pandas as pd
- import logging
- from dotenv import load_dotenv
- import os

### ✅ Results Found:
Criation of a code that navegates every page of the website and extracts every information about a Steam Deal and loads the results to a GBQ Table based of the credentials given by the .env.

### ⚠️ Note

The .env_sample file in the repository is and example of what type of credential you need in Google big Query to load the data.

