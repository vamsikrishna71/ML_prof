Collaborative filtering is probably the most commonly used recommendation algorithm, there are two main types of methods:

User-based collaborative filtering is based on the user similarity or neighborhood
Item-based collaborative filtering is based on similarity among items
They both work similarly, let's briefly explain how user-based collaborative filtering works.

User-based collaborative filtering looks for users who are similar. This is very similar to the user clustering method done previously; where we employed explicit user profiles to calculate user similarity. However, the user profiles may not be available, so how can we determine if two users are similar?

User-item interaction matrix
For most collaborative filtering-based recommender systems, the main dataset format is a 2-D matrix called the user-item interaction matrix. In the matrix, its row is labeled as the user id/index and column labelled to be the item id/index, and the element (i, j) represents the rating of user i to item j.

Below is a simple example of a user-item interaction matrix:
