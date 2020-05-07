# Udacity Project
Writing a blog post with Sydney AirBNB data

### Installations

This project was written in the Anaconda environment and Python 3

### Motivation

The purpose of this project was to explore the Sydney AirBNB data as part of Udacity's Data Science Nanodegree program. The project considers the following 3 questions:
- What are the busiest times of the year to visit Sydney? By how much do prices spike?
- Is there a general upward trend of both new Airbnb listings and total Airbnb visitors to Sydney?
- Can you describe the vibe of each Sydney neighborhood using listing descriptions?

### Files

This repository contains the following files:
- Udacity - AirBNB data blog post.ipynb
  - Jupyter notebook exploring and analysing the Sydney AirBNB data
  
### Data
  
The data used in this project (860MB unzipped) is available from:
- listings.csv (Detailed Listings data for Sydney)
  - http://data.insideairbnb.com/australia/nsw/sydney/2019-07-10/data/listings.csv.gz
- calendar.csv (Detailed Calendar Data for listings in Sydney)
  - http://data.insideairbnb.com/australia/nsw/sydney/2019-07-10/data/calendar.csv.gz
- reviews.csv (Detailed Review Data for listings in Sydney)
  - http://data.insideairbnb.com/australia/nsw/sydney/2019-07-10/data/reviews.csv.gz

### Summary

1) We found that the busiest times to visit Sydney are December-January, particularly during Christmas/New Year. Prices spiked by around 40% during this peak period.
2) A general upward trend was seen in the number of AirBNB listings, though the rate at which new hosts have been joining the platform has slowed since 2016. We also saw an upward trend in the number of AirBNB visitors to Sydney, as indicated by the volume of reviews left on the platform.
3) With the help of scikit-learn and TfidfVectorizer, we were also able to describe the vibe of various Sydney neighbourhoods using the listing descriptions.

### Acknowledgements

With thanks to:

Udacity - for setting up the project and course contents.

Inside Airbnb - for providing the data. For more information, visit: http://insideairbnb.com/get-the-data.html

