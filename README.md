# Machine Learning with Graphs

Solutions to the assignments of the course __CS224W: Machine Learning with Graphs__ offered by Stanford University. The Winter-2021 offering of this class was chosen, as the assignments had more content.

The assignments consist of 6 Colab Notebooks, each aiming to teach a different topic. Specifically:

- [Colab 0](CS224W_Colab_0.ipynb): Introduction to the [NetworkX](https://networkx.org/) and [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/) python packages and a small application on the [KarateClub](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.KarateClub) dataset.

- [Colab 1](CS224W_Colab_1.ipynb): Training a vanilla Neural Network to learn the node embeddings of the [KarateClub](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.KarateClub) dataset.

- [Colab 2](CS224W_Colab_2.ipynb): A more in depth application of [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/) for node and graph classification on the OGB ([Open Graph Benchmark](https://ogb.stanford.edu/)) [arxiv](https://ogb.stanford.edu/docs/nodeprop/#ogbn-arxiv) and [molhiv](https://ogb.stanford.edu/docs/graphprop/#ogbg-mol) datasets respectively, using GCN (Graph Convolution Networks).

- [Colab 3](CS224W_Colab_3.ipynb): An even deeper application of [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/) for node classification on the [Cora](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.Planetoid) dataset with the GraphSAGE and GAT (Graph Attention Network) models. Furthermode, a short introduction to [DeepSnap](https://github.com/snap-stanford/deepsnap) library is made, as well as a small application for edge prediction on the [Cora](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.Planetoid) dataset.

- [Colab 4](CS224W_Colab_4.ipynb): Some [DeepSnap](https://github.com/snap-stanford/deepsnap) functionalities for [Heterogeneous Graphs](https://snap.stanford.edu/deepsnap/modules/hetero_graph.html#deepsnap.hetero_graph.HeteroGraph), and an implementations of Heterogeneous GNN Convolutional/Attention models for node property prediction on the [ACM(3025)](https://arxiv.org/pdf/1903.07293.pdf) dataset.

- [Colab 5](CS224W_Colab_5.ipynb): A small introduction to [Neighbor Sampling](https://pytorch-geometric.readthedocs.io/en/1.6.1/modules/data.html#torch_geometric.data.NeighborSampler) with various ratios and [Subgraph (Cluster) Sampling](https://arxiv.org/abs/1905.07953).

## Resources

The resources that were used for the completion of the assignments are:

1. Online lectures of the course, available on [youtube](https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn).
2. The corresponding slides, available in the [course website](http://snap.stanford.edu/class/cs224w-2020/).