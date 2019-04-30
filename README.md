# CSE 482 Big Data Analysis: Final Project
### An Analysis of PGA TOUR Statistics

This repository contains all files for my CSE 482 final project.
The goal of the project was to find associations between different statistics on the PGA TOUR. This was done in the following way:
- Scrape data from the PGA TOUR's website
- Clean and preprocess the scraped data
- Discretize the data so it can be consumed by the Apriori algorithm
-- This is done by splitting different statistics by quantiles
- Run the Apriori algorithm to determine which attributes have the highest support and confidence

The files in the directory are as follows:
- final_report_rozwado7.pdf: My final report
- golf_data_analysis.ipynb: All code that was used for the project (scraping, cleaning, discretizing, running Apriori)
- All other files have either been produced or are used by the Jupyter Notebook
- misc.: oOther files that are not important to the project, but may have still been used

Completed in 2019 by Tyler Rozwadowski
