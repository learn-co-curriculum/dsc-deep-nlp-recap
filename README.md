
# Deep NLP with Word Embeddings - Recap

## Introduction

Congratulations! You know have a myriad of powerful NLP tools that you can begin to tap into and further explore. With that, take a minute to review some of the key concepts you were exposed to.

## Objectives
You will be able to:
* Understand and explain key concepts regarding RNN's, GRU's and LSTM's
* Understand and explain word embeddings

## RNN's and Word Embeddings

Remember that word embeddings are a type of vectorization strategy that computes word vectors from a text corpus. They use similarity metrics, which can reveal how certain words relate to each other, or "semantic relationships".
Unlike TF-IDF vectorization, the size of word embeddings is a tunable parameter, which can help overcoming the curse of dimensionality. Word Embeddings can be created using so-called "Word2Vec" models that are given enough training data.
Since deep learning is used to create Word2Vec models, training Word Embeddings can be really time consuming, and when building a predictive model you'd want to avoid spending a lot of time here. Pretrained Word Vectors are very useful here, and GLoVe is the most commoly used model When using GLoVe, and moving towards a vector representation for any arbitrarily-sized block of text, mean word embeddings can be used.


##  GRU's and LSTM's

Building from this, you then took a look at some new architectures for neural nets. Aside from having a temporal aspect as with RNN's, GRU's (Gated Recurrent Units) and LSTM's (Long Short Term Memory Cells) have capabilities for both summarizing important information seen prior and forgetting needless details to free up memory. This acts as an analogy to human memory and allows for improved performance in many tasks.

## Summary

In this section you learned about advanced deep network architectures including RNN's, GRU's and LSTM's. You also saw how to create word embeddings, an alternative methodology for encoding textual data into numerical spaces. With that, you also saw how to use transfer learning to apply Word2Vec models and improve NLP classification algorithms.
