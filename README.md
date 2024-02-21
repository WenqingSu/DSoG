# Spectral co-Clustering in Multi-layer Stochastic co-Block Models
This repository contains the main functions to run simulations and analysis for the paper "Spectral co-Clustering in Rank-deﬁcient Multi-layer Stochastic co-Block Models" by Su et al. (see [Su et al.(2023)](https://arxiv.org/abs/2307.10572)). The spectral co-clustering algorithm based on the debiased sum of Gram matrices denoted as DSoG in this paper.

# Python Code
The file [simulation.ipynb](simulation.ipynb) contains an example of DSoG for co-clustering in multi-layer ScBMs. The file [real_data_analysis.ipynb](real_data_analysis.ipynb) contains an real-world application of the DSoG method to the Worldwide Food and Agricultural Trade dataset. The raw data used in this article can be found at [https://www.fao.org/faostat/en/#data/TM](https://www.fao.org/faostat/en/#data/TM). It can be transformed to a multi-layer network, where layers represent food and agricultural products, and nodes are countries and edges at each layer represent import/export relationships of a speciﬁc food and agricultural product among countries. Researchers interested in the  multi-layer network themselves directly can contact Wenqing Su.

# References
Su, Wenqing, Xiao Guo, Xiangyu Chang, and Ying Yang. "Spectral co-Clustering in Rank-deficient Multi-layer Stochastic co-Block Models." arXiv preprint arXiv:2307.10572 (2023).

