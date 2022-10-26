# surfs_up

## Overview of Project

An investor asked me to analyze and report weather data to support a business plan for which I am raising funds. Specifically, he wants me to extract and compare the temperature data for the months of June and December over the years for a Hawaiian island, Oahu, to determine if the surf and ice cream shop business is sustainable year-round. In doing so, I will use an SQLite database, including the temperature data, and write queries via Jupyter Notebook to provide summary statistics for these months. Particularly, I will use the Python SQL toolkit and Object Relational Mapper as well as the SQLAlchemy extract function to write queries. Besides, the query results are stored in Pandas data frames to obtain summary statistics. Below I will explain the results of the queries and their analysis.

## Results

Below I added two screenshots of the summary statistics of Oahu's temperature in June and December.

![This is an image](/June.png)  ![This is an image](/December.png) 

According the above resutls:

- The average temperature in Oahu for the months of June is slightly (3 °F) more than December.
- While the maximum historical temperature for June (85 °F) is almost similar to December (83 °F), the minimum historical temperature in December (56 °F) is moderately lower than June (64 °F).
- Overall, the temperature disctirubutions of June and December in Oahu look comparable (roughly 2 °F difference in first, second, and third quartiles).

## Summary: 

In general, the obtained statistics indicate that the temperature range of June and December in Oahu follow almost similar patterns. This finding support the sustainability of the surf and ice cream shop business year-round. Despite these promising results, however, temperature similarity may not be sufficient to make the final investment decision. In fact, there are other influential factors such as precipitation that should also be considered to ensure business sustainability. Given that, I suggest running the following queries to further investigate weather condition in Oahu:

Query 1:



