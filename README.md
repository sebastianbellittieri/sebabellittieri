# Readme!

Hi! Mi name is Sebastián Bellittieri. 

This repository was created in order to work with some time-series projects including my Master's Thesis in Applied Statistics (in a separate branch).

I have hust added a new file presenting my solution to a Data Scientist test for Globant. It has 3 separate excersises: 

The first using NLP with Bert-topic to identify topics in abstracts showing how we can model topics from a set of academic papers from NSF Research Awards. 
I have a sample of more than 13159 abstracts files from a variety of subjects. I did use an unsupervised model to classify these abstracts into topics.

I have chosen BERTopic model in orden to produce an acceptable outcome for this process and being able to explain every part of my procedure. 
I could have used LLM's but I have found 2 main issues regarding LLM's for this particular task: the first was related to the costs of working with LLMs 
(with exception of LLAMA2 of course) and the other important aspect is that in a certain aspect LLMs work as a "black box". I have selected BERTopic because 
it has the power of a transformer model that uses word embeddings and this text vertorization makes possible to locate semantic similar words and also supports 
UMAP for dimension reduction and HDBSCAN for document clustering and I can explain these concepts though a technical interview.

The second part of this notebook is related to clustering. With the Birmingham credit card expenses from August 2021-August 2022 I have performed a RFM clustering with 
Kmeans for clustering.

In the third I have forecasted with SARIMAX the dayly expenditures for the moth of August 2022 and evaluated some metrics against my test set.

There is a larger description of every exercise in the notebook and comments regarding every output. 
