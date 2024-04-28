# EmpiricalProject-720005462
In this repository you will find the code and data necessary to replicate my project on the demographic changes in Premier League football.

All data was scraped from the Offical Premier League website which can be accessed at this link:
https://www.premierleague.com/home

The project directory has three ipynb files which were generated in Jupyter notebooks.

The first notebook to use is called WebScrape. This code will web scrape the Premier League website for the determined variables.
Due to a wifi disconnect I also wrote code which will populate the csv from a determined line of the table, to prevent having to run all the code from the beginning.
Please note that you may have to change some of the code regarding closing ads, as these frequently change on the website.

The notebooks LeagueTableAnalysis and PlayerDataAnalysis run code to process, analyse and visualise the data.

There were some missing rows of data which were due to a lack of information on the Premier League website. I removed rows which were missing key data such as nationality and club but kept rows which were only missing height.

The folders Graphs, LeagueData and PlayerData have been included for clear directory structure but are not necessary.
