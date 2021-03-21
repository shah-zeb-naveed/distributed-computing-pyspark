# Distributed Computing - PySpark

This repository contains mini-projects on distributed computing using Spark in Python.

1. Text Analytics: Point-wise Mutual Information in PySpark

Calculates the PMI for a token or a pair of tokens for all the words ocurring in a text file.

2. Graph/Network Analysis: Personalized PageRank Algorithm in PySpark

Implements a modified version of the PageRank Algorithm in which the ranking is performed in reference to a given source node. The modifications are two-fold:
1. Random Jumps only to the source node
2. Lost mass due to dangling nodes is transferred completely to the source node instead of redistrubuting over the entire graph
