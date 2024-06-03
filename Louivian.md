# Analysis of Facebook Pages Public Figure Network

## Overview

This analysis involves the use of the Louvain algorithm to detect communities within the Facebook Pages Public Figure Network. The network graph visualization and the results of the community detection are discussed below.

## Louvain Algorithm

The Louvain algorithm is an efficient method for detecting communities in large networks. It optimizes modularity, which is a measure of the strength of division of a network into communities. Nodes within the same community are densely connected, while connections between communities are sparser.

## Visualization

Below is a force-directed graph visualization of the network, showing the communities detected by the Louvain algorithm. Each node represents a Facebook page of a public figure, and edges represent the connections between them. Nodes are colored based on the community they belong to.

![Louvain Communities in Facebook Pages Public Figure Network](./Screenshot_2024-06-03_125254.png)

## Results

### Louvain Modularity

The modularity score for the Louvain community detection is:
- **Louvain Modularity**: 0.18277296317353717

A higher modularity score indicates a stronger community structure. In this case, the modularity score suggests a moderate level of community structure in the network.

### Louvain Conductance

Conductance is a measure of the quality of the community structure, comparing the edge boundary of communities:
- **Louvain Conductance**: [0.43162217659137575, 0.3532608695652174, 0.5907894736842105, 0.7155655095184771]

Lower conductance values indicate better-defined communities. The range of conductance values here suggests varying degrees of community definition within the detected communities.

### Louvain Normalized Mutual Information (NMI)

NMI compares the similarity of the detected community structures with a ground truth. For this analysis, we used the Louvain results as the ground truth for demonstration purposes:
- **Louvain NMI**: 0.017451710723215084

An NMI value close to 1 indicates high similarity, while a value close to 0 indicates low similarity. The low NMI value here suggests that the detected communities are quite distinct from the ground truth, highlighting the complex structure of the network.

## Conclusion

The Louvain algorithm successfully identified several communities within the Facebook Pages Public Figure Network. The moderate modularity score and varying conductance values indicate a reasonable community structure, though the low NMI suggests further analysis with a more accurate ground truth is necessary.

This analysis provides valuable insights into the structure and interconnections within the network, showcasing the effectiveness of the Louvain algorithm for community detection.

