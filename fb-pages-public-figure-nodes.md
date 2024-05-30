# Facebook Pages Public Figure Dataset

## Overview
This dataset contains information about public figure pages on Facebook. It includes two main files: `.nodes` and `.edges`, which represent the nodes and edges of a network graph, respectively. This document describes the structure and content of the `.nodes` file.

## Nodes File (`fb-pages-public-figure.nodes`)

### Description
The `.nodes` file contains information about individual nodes in the network, representing public figure pages on Facebook. Each row in the file corresponds to a single node and includes the following columns:

1. **Node ID**: A unique identifier for each public figure page.
2. **Node Name**: The name associated with the public figure page.
3. **Attribute**: An additional attribute of the node, which can represent various metrics (e.g., follower count, page rank).

### File Format
The file is a text file with space-separated values (SSV). Each row after the first row represents a node with its associated data.

### Columns
- **Node ID (Column 0)**: An integer or numerical identifier for the public figure page.
- **Node Name (Column 1)**: The name of the public figure associated with the page.
- **Attribute (Column 2)**: A numerical value representing an additional attribute of the node, such as follower count.

### Example Rows
Here are the first few rows of the `.nodes` file to illustrate its structure:
116999698310182 Mike Rowe 8980

1173678312659310 Louis Ng Kok Kwang 2230

466981723395173 Pastor Everaldo 7510

251453648389404 Ronen Manelis דובר צה"ל רונן מנליס 2708

1596076743971510 QPark 7349


### Potential Uses
The data in the `.nodes` file can be used for various analyses, including but not limited to:
- Identifying key public figures based on their attributes.
- Analyzing the distribution of followers or other metrics across different public figures.
- Preparing the data for community detection algorithms to find groups of closely connected public figures.

## Edges File
A description of the `.edges` file will follow in a similar format, detailing the connections between the nodes.

## Citation
If you use this dataset, please cite the following paper:
