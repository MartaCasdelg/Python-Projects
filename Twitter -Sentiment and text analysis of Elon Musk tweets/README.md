# **Sentiment Analysis of Elon Musk Tweets** 

![Twitter](https://images.unsplash.com/photo-1661195158340-8227d1b17d6e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1332&q=80)


## Description
This subrepository contains a Twitter API data extraction project done in order to collect information about Elon Musk's tweets and perform sentiment and NPL analysis.

In the jupiter notebook you will find the steps to perform the data extraction as well as to perform the analyses. Although I have selected Elon's profile for this project, you can choose the one you like the most and carry out your own project.

Additionally, I have included the csv resulting from the project, including both the raw and final extracted data, which went through a cleaning and transformation process that you can also contemplate in the notebook. You can download the data from this repository or from [kaggle](https://www.kaggle.com/datasets/marta99/elon-musks-tweets-dataset-2022), where I have uploaded the dataset.

The dataset contains information about:

- `Tweets`: original text of the tweet.
- `Retweets`: number of retweets of the current tweet.
- `Likes`: number of likes of the current tweet.
- `Date`: date of creation of the tweet.
- `Cleaned_tweets`: text of the tweet after removing 'RT', hashtags, hyperlinks, mentions, emojis, leading and trailing whitespaces.

Please note that to get data from the api you need a developer account on the twitter developer portal, as well as a minimum permission level of 'elevated'.

If you have an 'essential' permission level, this code will not work for you so you have to make a request to have your permissions extended through the developer portal. Once this is done, you will be able to run this code with your login credentials.


## Resources

* [Twitter API documentation.](https://developer.twitter.com/en/docs/twitter-api)
* [Using the Twitter API for Academic Research Track (Professor Foote Youtube video).](https://www.youtube.com/watch?v=rQEsIs9LERM)
* [Scrape Users Tweets (Samarth Godase Youtube video).](https://www.youtube.com/watch?v=1ELzPZcpTsg)


## Feedback

If you have any feedback, please reach out to me at martacasdelg@gmail.com


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://martacastrillo.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marta-castrillo-delgado/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/martacasdelg)
