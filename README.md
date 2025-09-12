# COLLECTIVE BEHAVIOR-DRIVEN ASYMPTOTICALLY STABLE GRAPH NEURAL NETWORKS: A LIGHTWEIGHT NODE CLASSIFICATION MODEL

## Introduction

Graph Neural Networks suffer from a severe oversmoothing problem in deep network architectures. Oversmoothing is analogous to individual collisions in collective behavior, which arise due to the lack of multi-agent interaction rules. Inspired by the three core collision-avoidance  in natural collective behavior, this paper proposes an (A)lignment-(C)ohesion-(S)eparation (G)raph Neural Network (ACSG), which is designed to fundamentally alleviate the oversmoothing problem. Specifically, ACSG constructs an asymptotically stable dynamic system by emulating three principles—individual operating environment (Alignment), multi-level collective leadership (Cohesion), and individual operating state (Separation)—thereby effectively alleviating the oversmoothing problem. Theoretically, we are the first to prove that collective behavior-driven GNN dynamic systems possess asymptotic stability, ensuring that node features converge to a globally optimal equilibrium state. Experiments conducted on several real-world homophilic and heterophilic graph datasets demonstrate that ACSG achieves state-of-the-art performance, exhibits the lowest boundary ambiguity, and maintains a lightweight architecture. This study provides a new paradigm for addressing the oversmoothing challenge in GNNs.

### Experiments
For example to run for Cora with random splits:
```
cd src
python run_GNN.py --dataset Cora
```

## Comments 

- Our codebase for the graph diffusion models builds heavily on [Graph neural PDE](https://github.com/twitter-research/graph-neural-pde). Thanks for open-sourcing!
