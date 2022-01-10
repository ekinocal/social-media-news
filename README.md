How News Appears on Socıal Medıa

Inspiration

What do social media users care about, and in what ways do they care? What may they not know about? What types of trends appear most on each social media platform? Are people who get the majority of their news from social media able to get an accurate and comprehensive idea of what is going on? How can algorithms such as Twitter’s trending topics algorithm influence and shape what users talk about, read, and react to?

![image](https://user-images.githubusercontent.com/61598281/148839062-f7785b33-a217-416d-8308-170279b16f7a.png)

The emergence of social media has altered the information environment in a variety of ways, including how many Individual stay up to date on current events. In fact, social media is becoming one of the most popular avenues for individuals, especially young folks, to obtain political information.

Social media has had an undeniable influence on journalism, for better or for worse. It has accelerated the dissemination of news to a wider audience, but at the sacrifice of reliability and accurate reporting. Individuals nowadays utilize social media to gather information about the news rather than waiting for news broadcasters to discuss a breaking story.

With over 3 billion active monthly users, social media has become the primary source of information worldwide. Television news has been failing as many people have shifted to video streaming services, relying only on the website for their info. 

![image](https://user-images.githubusercontent.com/61598281/148839159-596b331f-a370-4dd0-aaf4-a64f81309596.png)

In this research I have tried to anlysis social media datas in different topic and ways. The dataset commonly contain Social Media datas and sentimesnts in different subjects. I tried to use all of them in different ways. I wish it will be helpfull.
These datasets consist of 9 different subjects. These are : news, news_api, politics, sports, television, trending, twitter, uplifting_news, worldnews.

![image](https://user-images.githubusercontent.com/61598281/148839358-a3f63107-190e-42c6-948d-af248b793bc2.png)


Data Analysis
First of all, news api dataset examined. There are 3 different title in Source column. All datas in this column were collected under three titles. In this way, two charts were created where the percentage distributions of the titles can be seen. Thanks to this analysis, the most popular broadcasting tool could be decided in the time in the dataset. The reason for using two different graphs was to better understand the percentile distribution.
    
![image](https://user-images.githubusercontent.com/61598281/148839428-cc4d8c8a-1574-4cd5-b0fb-0b790beeb6b0.png) ![image](https://user-images.githubusercontent.com/61598281/148839441-82ae9181-ecd8-46db-a1f6-44f12aa0767c.png)



The second dataset examined was the twitter dataset. The difference of this dataset from the others was that it made sentiment analysis. 
It had two columns showing positive and negative data, but it did not show whether the sentiment analysis result was positive or negative. Therefore, one more column was added and the results were found by subtracting the negative data from the positive data. All the results were visualized using the plotly library and it was possible to have an idea about the most intense topics and their sentiments at that time.
![image](https://user-images.githubusercontent.com/61598281/148839547-3d7ef6f2-3ed0-487a-9ebd-5043f6502b12.png) ![image](https://user-images.githubusercontent.com/61598281/148839570-3e6c38f7-9558-4694-89cb-1566829837e3.png)

Afterwards, it was decided to examine and compare the politics and sports datasets. By looking at the total scores of these datasets and visualizing them, an idea was gained about which one was mentioned more at that time.
![image](https://user-images.githubusercontent.com/61598281/148839702-9f539748-eaf2-47c8-a598-409aafdb008a.png) ![image](https://user-images.githubusercontent.com/61598281/148839722-91a3fb23-7521-4687-8a76-9b20f9198cb6.png)

By reading the trending dataset, the trends in that period and which trends were most talked about were looked at. In this way, it was possible to understand which ones were on the agenda at that time.
![image](https://user-images.githubusercontent.com/61598281/148839817-620f5827-a51a-4a50-9de3-02a23785b8ad.png) ![image](https://user-images.githubusercontent.com/61598281/148839851-189f1154-50f9-4df9-afc0-5e7a3d2686e6.png)

Finally, the news, television, politics and sports datasets were combined into a single dataset. They all had the same columns. This way they could all be compared. Two pie chars were created to receive the most comments and scores. These scores and comments are uniquely classified.!

![image](https://user-images.githubusercontent.com/61598281/148839901-852ed185-8de4-4a9d-be6b-b58522a7a68f.png)

![image](https://user-images.githubusercontent.com/61598281/148839955-796ff7b5-bb54-4714-bfe0-cefe7b776f7d.png)

Reddit API Analysis
Reddit APIs were used to compare the given datasets with the sports and politics parts. First of all, politics and sports queries were scanned within the seo query, and these were scanned in a 1-day period since our datasets are also in a 1-day period according to the subreddits. The distribution of the subreddits was visualized and compared with our datasets.

![image](https://user-images.githubusercontent.com/61598281/148839997-6759b59a-ace7-4818-837e-daaaf0afe144.png) ![image](https://user-images.githubusercontent.com/61598281/148840019-b36403ba-117f-4f0c-a7ee-8f2e30c8162f.png)



My Dataset Link: https://www.kaggle.com/socialmedianews/how-news-appears-on-social-media
