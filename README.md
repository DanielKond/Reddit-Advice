# Reddit-Advice

In this project, data was obtained from reddit using its PRAW API. The data of interest was top posts of all time from the subreddits regarding dating and relationships.
The scores followed a roughly bimodal normal distribution with a slightly longer right tail.

https://raw.githubusercontent.com/DanielKond/Reddit-Advice/master/score_plot.PNG

A regex was used to roughly determine if a post was made by a Male, Female, or Unknown, and the top 10 comments for each post were stored in a separate file.

https://raw.githubusercontent.com/DanielKond/Reddit-Advice/master/pie%20chart.PNG

The comments were analyzed for the frequency of word distributions, as well as total word counts. It was found that while there were far more F posts in the top scores, M posts tended to receive statistically longer comments.

https://raw.githubusercontent.com/DanielKond/Reddit-Advice/master/response%20length.PNG

No particular differences were found in the responses to Male or Female posts following a sentiment analysis from the Vader library, and no Machine Learning algorithm was able to distinguish the gender of the post a common was made on.

https://raw.githubusercontent.com/DanielKond/Reddit-Advice/master/Valence%20Gender.PNG

The same process was also done for posts mentioning cheating or abuse. No significant differences were found in responses to those posts, however a graph of the valences shows that women who mentioned cheating were less likely to get a positive response.

https://raw.githubusercontent.com/DanielKond/Reddit-Advice/master/Valence%20Cheat.PNG

Overall, it appears that the common belief that Redditors treat men and women differently is not justified; however, it does appear to be true that the internet provides the same "advice" regardless of the particulars of the issue at hand

