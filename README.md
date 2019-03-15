# HackerNews_Posts_Analysis
In this project, we'll work with a data set of submissions to popular technology site Hacker News. We'll compare post submission to analyse whether user are more likely to 'ask a question' or 'share something interesting'. We will also analyse if the posts created at a certain time receive more comments on average than others.
We're specifically interested in posts whose titles begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question.

We'll compare these two types of posts to determine the following:<br>
- Do Ask HN or Show HN receive more comments on average?<br>
- Do posts created at a certain time receive more comments on average?

Some details about the data set 'hacker_news.csv' columns :<br>

id - The unique identifier from Hacker News for the post<br>
title - The title of the post<br>
url - The URL that the posts links to, if it the post has a URL<br>
num_points - The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes<br>
num_comments - The number of comments that were made on the post<br>
author - The username of the person who submitted the post<br>
created_at - The date and time at which the post was submitted<br>
You can find the analysis and conclusion in the file : <b>HackerNews_Post_Analysis.ipynb</b>
