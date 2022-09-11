# Topic Recognition

## Objectives

Identify the main topic/s from texts from a news database. The news are in English and are classified in 5 main topics.

This notebook trains 2 main models:

- A supervised one as a multi-classifier able to assign each document/text with one of the 5 topics.

- An unsupervised one ignoring the labels. Supose we have obtained a set of documents(texts) and we want to classify them by topics (topic modeling). The result will be a proposed grouping by topics (cluster) that will allow to identify the most important elements from each group. The number of topics or groups for this task are some of the parameters that need to be set.
  - KNN
  - LSA
  - LDA
