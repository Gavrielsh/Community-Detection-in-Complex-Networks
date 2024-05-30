# Community Detection Algorithms Comparison

## Overview

This project compares three community detection algorithms: Girvan-Newman, Clique Percolation Method (CPM), and Louvain. The goal is to analyze their performance on a selected network dataset using various evaluation metrics.

## Algorithms

### 1. Girvan-Newman Algorithm
- **Definition:** A divisive hierarchical clustering method that uses edge betweenness to detect communities.
- **Strengths:** Effective for smaller networks.
- **Weaknesses:** Computationally intensive for larger networks.
- **References:** Girvan, M., & Newman, M. E. J. (2002). *Community structure in social and biological networks*.

### 2. Clique Percolation Method (CPM)
- **Definition:** Detects communities by finding k-cliques that share k-1 nodes.
- **Strengths:** Good for overlapping communities.
- **Weaknesses:** Sensitive to the choice of k.
- **References:** Palla, G., Derényi, I., Farkas, I., & Vicsek, T. (2005). *Uncovering the overlapping community structure of complex networks in nature and society*.

### 3. Louvain Algorithm
- **Definition:** An optimization method that maximizes modularity using a multi-level approach.
- **Strengths:** Scales well to large networks.
- **Weaknesses:** May produce different results depending on the initial configuration.
- **References:** Blondel, V. D., Guillaume, J.-L., Lambiotte, R., & Lefebvre, E. (2008). *Fast unfolding of communities in large networks*.

## Steps

### Step 1: Data Collection
1. **Choose a Network Dataset:** Select a dataset suitable for analysis, such as social network data from Twitter or Facebook, or collaboration networks from academic publications.
2. **Dataset Preparation:** Clean and preprocess the dataset, removing any irrelevant or noisy data.

### Step 2: Algorithm Implementation
1. **Girvan-Newman Algorithm:**
   - Implement using a suitable library or from scratch.
   - Calculate edge betweenness and iteratively remove edges with the highest betweenness.
2. **Clique Percolation Method (CPM):**
   - Implement CPM by identifying k-cliques in the network.
   - Use overlapping k-cliques to form communities.
3. **Louvain Algorithm:**
   - Implement the Louvain method or use an existing library.
   - Apply the method to maximize modularity at different levels of the network.

### Step 3: Evaluation Metrics
- **Modularity:** Measures the strength of division of a network into communities.
- **Conductance:** Evaluates the quality of the community structure by comparing the edge boundary of communities.
- **Normalized Mutual Information (NMI):** Compares the similarity of the detected community structures with a ground truth.

### Step 4: Experimental Setup
1. **Network Dataset:** Prepare the selected dataset.
2. **Parameter Tuning:** Determine optimal parameters for each algorithm (e.g., k for CPM).
3. **Run Experiments:** Execute each algorithm on the dataset and collect results.

### Step 5: Analysis and Results
1. **Compare Performance:** Analyze the results based on the chosen evaluation metrics.
2. **Statistical Analysis:** Use statistical methods to determine the significance of the differences observed.
3. **Visualization:** Create visual representations of the community structures detected by each algorithm.

### Step 6: Conclusion and Discussion
1. **Summarize Findings:** Present a summary of the comparative performance of the algorithms.
2. **Discuss Limitations:** Address any limitations in the study and potential improvements.
3. **Future Work:** Suggest directions for future research based on the findings.

## Tools and Libraries
- **NetworkX:** For network analysis and visualization.
- **Scikit-learn:** For additional clustering and validation methods.
- **Matplotlib/Seaborn:** For creating visualizations.
- **Gephi:** For interactive visualization and exploration of networks.

## References
- Girvan, M., & Newman, M. E. J. (2002). *Community structure in social and biological networks*.
- Palla, G., Derényi, I., Farkas, I., & Vicsek, T. (2005). *Uncovering the overlapping community structure of complex networks in nature and society*.
- Blondel, V. D., Guillaume, J.-L., Lambiotte, R., & Lefebvre, E. (2008). *Fast unfolding of communities in large networks*.
