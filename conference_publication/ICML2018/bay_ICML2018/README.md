# A Fast and Scalable Joint Estimator for Integrating Additional Knowledge in Learning Multiple Related Sparse Gaussian Graphical Models
- **author**: Beilun Wang, Arshdeep Sekhon, Yanjun Qi
- **abstract**: We consider the problem of including additional knowledge in estimating sparse Gaussian graphical models (sGGMs) from aggregated samples, arising often in bioinformatics and neuroimaging applications. Previous joint sGGM estimators either fail to use existing knowledge or cannot scale-up to many tasks (large K) under a high-dimensional (large p) situation. In this paper, we propose a novel \underline{J}oint \underline{E}lementary \underline{E}stimator incorporating additional \underline{K}nowledge (JEEK) to infer multiple related sparse Gaussian Graphical models from large-scale heterogeneous data. Using domain knowledge as weights, we design a novel hybrid norm as the minimization objective to enforce the superposition of two weighted sparsity constraints, one on the shared interactions and the other on the task-specific structural patterns. This enables JEEK to elegantly consider various forms of existing knowledge based on the domain at hand and avoid the need to design knowledge-specific optimization. JEEK is solved through a fast and entry-wise parallelizable solution that largely improves the computational efficiency of the state-of-the-art O(p5K4) to O(p2K4). We conduct a rigorous statistical analysis showing that JEEK achieves the same convergence rate O(log(Kp)/ntot) as the state-of-the-art estimators that are much harder to compute. Empirically, on multiple synthetic datasets and one real-world data from neuroscience, JEEP outperforms the speed of the state-of-arts significantly while achieving the same level of prediction accuracy.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](http://proceedings.mlr.press/v80/wang18f/wang18f.pdf)
- **code**: [code](https://github.com/QData/jeek)
- **dataset**: ABIDE,  Gaussian datasets, Real-World Genomics Data
- **ppt/video**:
- **curator**: Mengya Ji