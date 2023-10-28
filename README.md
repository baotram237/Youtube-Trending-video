# Youtube-Trending-video
EDA trending videos on Youtube

# Focus on Exploratory Data analysis
**Youtube Trending Videos**

# Our Objective:
- Analysis Factors that make a video go on top Trending in the US
- Finding out the underlying patterns of these videos and viewer behavior
- Explore the relationship of view, likes, dislikes, and comments through correlation matrix and scatter plots
- Using WordCloud to find out the topics that are popular among YouTube viewers
  
# Key Analysis Questions:
- What are some special features of trending videos (publish time, category, topic, titles...)?
- Is there any relationship between the views, likes, dislikes, and comments?
- How long videos can go on top trending and the trending duration?
- Do the favorite subjects of YouTube viewers change over time?
- What is the best time to publish a video that is easier to be on top trending?

- The dataset (sourced from Kaggle) includes trending video information (id, title, publish time, channel, category, trending date, tags, view, like, dislike, comment, description, etc.), collected from 12/8/2020 to 13/10/2023, consisting of **231,787 rows** and **16 fields**.

# Tasks:
- Data preprocessing: Validate data, Map with JSON file, identify abnormals
- Analysis of the trending videos, and viewer behaviors, find valuable insights related to the topic, category, and publish time for creator that enhance the chance to be on top trending.

# Some findings:
**- It usually takes 1-5 days for a video to go on top trending. Videos can be on top trending for mainly 4-7 days, there are some videos that on the top for more than 37 days**
![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/f5a2735f-9ac0-448e-af59-9dbaea35f7e0)

**- Gaming, entertainment, and Music videos are more popular on top trending**
![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/3be52e27-808f-4a51-9a87-190e111cda07)

**- Sports videos are now more attractive and have an average views increase sharply, while Music, Entertainment, and other's average views decreased dramatically, which expresses the change in viewer attention over time.**
![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/811c5718-dabd-40eb-844c-b375353d946c)

**- There is a strong positive correlation between likes and views, while views increase, likes will increase, the correlation between comment counts and likes is also considerably strong.**
  ![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/b99e2d51-45d7-4598-b078-24b253219c60)

**- Some trending topics on YouTube for 3 years (word cloud from tags and title): Music videos and gaming videos are so far on hot topics**
![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/34064437-97f4-442d-a413-3766aa1c8faa)

![image](https://github.com/baotram237/Youtube-Trending-video/assets/82713550/1dd74810-2628-4d34-b57e-df91f9038bd1)


