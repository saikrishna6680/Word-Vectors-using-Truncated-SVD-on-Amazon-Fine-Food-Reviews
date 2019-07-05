# Word-Vectors-using-Truncated-SVD-on-Amazon-Fine-Food-Reviews

Word Vectors using Truncated SVD is applied on Amazon Reviews dataset.

Procedure Followed:

1. Take Reviews From data-set.

2. get Top Important Features using TF_IDF.

3. Calculate Co-occurance Matrix with Selected Top Important Features.

4. Choose the n_components in Truncated svd, with Maximum Explained Variance and Plot the cummulative Explained Variance ratio.

5. Apply K-means clustering Algorithm & find number of cluster using Elbow method.

6. Write a Function that takes a word and returns the most similar words using cosine similarity between the vectors.
