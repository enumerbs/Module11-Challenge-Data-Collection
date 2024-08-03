# Module11-Challenge-Data-Collection

Data Analytics Boot Camp - Module 11 - Data Collection \
Data Collection Challenge

---

# Results

The *Part1_MarsNews* subfolder contains the following files:

- **part_1_mars_news.ipynb** (Python code and data scraping results)<br>
- **mars_news_articles.json** (data scraping results saved in JSON format)

The *Part2_MarsWeather* subfolder contains the following files:
- **part_2_mars_weather.ipynb** (Python code, data scraping results, and data analysis results)
- **mars_weather_data.csv** (data scraping results, augmented and saved in CSV format)


# Implementation notes

**part_1_mars_news.ipynb** (optional final step)
 - Saved the results in JSON format to a file, by using json.dump() from the Python json module.

 **part_2_mars_weather.ipynb** (final step)
 - Augumented the data scraping results with a calculated column giving the number of terrestrial days since the earliest date of observation.
 - Saved the augmented results in CSV format to a file, by using the Pandas DataFrame to_csv() method.

# References

The following references were used in the development of the solution for this Challenge.

## Automated web scraping
- Class notes/sample files for 'Data Collection', Monash University 'Data Analytics Boot Camp'

## Matplotlib
- Sorting bar chart bars in increasing order https://www.tutorialspoint.com/how-to-sort-bars-in-increasing-order-in-a-bar-chart-in-matplotlib

## Pandas - DataFrame
- astype() type conversion https://www.w3schools.com/python/pandas/ref_df_astype.asp
- to_datetime() type conversion https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html

## Python JSON module
- Saving JSON to a file https://sentry.io/answers/write-json-data-to-a-file-in-python/
