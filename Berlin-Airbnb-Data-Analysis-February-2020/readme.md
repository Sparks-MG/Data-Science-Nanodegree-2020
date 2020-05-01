# Berlin Airbnb Data Analysis February 2020

## Udacity Nanodegree Data Science Project: Write a Data Science Blog Post


### Motivation
This project is part of Udacity's Nanodegree in Data Science and will be implemented via the programming language Python following the CRISP-DM methodology. The results are published in an accompanying blog on medium: https://medium.com/@martin.gleditzsch/berlin-or-berlout-1eee1e8ffb43?sk=cc2e9e8ba090abc3c0ce52dc97acacb0.

For this project, I was  interestested in Airbnb data for Berlin which was scrapped in February 2020 to **answer the following questions:**
* How expensive is an overnight stay in Berlin? What are minimum, average, typical or maximum prices?
* How does the cost vary depending on the month or day?
* How does the cost vary depending on the neighbourhood in the city?
* Is there a correlation between price of a listing and user rating?

### Dataset
The dataset was originally collected by **Murray Cox' Inside Airbnb project**  by compiling publically aviable data fo **Berlin, Germany at  18. February 2020**: http://insideairbnb.com/get-the-data.html .
The data is avaible under a Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.

The CSV files come in **two variants**, a **detailed variant** (compressed in an gz archive with more columns) and a smaller less-detailed variant. We will focuse on the detailed variant, thus only that data is provided here. To run the main file, you need to unpack the archives first.

### Necessary Python Libraries 
* Data Wrangling and Analysis: **pandas, NumPy**
* Data Visualisation: **Matplotlib, seaborn**

### Included Files
All files necessary for analysis and visualisation are included in the Github respository and are as followed:
* **Airbnb_BerlinAnalysis.ipynb**: notebook containing the code and representation.
* **calendar.csv.gz**: a compressed CSV file containing **detailed** information on availability, date and prices of all Airbnb listings in Berlin between 18. February 2020 and 17. February 2021.
* **listings.csv.gz**: a compressed CSV file containing even more **detailed** information on the listings.

### Summary of the results

* The average (mean) overnight stay price per night is 80 \\$.  This value is, however, heavily influenced by the more expensive listings. 
* The median overnight stay price is 50 \\$, which is realistic from my experience.
* That price is influenced by the week day (Friday and Saturday are more expensive) and the month (January is the most expensive, March the cheapest month).
* The neighbourhood has a big impact on the price. However, the value seems to have no clear function of the distance to the city center.
* None of the review score metrics have any impact on the price, which is quite a surprise. So overall, the quality of the listings is comparable for different price ranges.


### Aknowledgement
* Murray Cox' Inside Airbnb project for collecting and hosting the AirBnB Data: https://insideairbnb.com/.
* A multitude of Stackoverflow users whose questions and answers I found, when I was stuck on a pandas related coding problem.
