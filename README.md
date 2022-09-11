# skill-ed
Data is scraped from LinkedIn and is used for analyzing various skills required for different job roles 

# 1. Data Scraping\n
  Selenium module of python is used for automating the LinkedIn page and job description is extracted for various job roles. It is then exported into json file to         avoid any data loss. 'scraper.py' is the python code used for scraping.
  
# 2. Data Cleaning and extraction
  The scraped data is cleaned and required skills are extracted using regular expressions. A number of technical and soft skills are feeded initially for extracting       count. The python code used for this is 'count.py'. Count of each skill is then exported into an excel sheet using python pandas
  
# 3. Visualization
  Obtained data is then visualized as charts using streamlit and plotly. 'skill_visualization.py' is the python code written for this implementation. 
