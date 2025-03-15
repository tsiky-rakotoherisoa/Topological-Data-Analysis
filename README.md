# Topological-Data-Analysis

### Objective

Given two folders, normal folder and Asthma folder. The first folder consists of recorded sound waves of normal breathing. The second folder consists of recorded sound waves of breathing with a wheezing sound. We want to perform a binary classification using Topological Data Analysis.

### Useful functions for this project

1- Function to apply a Takens embedding transformation to a given time series using a specified embedder. It transforms the input time series into an embedded time series and optionally prints the shape of the embedded time series along with the optimal embedding dimension and time delay.

2- Function designed to transform a list of persistence diagram into a single array where each point in the diagram is labeled with its corresponding homology dimension.

3- Functions to generate features using persistence entropy, Carlson coordinate, Wasserstein distance.
This function takes as input an audio file and return the features concatenated. Features from the Carlsson coordinate, and the different metrics.
