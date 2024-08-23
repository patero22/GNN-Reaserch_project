# Project: Efficient Data Formats for Graph Neural Networks (GNNs)


## Overview

This project aims to thoroughly compare and understand how different sparse matrix formats (COO, CSR, CSC) influence computational efficiency in Graph Neural Networks (GNNs). The focus will be on analyzing three selected GNN models from a list of popular architectures and examining how these models are managed by two widely-used libraries: PyTorch Geometric (PyG) and Deep Graph Library (DGL). Through this project, participants will deepen their knowledge of data handling, computation optimization, and learn the internal mechanisms behind data format conversions in the context of two different programming libraries. The project will enhance understanding of how data formats affect the performance and efficiency of GNN models.


## Goals

### Theoretical Understanding: 
Gain a foundational knowledge of Graph Neural Networks (GNNs) and their relevance.
### Data Format Analysis: 
Study the three most popular data formats used in GNN computations: COO (Coordinate), CSR (Compressed Sparse Row), and CSC (Compressed Sparse Column).
### Performance Evaluation: 
Analyze the impact of data formats on computation performance in PyG and DGL libraries, focusing on three specific GNN models chosen from the following options:
GCN (Graph Convolutional Network)
GraphSAGE
RGCN (Relational Graph Convolutional Network)
GAT (Graph Attention Network)
GIN (Graph Isomorphism Network)
Graph Transformer
### Publication: 
Write a publication that discusses how the choice of data format affects computational efficiency and storage in the PyG and DGL libraries.


## Project Workflow

### Research and Learning:
Study the theoretical aspects of Graph Neural Networks.
Investigate how GNN models are implemented in different data formats (COO, CSR, CSC).
### Data Format Comparison:
Implement and test the three selected GNN models using different sparse matrix formats in both PyG and DGL.
Measure and compare the computational efficiency of the models when using COO, CSR, and CSC formats.
### Analysis and Reporting:
Document the results and analyze how each format impacts the speed, memory usage, and overall performance.
Focus on the differences in data management and storage in PyG vs. DGL.
### Visualization:
Use Python to create detailed visualizations of the data format comparisons, providing graphical insights into performance impacts.
### Final Report:
Compile the findings into a written publication that highlights key observations and conclusions regarding the impact of data formats on GNN efficiency.


## Future Work

Expand the project to include more GNN architectures and additional data formats.
Explore other GNN frameworks and libraries for further comparison.
Optimize memory management for large-scale graph data.



# TL;DR:
This project compares how different sparse matrix formats (COO, CSR, CSC) impact the efficiency of Graph Neural Networks (GNNs) in two libraries: PyTorch Geometric (PyG) and Deep Graph Library (DGL). By focusing on three GNN models, we analyze how data formats affect computational performance.

## Goals
1. Understand GNN basics.
2. Analyze COO, CSR, CSC formats in GNNs.
3. Evaluate format impact on PyG and DGL for selected models: GCN, GraphSAGE, RGCN, GAT, GIN, or Graph Transformer.
4. Write a publication on format performance and data storage efficiency.

## Workflow
1. Research GNN theory and data formats.
2. Compare formats in PyG and DGL for three GNN models.
3. Visualize and analyze performance impacts.
4. Write a report summarizing findings.

## Future Work
1. Expand the project with more GNN models.
2. Expand the project with more data formats.
3. Expand the project with optimization.
