# Reddit-Scraper-info
Example and description of private ecobee-reddit-scraper project

![](/reddit-scraper.png)

This web application is a graphical interface for analyzing the sentiment values of subreddits posts and was created at the ecobee hackathon (HackTheHive). After providing a subreddit, the app pulls data from the Reddit API and passes the posts through Google's Natural Language Processing API to provide a sentiment for the text. We use this to categorize the data into 3 sections, positive, negative, and questions, then display the data in graph form. In order to save on cost, we persist the sentiment values of posts we have already seen in a PostgreSQL db.
