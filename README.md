# Data Mining
Technical Report on Data Mining, Webscraping, Google Analytics

## 1). Wowowiki: Creating a Wikipedia recommendation algorithm using a Semantic Network model
![image](https://user-images.githubusercontent.com/67006507/122386284-54d69c80-cfa0-11eb-9204-cbf48ddd0dd5.png)

Wikipedia, a free online encyclopedia, is known to provide information of every topic imaginable. Its contents are provided via a peer-reviewed open collaboration. A quick google search of a certain topic will almost always return a Wikipedia link in the first page of results. However as much as this can be widely and easily accessed, this can also be edited and updated by basically anyone who has an internet connection. This means that the content of Wikipedia is ever growing, collecting different information and interpretations from people all around the world regardless of a person’s qualifications.

This study attempts to explore exactly that concept of interconnectedness through Wikipedia’s hyperlinks. Using the English Wikipedia dump, the study seeks to understand the relationship of concepts centered around a chosen Wikipedia topic through a network analysis of Wikipedia abstract hyperlinks.

The models that will be used are capable of generating networks of any topic in the dataset. For the purpose of this research, the “Asian Institute of Management” and “Data Wrangling” Wikipedia pages will be used as examples. Aside from generating a network of their related topics, the models also offer a recommendation system that will generate the most relevant topics based on its closeness centrality and will ultimately provide both a visual and quantitative analysis of the topic of interest.

## 2). TRAILERs Can Tell:Correlating Movie Success with Movie Trailers
![image](https://user-images.githubusercontent.com/67006507/122392705-b26de780-cfa6-11eb-8991-6e7d61e14a42.png)

With the rise of technology, one of the most affected business sectors is the Movie Industry. The Movie Industry has been always a lucrative business. With the right Marketing and Sales Strategy, every movie production will be a box office hit. Due to this, the Movie Industry has been doing a lot of reformations in its Marketing Steps and one this are the heavy use of movie trailers for each of their movie production.

To discuss such correlation, Top 100 Movies Titles from 2020 until 2010 was web scraped from Rotten Tomatoes website. Rotten Tomatoes is one of the leading movie critic rating platforms on the web as of present which makes it a viable source of information. Using the generated movie titles, additional information from IMDb (another leading movie database) was extracted using web scraping. Such information includes movie profits, movie rating, movie awards and nominations and the likes. Using also the Movie Title, Movie Trailer Information was extracted in YouTube Website using web scraping and YouTube API. Such Information includes view counts, likes and dislikes count and many more. Using all the extracted data, the paper was able to conclude significant findings.

Using the data, the research paper was able to conclude a significant insight. It was observed that the most important factor in a movie trailer is the view count. The Movie Trailer Views Count has a string linear relationship to Movie Success in all three success factors. This means that Greater Number of View Counts will result to success in terms of Movie Rating, Movie Awards and Movie Earnings.

## 3). Breaking Down LA : Redefining and labelling Los Angeles Neighbourhoods through AirBnB Listings’ Non-Geographical Cluster labels
![image](https://user-images.githubusercontent.com/67006507/122393054-0e387080-cfa7-11eb-8244-f9fbe96d598f.png)

One of the most visited cities in America is the Los Angeles City. It is coined as the home of stars and tourists gather around Los Angeles for its scenic tourist spots and for fans to see their beloved celebrities. With the advent of the Real Estate Business boom, it is very crucial to know the details and description of real estate places around Los Angeles. With this study, we will be able to understand the different clustering derived from the features of Airbnb listings around Los Angeles.

Using a Kmeans Clustering, the study was able to cluster the Los Angeles Neighbourhood to three new distinct clusters with Different Characteristics. Cluster 0 can be considered the Prime Real Estate Place, Cluster 1, being the Business and Tourist Place and lastly, Cluster 2 as the Residential Oriented Place.

## 4). In what ways can Redditors f*ck up?:Clustering the Today I F*cked Up(TIFU) SubReddit Section
![image](https://user-images.githubusercontent.com/67006507/122420549-59aa4900-cfbe-11eb-99e9-bfae95dfe308.png)

Reddit. com is coined as the "front page of the internet" which means that it is one of most popular and frequently visited website globally. Due to a lot of users, different topics and subreddit submission are being done everyday to the website. This in turn give the website a very wide array of topics to maintain. One popular subreddit is TIFU, which contains stories from different people commiting mistakes and acts of stupidity. This study aims to uncover the common mistakes people make based on the submissions under the TIFU subreddit. This was achieved by first extracting the topics/concepts of the submissions using Latent Semantic Analysis and afterwards, K-means clustering was done to group submissions with similar concepts/topics.

Based from these, 12 distinct topics / themes under the TIFU subreddits were identified, with topics ranging from sexual to work themes to romantic themes.
