# About my first project on Github - Exploring Hacker News Posts - Completed in collaboration with @ArafatSadiq

In this project, we'll compare two different types of posts from Hacker News, a popular site where technology related stories (or 'posts') are voted and commented upon. The two types of posts we'll explore begin with either Ask HN or Show HN.

Users submit Ask HN posts to ask the Hacker News community a specific question, such as "What is the best online course you've ever taken?" Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting.

We'll specifically compare these two types of posts to determine the following:

1. Do Ask HN or Show HN receive more comments on average?
2. Do posts created at a certain time receive more comments on average?

It should be noted that the data set we're working with was reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions.



This data set is Hacker News posts from the last 12 months.

It includes the following columns:

1. title: title of the post (self explanatory)

2. url: the url of the item being linked to

3. num_points: the number of upvotes the post received

4. num_comments: the number of comments the post received

5. author: the name of the account that made the post

6. created_at: the date and time the post was made (the time zone is Eastern Time in the US)

