---
layout: post
title: Reflection on the Online News Popularity Analysis
---
[Github Pages Repo](https://kaslemr.github.io/Online-News-Popularity-Blog-Post/)

My process for this project began with reading in and exploring the online news dataset. I also read the paper **Predicting and Evaluating the Popularity of Online News** by Hen and Yang, which provided additional context to the features created in this dataset and attempts to predict the number of social media shares. The objective of this project was relatively simple - predict the popularity of each article. Much of the hard work was done already because there were a lot of features that characterized the articles using natural language processing techniques such as sentiment analysis and word counting. I started by visualizing the dataset with exploratory analysis and noticed the the response variable had a very large range, and a few outliers. These outliers were articles that were shared a many times more than other articles - this would probably affect the predictions.

Then, I set up the regression analysis using two tree-based algorithms and, performed the CV training, and evaluated them based on RMSE on the test sets. Finally, I set up an automated process to run each weekday's report.
<br />
<br />
If I were to do this project again, or if I had more time, I would try to automate data selection techniques as well as outlier analysis. This way, I could optimize each data set before training the models, and the performance of the models would likely improve. 

My big takeaways for this project were understanding the process for automating reports in R, and learning how one can use feature engineering to create a dataset used for prediction on text such as news articles. Seeing the variables created in the dataset gives me perspective on the type of features you can create if you don't go with a neural network algorithm for prediction on text.


