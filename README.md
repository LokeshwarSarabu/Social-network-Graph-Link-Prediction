# Social Network Graph Link Prediction

### Problem statement:

Given a directed social graph, have to predict missing links to recommend users.

### Data Overview:

Data contains two columns source and destination for each edge in graph

1. source_node 
2. destination_node

### Business objectives and constraints:

1. No low-latency requirement.
2. Probability of prediction is useful to recommend ighest probability links.


### Mapping the problem into supervised learning problem:

- Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.
