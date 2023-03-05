# web-scrape-learning
The purpose of this repository is to record the practice of web scraping. as a beginner, I tried the selenium and python to extract price of computer from the website.
from selenium import webdriver
from selenium.webdriver.common.by import By
from bs4 import BeautifulSoup
import time
import pandas as pd
from selenium.webdriver.chrome.service import Service
