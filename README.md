# Social Network Graph Link Prediction

### Problem statement:

Given a directed social graph, have to predict missing links to recommend users.

### Data Overview:

Data contains two columns source and destination for each edge in graph

1. source_node 
2. destination_node

### Business objectives and constraints:

- No low-latency requirement.


### Mapping the problem into supervised learning problem:

- Map this to binary classification task with 0 implying the absence of edge and 1 implying the presence of edge as y_i's.
- Now, I need to featurize the pair of vertices such that these features can help us to predict the presence/ absence of edge.
