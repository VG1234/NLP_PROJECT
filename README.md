# **A system that classifies and answers incomplete question tweets**


Twitter has 396.5 million users worldwide, according to data on its audience. Even though it may not have as many users as platforms like Facebook and Instagram, which have billions of users each, Twitter nevertheless has a faithful following of people that log in frequently. In fact, Twitter has 206 million active users every day, so people are always checking it out to see what others are tweeting about.There is a lot for Twitter users to share with their followers. The website has evolved into a location where users may post daily updates and talk about shared interests with other users from around the globe. There are many conversations to join because at least 500 million tweets are sent every day.Tweets from accounts that users don't follow have been added to users' timelines as part of an experiment by Twitter. In light of recent confirmation from the social network, it is now a standard function and no longer an experiment.

Information propagation on Twitter makes this platform more popular than any other social media platforms.The importance of summary becomes more significant while dealing with social media platforms like Twitter where information is overloaded with rich content and is ever increasing. Besides using this communication media for relationship maintenance, many people also use it as valuable information sources and engage in question and answering (Q and A). With the increasing popularity of social Q and A, different questions are being asked on Twitter and some of these questions are objective in nature, where in a question is posted as text with a link to an article or a web source attached to it. This link provides the description and answers to the question.

The motivation for this project is to identify the incomplete question tweets which are objective in nature with a URL provided to answer the question and then obtain a brief summary using the content provided in the web source or article present in the URL. This would save time for many people on Twitter. There exists research work that focuses on Question identification on Twitter. In this project, our work extends the Question identification by extracting the answers to the question.

# **Datasets**

We have collected the tweets from three different twitter pages using Twitter APIv2
1. Article Bay
2. Sciencefocusqa
3. BIz_articles_

Stored them in csv file 
> you could find them in Datasets/twitterdata.csv

Manually we have classified 1000 tweets whether they are complete or incomplete as 1 and 0.
> Stored them in Datasets/Datasetforbert - Sheet1.csv

Used that data for classification, you could find indepth info in **NLP_TEAM5.ipynb**
