
Oldest Living Baseball Players - Web Scraping & Data Dashboard

This project scrapes, processes, and visualizes data about the oldest living Major League Baseball (MLB) players. It demonstrates the use of Python for web scraping, data cleaning, SQL database management, and interactive dashboard development using Streamlit.

Deployed site link:

https://python-web-scraping-project.onrender.com/


Features:

Web scraping from Baseball Almanac using Selenium and BeautifulSoup

Data cleaning and transformation with pandas

SQLite database creation and querying

Interactive data dashboard with filters and charts using Streamlit

Visualizations include:

Age distribution

Players by team

Longest career span



How to Run
Install dependencies:

pip install -r requirements.txt

Run the scraper:

python scraper.py

Clean the data:

python clean_oldest_players.py

Import into SQLite:

python import_to_db.py

Launch the Streamlit dashboard:

streamlit run dashboard.py


Technologies Used:

Python
Selenium, BeautifulSoup
pandas, numpy
SQLite, sqlalchemy
matplotlib, seaborn
Streamlit

