# Clifford Algebra Multi-Vector Transformer
NN - Bruno Francesco Nocera, Leonardo Colosi

## Introduction
The task chosen is a NLP binary classification task about sentiment analysis of reviews. Given in input a text review the model has to output if it is a good review or a bad one.In order to solve the sentimental analysis task we have decided to implement a classical transformer model with a custom attention function based on geometric algebra operations (see Geometric Algebra). Our approach involves building an encoder model capable of producing meaningful embeddings with lower dimensionality

## How to run
Load the MultiVectorTransformer.ipynb in colab and press Run All button.
In the global config cell there are some parameters that could be change to make experiments. 




TODO:
- [X] MultiVector embedding
- [X] Positional encoding
- [X] SterableGeometricProduct product attenction function
  - [X] (n,d) (d,n) --> (n,n) multivectros
  - [X] FC for each grade (?)
  - [X] Normalization
  - [X] Optimization (alternative to test)
    - [X] Remove learnable gm
    - [X] Parallelize subspaces projection
    - [X] Use samaller algebra dimention
    - [X] Change geometric product logic
- [X] Test against dot product transformer
- [X] Plot losses 
- [X] Metrics



