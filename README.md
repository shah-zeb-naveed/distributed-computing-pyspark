# page-rank-pyspark
Personalized PageRank Algorithm in PySpark

Implements a modified version of the PageRank Algorithm in which the ranking is performed in reference to a given source node. The modifications are two-fold:
1. Random Jumps only to the source node
2. Lost mass due to dangling nodes is transferred completely to the source node instead of redistrubuting over the entire graph
