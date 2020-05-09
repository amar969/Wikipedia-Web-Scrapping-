# Asia-countries-Area-wise-list-web-scraping

What is Web-Scraping ??

It's the process of extracting information from a web page by taking advantage of patterns in the web page's underlying code. Let's start looking for these patterns!

For our dataset extracation we are using Wikipedia page of Asia area wise list.

Wikipedia Link -: https://en.wikipedia.org/wiki/List_of_Asian_countries_by_area

When converting this into dataset,

Extracting the list of country names from the list of Wikipedia List.

Here we are using two different Libraries 
1. Requests (we can install using "pip install requests")
2. BeautifulSoup (we can install it using "pip install BeautifulSoup")

Here we are using tag name,

find_all() is the most popular method in the Beautiful Soup search API, you can use a shortcut for it. If you treat the BeautifulSoup object or a Tag object as though it were a function, then it’s the same as calling find_all() on that object. These two lines of code are equivalent:

soup.find_all("a")
soup("a")

We are extracting all the anchor's tag of html from our Wikipedia page.

Then using Pandas 

we are converting extracted list of Title from anchor tag into Dataframe using pandas.

