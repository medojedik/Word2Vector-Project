# Word2Vector
## Introduction
Word2Vec uses CBOW or Skip-gram method for computing vector representations of words. 
These representations can then be used in many 
natural language processing (NLP) applications and for further use.
## How does W2V work
Word2Vec takes a *text corpus* as input and produces *word vectors* as output. 
First it constructs a vocabulary from the training text data and then 
learns vector representation for each word using neural network. The resulting word vector file can later on be used
in many NLP and machine learning applications.
## As for this project
In this repository I am using Word2Vec on collected text data from 
**Chamber of Deputies of the Czech Republic**. 
My main goal is to have (semantically) similar words close in vector space which Word2Vec creates.

#### Also done in this project:
- I am using **gensim** library from Radim Řehůřek
- In this repository I am exploring different usage of gensim's word2vec *(E.g. finding most similar words)*
- I am visualizating word vectors in 2D plot using **t-SNE** for dimensionality reduction
- I am using **clustering** to find some interesting cluster groups for word vectors
- For all above I am using **cosine metric**
