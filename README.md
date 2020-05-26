# Neural combinatorial optimization
A peper list for machine learning models solving combinatorial problems, NP-hard problems and graph problems.

## Tag abbreviations
* GAT: Graph Attention Network
* Graph ConvNet: Graph Convolutional Network
* TSP: Traveling Salesman Problem
* PtrNet: Pointer Network
* RL: Reinforcement Learning

# Paper list

## Supervised learning
* Pointer Networks. [NIPS-2015] [[Paper]](https://arxiv.org/pdf/1506.03134.pdf) [[Data]](https://drive.google.com/drive/folders/0B2fg8yPGn2TCMzBtS0o4Q2RJaEU) `PtrNet` `TSP, Convex hulls, Delaunay triangulations` `Autoregressive`

* Discriminative Embeddings of Latent Variable Models for Structured Data [ICML-2016] [[Paper]](https://arxiv.org/pdf/1603.05629.pdf) `Structure2Vect`

* Residual Gated Graph ConvNets. [arXiv-2017] [[Paper]](https://arxiv.org/pdf/1711.07553.pdf) `Graph ConvNet`

* Learning Combinatorial Optimization Algorithms over Graphs. [NIPS-2017] [[Paper]](https://arxiv.org/pdf/1704.01665.pdf) `Structure2Vect` `Graph problems, TSP` `RL`

* Graph Attention Networks [arXiv-2017] [[Paper]](https://arxiv.org/abs/1710.10903) `GAT` `Graph problems`

* Neural Combinatorial Optimization with Reinforcement Learning. [ICLR-2017] [[Paper]](https://arxiv.org/pdf/1611.09940.pdf) `PtrNet` `RL`

* Revised Note on Learning Algorithms for Quadratic Assignment with Graph Neural Networks. [arXiv-2017] [[Paper]](https://arxiv.org/pdf/1706.07450.pdf) `Non-autoregressive`

* Learning heuristics for the tsp by policy gradient [CPAIOR-2018] [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_12) `GAT` `RL` `Autoregressive` `2OPT Local search`

* Graph neural networks: A review of methods and applications [arXiv-2018] [[Paper]](https://arxiv.org/pdf/1812.08434.pdf)

* An Efficient Graph Convolutional Network Technique for the Travelling Salesman Problem. [arXiv-2019] [[Paper]](https://arxiv.org/pdf/1906.01227.pdf) [[Code]](https://github.com/chaitjo/graph-convnet-tsp)
`Graph ConvNet` `TSP` `Non-autoregressive` `Superviced` `Concorde` `Beam search`

* Attention, Learn to Solve Routing Problems! [ICLR-2019] [[Paper]](https://arxiv.org/pdf/1803.08475.pdf) `GAT` `REINFORCE` `Autoregressive` `TSP`

* On Learning Paradigms for the Travelling Salesman Problem [arXiv-2019] [[Paper]](https://arxiv.org/pdf/1910.07210.pdf) `TSP`








## Unsupervised learning


## Solvers
* Concorde [[Site]](http://www.math.uwaterloo.ca/tsp/concorde/)
* LKH3 [[Site]](http://akira.ruc.dk/~keld/research/LKH-3/)
* Gurobi [[Site]](https://www.gurobi.com/resource/traveling-salesman-problem/)

## Datasets
* TSPLIB [[Paper]](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.3.4.376) [[Site]](http://elib.zib.de/pub/mp-testdata/tsp/tsplib/tsplib.html)

## Related papers
* The Graph Neural Network Model [IEEE-2009] [[Paper]](https://ieeexplore.ieee.org/document/4700287) `GNN`
