1️⃣ K-Nearest Neighbors (KNN)

KNN is a simple and powerful supervised learning algorithm used for:

Classification

Regression

Similarity search

🔍 Key Concepts:

Euclidean Distance

Cosine Similarity

Sorting by distance

Selecting top K neighbors

⚙️ Implementation Features:

Manual distance calculation

Sorting based nearest neighbor selection
2️⃣ KD-Tree (K-Dimensional Tree)

KD-Tree is a space-partitioning data structure used to efficiently search nearest neighbors.

🔍 Key Concepts:

Binary Tree structure

Splitting by alternating axes

Tree Traversal

Backtracking

Pruning search space
Supports cosine similarity

Clean step-by-step logic

3️⃣ Locality Sensitive Hashing (LSH)

LSH is an approximate nearest neighbor algorithm used for high-dimensional similarity search.

This implementation uses:

🔍 Random Hyperplane Method (Cosine Similarity)

Steps:

Generate random hyperplanes

Compute dot product with data points

Convert sign to binary hash (0/1)

Group points into buckets

Compare only within same bucket

⚙️ Implementation Features:

Random hyperplane hashing

Bucket formation using dictionary

Query hashing

Cosine similarity inside bucket

Efficient approximate nearest neighbor search
