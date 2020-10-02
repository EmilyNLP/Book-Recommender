# book-recommender

This project is in progress.

1.[Web Scraping and EDA](https://github.com/yaodehong/Book-Recommender/blob/master/1_Web%20Scraping_EDA.ipynb)

2.[Weighted Rating__Naive Bayes__SVM](https://github.com/yaodehong/Book-Recommender/blob/master/2_Weighted%20Rating_Naive%20Bayes_SVM.ipynb)

On the website of goodreads.com, each book has a score which was denoted by "A book’s total score is based on multiple factors, including the number of people who have voted for it and how highly those voters ranked the book." I could not find the formula it uses and find the weighted rating formula applied by IMDB as follows:

Weighted Rating (WR) = $(\frac{v}{v + M} . r) + (\frac{M}{v + M} . C)$

where,
* *v* is the number of ratings for the book
* *M* is the minimum number of ratings required to be listed in the chart
* *r* is the average rating of the book
* *C* is the average rating across the whole dataset

I use the above formula to generate the book weighted raing score:


3.[Content Based Recommender](https://github.com/yaodehong/Book-Recommender/blob/master/3_Content%20Based%20Recommender.ipynb)

4.[Collaborative Filtering with neighborhood methods](https://github.com/yaodehong/BookRecommender/blob/master/4_Collaborative%20Filtering%20with%20neighborhood%20methods.ipynb)

5.[Collaborative filtering with latent factor models](https://github.com/yaodehong/BookRecommender/blob/master/5_Collaborative%20filtering_latent%20factor%20models.ipynb)
