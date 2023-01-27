# Twitter_Scrapping

![52018-103343-51653-102330-twitter-xl-xl](https://user-images.githubusercontent.com/116914474/215165753-1ca890fa-5045-40bf-b8ab-0b745cb9e57c.jpg)
Check it out a script for twitter data scrapping with sreamlit GUI. This way Data Scientists scrape data from twitter for research purpose.
## Benefits:

1)You can search data as per your need.(you can even use hashtag to search the data related to it)

2)The Scraped data will be shown in the form of a dataframe.

3)You can upload that scraped data to a mongodb Database.

4)You get an option to download the data onto your machine in two different formats those are CSV and JSON.

## Discription:
### Problem statement
Today, data is scattered everywhere in the world. Especially in social media, there may be a big quantity of data on Facebook, Instagram, Youtube, Twitter, etc. This consists of pictures and films on Youtube and Instagram as compared to Facebook and Twitter. To get the real facts on Twitter, you want to scrape the data from Twitter. You Need to Scrape the data like (date, id, url, tweet content, user,reply count, retweet count,language, source, like count etc) from twitter.

### Approach:
● By using the “snscrape” Library, Scrape the twitter data from Twitter
(Note "snscrape" is also used to scrape the data of Instagram, Facebook, Reddit and may more.)

● Creating a dataframe with date, id, url, tweet content, user,reply count, retweet count,language, source, like count.

● Storing each collection of data into a document into Mongodb along with the hashtag or key word we use to Scrape from twitter.

● Creating a GUI using streamlit that should contain the feature to enter the keyword or Hashtag to be searched, select the tweet count that need to be scraped. After scraping, the data needs to be displayed in the page and need a button to upload the data into Database and download the data into csv and json format.
## Working Procedure
1)Download the "Twitter.py" file.

2)Open Terminal if your machine is mac or command prompt if it is windows.
![Screen Shot 2023-01-28 at 12 49 25 AM](https://user-images.githubusercontent.com/116914474/215178594-d0941770-2d78-40eb-82bb-01eaf5af48e5.png)

3)After running "streamlit run twitter.py" command a window gets directly opened
![Screen Shot 2023-01-28 at 12 56 18 AM](https://user-images.githubusercontent.com/116914474/215179729-8ce2409e-afb6-4365-bf49-e0e121fc279b.png)

4)You can select the count of data that to be scraped.
![Screen Shot 2023-01-28 at 12 59 45 AM](https://user-images.githubusercontent.com/116914474/215180324-bb333671-4f2c-4040-ada1-07897e8e9e00.png)

5)You can upload the data in mongodb database 

6)If you want to download you can download the file in the format it should be downloaded.

![Screen Shot 2023-01-28 at 1 03 51 AM](https://user-images.githubusercontent.com/116914474/215181855-04f14143-c9f1-4fa9-8739-c3d06e952d97.png)

