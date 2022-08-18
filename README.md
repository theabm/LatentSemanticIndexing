# Information Retrieval Project

This repository contains an implementation of Latent Semantic Indexing for the Information Retrieval course held by Professor Luca Manzoni at the University of Trieste AA. 2021-2022.

# Goal

Implement an Information Retrieval System that uses Latent Semantic Indexing (LSI) to answer queries. The main goals are to:

    - Implement a system that accepts free-form text queries
    - Evaluate the system on a set of queries
    - Explore the effect of different dimensions for dimensionality reduction in quality of retrieval

# Data Set

The data set consists of a 35,000 movie descriptions scraped from wikipedia. This dataset was found from Kaggle.

Among other things, it contains the title and plot description of each movie. A complete description of the data set can be found here:

https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots

# Implementation

The implementation can be found in the illustrative notebook named "LSI.ipynb". 

# Important Note
The notebook was ran on google colab, therefore, the paths and filenames are relative to that particular environment. To be able to properly run everything, fork the repository and change all the paths to a folder where the raw data set is contained and the where the cleaned corpus will be saved. 

