
# Airbnb Data Analysis

In this project we're going to study Airbnb business in New York City of different hotels. We'll explore the
data and fetch insights and recommend business decisions based on those insights. We'll computer this for
different hotels and compare if one is doing good what’s the reason behind it or if other is doing bad what’s
the reason behind that as well. We'll try to figure out the patterns between different features and how each
feature is impacting the target variable (price). From this analysis clients are going to benefit from. If we
provide them all the information about areas of hotels, type of services they provide and prices of multiple
hotels in that area then client will be able to easily and confidently select the required hotel based on its
services and client can get better environment according to his or her needs
There are two files in the dataset

### Inspiration:
* What can we learn about different hosts and areas?
* What can we learn from predictions? (ex: locations, prices, reviews, etc)
* Which hosts are the busiest and why?
* Is there any noticeable difference in traffic among different areas and what could be the reasonfor it?
* What are the features impacting price?
* Is price of the hotels have anything to do with areas of hotel?
* Which hotels have more listings and why?
* Which areas have more hotels and why?
* How do the price and listing vary in hotels?


## Summary & Conclusion

This Airbnb ('AB_NYC_2019') dataset for the 2019 year appeared to be a very rich dataset with a variety of columns that allowed us to do deep data exploration on each significant column presented. We have tested several hypotesis against the data, and the conclussions obtained are listed at the end of each section, however, here are the most interesting ones (IMO).

1. First, we have found hosts that take good advantage of the Airbnb platform and provide the most listings; we found that our top host has 327 listings.
2. After that, we proceeded with analyzing boroughs and neighborhood listing densities and what areas were more popular than another. Next, we put good use of our latitude and longitude columns and used to create a geographical heatmap color-coded by the price of listings.
3. Further, we came back to the first column with name strings and had to do a bit more coding to parse each title and analyze existing trends on how listings are named as well as what was the count for the most used words by hosts. Lastly, we found the most reviewed listings and analyzed some additional attributes.
4. For our data exploration purposes, it also would be nice to have couple additional features, such as positive and negative numeric (0-5 stars) reviews or 0-5 star average review for each listing; addition of these features would help to determine the best-reviewed hosts for NYC along with 'number_of_review' column that is provided.
5. Overall, we discovered a very good number of interesting relationships between features and explained each step of the process.
6. NYC shared rooms tend to be grouped in the city centre, maybe becuse there are thought for travelers who want to visit the most iconic city places.
7. Relating the price/popularity variables suggest that people who travel and use Airbnb tend to prefer the posts which are cheaper
8. There are two types of user posting rooms: Professionals, which are outliers, each one holding a high number of rooms; and Amateurs, who usually have only a few. Although amateurs can be making money as a business to, their volume is clearly inferior to the professional ones.

9.  The professional posts are located in the city centre.

10. The way rooms are announced is different between professionals and amateurs. The first use more objective terms to describe the room whereas the second use more subjective.

11. Having a room "near to" things affect to popularity (maybe it's a good idea to include this words in the title of the room).

This data analytics is very much mimicked on a higher level on Airbnb Data/Machine Learning team for better business decisions, control over the platform, marketing initiatives, implementation of new features and much more.