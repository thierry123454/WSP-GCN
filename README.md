# Weighted Shortest Path Graph Convolutional Networks (WSP-GCNs)

This repository contains the implementation of Weighted Shortest Path Graph Convolutional Networks (WSP-GCNs), designed to address common challenges in Graph Convolutional Networks (GCNs), including over-smoothing and over-squashing.

## Overview

GCNs are widely used for graph-structured data but struggle with information propagation bottlenecks in deep architectures. WSP-GCNs introduce weighted multi-hop shortest path neighborhood aggregation to balance local and long-range information flow. Key features include:
- Learnable Multi-Hop Weights: Dynamically balance contributions from different hop neighborhoods.
- Residual Connections: Optional fixed or learnable residual scaling to mitigate over-smoothing.
- Visualization: Track weight evolution and residual scale dynamics during training.

## Features
- Implementation of WSP-GCNs with configurable parameters:
  -	Number of hops
  - Residual connections (fixed or learnable)
  - Customizable weight initialization and noise addition
- Experiments on the Cora dataset, comparing WSP-GCNs with baseline GCNs and state-of-the-art techniques.
- Scripts for metrics computation, including accuracy and silhouette scores.
- Visualizations for weight dynamics and embedding separability.
