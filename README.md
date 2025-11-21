# Towards Asymptotically Stable: Lightweight GNNs: Against Over-smoothing

## Introduction

Graph Neural Networks (GNNs) suffer from severe over-smoothing as network depth increases, a phenomenon analogous to collision-like convergence in collective motion when multi-agent interaction rules are absent. Inspired by the three core principles of collision avoidance, we propose ACSG, a GNN framework that fundamentally mitigates over-smoothing by embedding collective-motion interaction mechanisms into the feature evolution process. ACSG first constructs a stable feature evolution domain through class-space anchoring, then strengthens the aggregation of homophilic nodes via hierarchical topology enhancement, and finally preserves feature distinctiveness through dynamic velocity equilibrium. Together, these components endow GNNs with interpretable multi-agent interaction rules that effectively prevent feature collapse in deep architectures. Theoretically, we provide the first proof that swarm-driven GNNs dynamical systems possess asymptotic stability. We further introduce swarm-inspired metrics to quantify boundary ambiguity and order formation during the evolution of representation. Experimental results on multiple real-world homophilic and heterophilic benchmarks demonstrate that ACSG achieves state-of-the-art performance while maintaining a lightweight model footprint. Our implementation is publicly available at: https://github.com/123ao69/ACSG.

### Experiments
For example to run for Cora with random splits:
```
cd src
python run_GNN.py --dataset Cora
```

## Comments 

- Our codebase for the graph diffusion models builds heavily on [Graph neural PDE](https://github.com/twitter-research/graph-neural-pde). Thanks for open-sourcing!
