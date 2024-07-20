# Content Based by Cosine Similarity: Movie Recommender System

## Introduction
#### Machine Learning in Recommender System

Recommender systems are vital in personalizing user experiences by suggesting products or content based on user preferences. Two main approaches are commonly used in recommendation systems:

### Collaborative Filtering: 
This method relies on the interaction history of users and items. By analyzing purchase patterns and co-occurrences, it finds similarities between users or items to make recommendations. The principle behind collaborative filtering is that if users share similar tastes, their recommendations will also be similar. This approach identifies users who are like you and suggests items they have enjoyed but you have not yet discovered.

### Content-Based Filtering: 
This approach recommends items similar to those the user has liked in the past, based on item features and user preferences. It involves analyzing item characteristics and comparing them with user profiles to make personalized recommendations.

In this project, we focus on a content-based approach using cosine similarity and Term Frequency-Inverse Document Frequency (TF-IDF) to recommend movies based on their content features.


## Methodology
### TF-IDF (Term Frequency-Inverse Document Frequency)
TF-IDF is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus). It helps in understanding the relevance of terms within the documents and is widely used in text mining and information retrieval.

### Cosine Similarity
Cosine similarity is a metric used to measure how similar two vectors (e.g., text documents) are. It calculates the cosine of the angle between them, which indicates how similar they are in terms of direction, regardless of their magnitude. In the context of a recommender system, cosine similarity is used to compare the content of movies and recommend those that are most similar to a given movie.

## References

- [Recommender System using Singular Value Decomposition](http://rstudio-pubs-static.s3.amazonaws.com/335300_11d40bf12d8940f78d9661b3c63150dc.html)
- [Singular Value decomposition (SVD) in recommender systems](https://medium.com/@m_n_malaeb/singular-value-decomposition-svd-in-recommender-systems-for-non-math-statistics-programming-4a622de653e9)
- [Various Implementations of Collaborative Filtering](https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0)
- [Collaborative Filtering based Recommendation Systems exemplified..](https://towardsdatascience.com/collaborative-filtering-based-recommendation-systems-exemplified-ecbffe1c20b1)
- [Machine Learning. Explanation of Collaborative Filtering vs Content Based Filtering.](https://codeburst.io/explanation-of-recommender-systems-in-information-retrieval-13077e1d916c)




