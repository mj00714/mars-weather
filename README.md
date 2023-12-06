# mars-weather

### Overview
The assignment is broken into two parts: 1) Scraping Titles and Preview Text (`mars_news.ipynb`) and 2) Scraping and Analyzing Mars Weather Data (`mars_weather.ipynb`). 

Starter files and the data output are stored in their own folders within the repository with the main files located in the main directory, mars-weather. 

### Mars News
- Splinter's automated browsing functionality was used to scrape text from the Mars News website. 
- After extraction, the Titles and Previews were organized and stored in a Python list of dictionaries. 

### Mars Weather
- The same basic process from part one was used to capture scrape data, but this time a table is our target. 
- The table data was then migrated to (our old friend) a Pandas DataFrame. In the future, I'd definitely use the Pandas `read_html` function to save time and simplify the code. 
- Some basic analysis was performed on the DataFrame and a few graphics were generated: Temperature by Months, Atmospheric Pressure and a visualization of the Martian Year. 
- A csv file was generated from the data and saved in the `data_output` folder
