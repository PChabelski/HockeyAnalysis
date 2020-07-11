# HockeyAnalysis
Exercise in web scraping &amp; data manipulation using Python

The notebook pulls data using the BeautifulSoup library (2 tables - Individual stats and Biographical stats) from NaturalStatTrick for Toronto Maple Leafs players from 2007 to the present roster. These tables are merged and stacked to form a single dataframe.

Note: You can load the dataframe directly through the natstattrickleafs.pkl file (I had to add a delay to the scrapper, as pinging NaturalStatTrick too often would cause a soft IP ban..)

A preliminary data cleanse is performed, and eventually some feature engineering and analysis of certain parameters & stats. 

TO UPDATE FOR V2:
- General scrubbing and cleaning of the entire notebook (remove table printouts during scraping, reformat analysis structure, etc)
- Incorporate data from other sites (HockeyReference, Corsica?) including older roster data -> could be an excellent exercise in fuzzy-matching?
