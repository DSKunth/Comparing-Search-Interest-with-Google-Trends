# Complex-Analysis

## Comparing Search Interest with Google Trends
### 1. Browser Wars
In this notebook, we'll analyze the worldwide popularity of browsers over time using Google Trends. Although this won't give us direct market share figures, we can use Google Trends to get a sense of interest of a given browser over time and how that interest compares to other browsers. In particular, we will be looking at five major players over the past two decades: Mozilla Firefox (2002-), Apple's Safari (2002-), Google Chrome (2008-), Microsoft Internet Explorer (1995-2020), and Opera (1995-).

The dataset you will use was downloaded as a CSV from this [Google Trends query](https://trends.google.com/trends/explore?date=all&q=%2Fm%2F01dyhm,%2Fm%2F0168s_,%2Fm%2F04j7cyf,%2Fm%2F03xw0,%2Fm%2F01z7gs) in mid-October of 2020. Here are the details:

datasets/worldwide_browser_trends.csv

This is a time series indexed by month with the search interest for each browser.
- Month: each month from 2004-01 to 2020-10
- Firefox: search interest for Firefox
- Safari: search interest for Safari
- Google Chrome: search interest for Chrome
- Internet Explorer: search interest for Internet Explorer
- Opera: search interest for Opera

Google defines the values of search interest as: Numbers represent search interest relative to the highest point on the chart for the given region and time. A value of 100 is the peak popularity for the term. A value of 50 means that the term is half as popular. A score of 0 means there was not enough data for this term.

### 2. Kardashian & Jenner Sisters
The sisters in particular over the past decade have been especially productive in this regard. Let's get some facts straight. I consider the "sisters" to be the following daughters of Kris Jenner. Three from her first marriage to lawyer Robert Kardashian:

- Kourtney Kardashian (daughter of Robert Kardashian, born in 1979)
- Kim Kardashian (daughter of Robert Kardashian, born in 1980)
- Khloé Kardashian (daughter of Robert Kardashian, born in 1984)

And two from her second marriage to Olympic gold medal-winning decathlete, Caitlyn Jenner (formerly Bruce):

- Kendall Jenner (daughter of Caitlyn Jenner, born in 1995)
- Kylie Jenner (daughter of Caitlyn Jenner, born in 1997)

![image](https://user-images.githubusercontent.com/98457852/187044057-a8ec5291-63e2-4853-a7ea-9695bd1343bb.png)

This family tree can be confusing, but we aren't here to explain it. We're here to explore the data underneath the hype, and we'll do it using search interest data from Google Trends. We'll recreate the Google Trends plot to visualize their ups and downs over time, then make a few custom plots of our own. And we'll answer the big question: is Kim even the most famous sister anymore?

First, let's load and inspect our Google Trends data, which was downloaded in CSV form. The query parameters: each of the sisters, worldwide search data, 2007 to present day. (2007 was the year Kim became "active" according to Wikipedia.)

This Project provides the opportunity to apply the skills covered in Data Manipulation with pandas and Manipulating Time Series Data in Python and their prerequisite courses.

"Present day" for this Project was March 21st, 2019 so the monthly data spans from 2007-01-01 to 2019-03-01.
