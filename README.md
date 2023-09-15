# beautifulsoup-challenge  
<font size="3">**Module 11 Challenge**  
**Contributors:** Cassia Yoon  
**Github link:** https://github.com/CassiaY/beautifulsoup-challenge</font>

## Project Background  
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements ona page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.  
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developinguntil now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.  
Assignment prompt is found in [Module 11 Challenge.pdf](/Module%2011%20Challenge.pdf).

## Deliverables
1. Scrape titles and preview text from Mars news articles:  see file [part_1_mars_news.ipynb](/code/part_1_mars_news.ipynb)
2. Scrape and analyze Mars weather data, which exists in a table: see file [part_2_mars_weather.ipynb](/code/part_2_mars_weather.ipynb)
3. Data frame csv file: see file [Mars_weather.csv](/output/Mars_weather.csv).

## Analysis
<font size="3">**Analyze your dataset by using Pandas functions to answer the following questions:**</font>

1. How many months exist on Mars?  
    *There are 12 months on Mars.*
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?  
    *There are 1977 Martian days' worth of data*
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.  

    *The coldest and warmest months on Mars are 3 and 8 respectively. See [avg_temp_by_mo_sorted](/output/avg_temp_by_mo_sorted.png).*

4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.  

    *The months with the lowest and highest atmospheric pressures are 6 and 9 respectively. See [avg_Pa_by_mo_sorted](/output/avg_Pa_by_mo_sorted.png).*  

5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.  

    *The estimated distance between peaks is around 690 days (1500-810 days). A year on Mars appears to be about 690 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days. See [edays_myear.png](/output/edays_myear.png)*

## Resources
- how to check datatype of dataframe columns: https://www.statology.org/pandas-check-dtype-all-columns/
- how to sort bar chart: https://stackoverflow.com/questions/70306401/how-do-i-order-my-x-axis-on-pandas-bar-plot
- pandas number of days: https://stackoverflow.com/questions/65048547/how-to-get-number-of-days-between-two-dates-using-pandas
- How many Earth days is a Mars year? https://mars.nasa.gov/resources/21392/mars-in-a-minute-how-long-is-a-year-on-mars/#:~:text=The%20Earth%20zips%20around%20the,year%20means%20longer%20seasons%20too.


# Acknowledgements
I wish to thank our teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
