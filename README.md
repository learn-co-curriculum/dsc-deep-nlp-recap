
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 44.

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:

* Word Embeddings are a type of vectorization strategy that computes word vectors from a text corpus
* Word embeddings use similarity metrics, which can reveal how certain words relate to each other, or "semantic relationships"
* Unlike TF-IDF vectorization, the size of word embeddings is a tunable parameter, which can help overcoming the Curse of Dimensionality
* Word Embeddings can be created using so-called "Word2Vec" models that are given enough training data
* Deep learning is used to create Word2Vec models, and the idea is that given a certain context, the model should be able to generate the next most plausible word in the sequence
* Training Word Embeddings can be really time consuming, and when building a predictive model you'd want to avoid spending a lot of time here. Pretrained Word Vectors are very useful here, and GLoVe is the most commoly used model
* When using GLoVe, and moving towards a vector representation for any arbitrarily-sized block of text, Mean Word Embeddings can be used
* scikit-learn pipelines can be used to create Mean Word Embeddings
