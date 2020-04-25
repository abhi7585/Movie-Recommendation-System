# Movie-Recommendation-System

## Terms:-

#### Content-based recommendation:
In this system, keywords are used to describe the items and a user profile is built to indicate the type of item this user likes. In other words, these algorithms try to recommend items that are similar to those that a user liked in the past, or is examining in the present. It does not rely on a user sign-in mechanism to generate this often temporary profile. In particular, various candidate items are compared with items previously rated by the user and the best-matching items are recommended. This approach has its roots in information retrieval and information filtering research.

#### CountVectorizer:
The CountVectorizer provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words, but also to encode new documents using that vocabulary.

#### Cosine Similarity:
Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them. The cosine of 0° is 1, and it is less than 1 for any angle in the interval (0, π] radians

#### Description:
The user enters the name of the movie and the number of the recommended movies user wants. Based on the features a combineFeatures column is created which is nothing but a concatenated string of all the features. Then it is transformed using CountVectorizer which is given input to cosine similarity which produces the index and value of all the movies wrt to the movie user-provided based on the count_matrix.
Finally, the list is sorted in order so that movie can be recommended. Using the index value movie title is retrieved from the df.

