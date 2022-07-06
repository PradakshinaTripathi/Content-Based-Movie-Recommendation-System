# Content-Based-Movie-Recommendation-System

The Project talks about a Movie Recommendation System (content Based) which works on cosine Similarity. You can enter the movie and choose the top 5 recommended movies which you might also like. The project includes the GUI of the Recommendation System.

Recommendation systems are used to increase user attraction by gaining a better grasp of the user's preferences. These systems have grown in popularity as a result of their capacity to provide users with customised material that is relevant to their interests. Millions of products are listed on e-commerce websites these days, making it nearly impossible to select a product of our choosing. This is where these systems come in handy by immediately proposing the things we want.
The categories of the algorithm for recommendation systems are – 
•	Content-based Recommendation.
•	Collaborative-filtering Recommendation
•	Hybrid Recommendation.

1. Content-based Recommendation
The main goal of a content-based recommender system is to determine how similar things are. Other users, if not ourselves, are not involved in this form of filter. The algorithm will just select items with similar content to recommend to us depending on what we like. There's less variety in the recommendations in this approach, but it will operate whether or not the user rates objects. Of course, there are numerous categories on which we can compute similarity: in the case of movies, we can choose to design our own recommender system based just on genre, or we may wish to include director, main actors, and other factors.

2. Collaborative Filtering Recommendation
We locate comparable people and recommend anything they want through Collaborative Filtering. We aren't using the item's features to recommend it in this form of recommendation system; instead, we group users into clusters of similar types and then recommend each user based on their cluster's preferences.
This method provides suitable items to the user based on the preferences of their neighbours. It determines the user's and his neighbour’s similarities before predicting the items. There could be an infinite number of users. From a list of users, this technique determines the most comparable user.
However, the similarity between users is determined by the ratings that people have given to a specific item.
In this way, the process continues and the desired outcome is achieved. This technique uses the user's ratings for any item in the enormous archive of user ratings. The user-item matrix is the name given to this enormous collection.

Why Cosine Similarity?
The cosine similarity between them is more accurate the more accurate the vector representation of the real-world object is.
The metric of cosine similarity is used to determine how similar two objects are. It estimates the cosine of the angle formed by two vectors projected in a multi-dimensional space mathematically. The output is either 0 or 1. 0 indicates no similarity, while 1 indicates that both elements are identical.


Programming Language –
Python


Libraries Used –
i.	Numpy – Numpy is the library that is used for mathematical calculation. It extends Python with intelligent data structures that ensure fast computations with arrays and matrices, as well as a large library of high-level mathematical functions that work with these arrays and matrices.

ii.	Pandas – Pandas is mostly used for data analysis and related tabular data modification in Dataframes. Pandas supports importing data from comma-separated values (CSV), JSON, Parquet, SQL database tables or queries, and Microsoft Excel.


iii.	Matplotlib.pyplot – Matplotlib is a Python package that allows you to create static, animated, and interactive visualisations.

iv.	Requests - The requests module allows you to use Python to send HTTP requests. The response data from an HTTP request is returned as a Response Object (content, encoding, status, etc).

v.	BeautifulSoup – Beautiful Soup is a Python module that is used for web scraping purposes to get the data out of HTML and XML files. It extracts data in a more understandable and hierarchical manner by creating a parse tree from the page source code.

vi.	Difflib – As the name implies, the difflib module may be used to find differences or "diffs" between the contents of files or other hashable Python objects. It can also be used to calculate a ratio that shows how closely two objects are related.

vii.	Sklearn – Classification, regression, clustering, and dimensionality reduction are just a few of the useful capabilities in the sklearn toolkit for machine learning and statistical modelling.


viii.	Tkinter – This framework makes it easy for Python programmers to develop GUI elements using the Tk toolkit's widgets. In a Python application, Tk widgets can be used to create buttons, menus, data fields, and so forth.

ix.	Seaborn – Seaborn is a Python module for creating statistical visuals. It's built on matplotlib and works well with pandas data structures. Seaborn assists you in exploring and comprehending your data.

Check Capture.png for the steps and algorithm





Conclusion
If we want to recommend suggestions based on aspects like genres, actors, overview, and so on, a content-based recommendation system is ideal. When we use parameters like genres, cast, and crews, which provide more in-depth information about the user's preferences, the accuracy of content-based filtering improves. The most basic type of recommendation system is based on Demographic filtering, which just uses parameters like popularity, budget, and revenue; these fields don't provide any specific information that could help us determine the user's preferences/likes.
Data Scraping was an essential part of the whole recommendation system. They are the features that are used to give the recommendation.
Talking about collecting the data, there are many APIs used. BeautifulSoup is the easiest and simplest way to scrape data from a particular site.
Cleaning the data helps to remove all the noise from the dataset. So after cleaning of the data we move for rest if the processes.
Some disadvantages of content-based filtering include the fact that it can only create suggestions based on the user's existing interests and does not consider what other users think of an item, resulting in low-quality item recommendations on occasion.


Future Work
Many other modifications, tests, and experiments have been postponed leading to a shortage of time (i.e., real-data research is normally quiet time consuming, taking days to complete a single run). Future research will focus on a more detailed examination of specific mechanisms, innovative suggestions for experimenting with other ways, or simply curiosity.
Further the improvised ideas could be –
1.	Taking More Complex Dataset – 
The dataset is from IMDB website, later in future, more complex dataset and live human tweets can be used. Also, the number of datasets is limited to 1000 which could be increased.

2.	Using Other type of Recommendation System – 
The other filtering and similarity measures can be checked to check the difference with the cosine similarity that has been used. The user Rating can be considered and on the basis of the rating, the system might recommend the movies from highest to lowest.

3.	Using More features – 
We can use more features like the gross of the movie, the rating, the Metascore, the votes etc., to make the recommendation system more accurate.

4.	Fetching the images of the Movies –
The image of the movies can be added in the GUI so that the GUI could look more interactive.
