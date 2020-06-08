# Neural combinatorial optimization
A peper list for machine learning models solving combinatorial problems, NP-hard problems and graph problems.

## Tag abbreviations
* GAT: Graph Attention Networks
* GNN: Graph Neural Networks
* Graph ConvNet: Graph Convolutional Network
* NMT: Neural Machine Translation
* Seq2Seq: Sequence to Sequences model
* TSP: Traveling Salesman Problem
* PtrNet: Pointer Network
* RL: Reinforcement Learning


# Paper list

## Supervised learning

* Pointer Networks. [[Vinyals | NIPS | 2015]](https://arxiv.org/pdf/1506.03134.pdf) [[Data]](https://drive.google.com/drive/folders/0B2fg8yPGn2TCMzBtS0o4Q2RJaEU)
    
    `PtrNet` `Autoregressive` `TSP` `Convex hulls` `Delaunay triangulations` 

* Discriminative Embeddings of Latent Variable Models for Structured Data. [[ICML | 2016]](https://arxiv.org/pdf/1603.05629.pdf)
    
    `Structure2Vect`

* Residual Gated Graph ConvNets. [[Bresson and Laurent | arXiv | 2017]](https://arxiv.org/pdf/1711.07553.pdf)
    
    `Graph ConvNet` `Graph problems`

* Learning Combinatorial Optimization Algorithms over Graphs. [[Dai et al. | NIPS | 2017]](https://arxiv.org/pdf/1704.01665.pdf) 
    
    `Structure2Vect` `Graph problems, TSP` `RL`

* Graph Attention Networks. [[arXiv-2017]] [[Paper]](https://arxiv.org/abs/1710.10903)
    
    `GAT` `Graph problems`

* Neural Combinatorial Optimization with Reinforcement Learning. [[Bello et al. | ICLR | 2017]](https://arxiv.org/pdf/1611.09940.pdf)
    
    `PtrNet` `RL`

* Revised Note on Learning Algorithms for Quadratic Assignment with Graph Neural Networks. [[arXiv | 2017]] (https://arxiv.org/pdf/1706.07450.pdf)
    
    `Non-autoregressive`

* Data-Driven Approximations to NP-Hard Problems [[Milan et al. | AAAI | 2017]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14700/13936)

    `PtrNet` `Data-driven` `TSP`

* Boosting Dynamic Programming with Neural Networks for Solving NP-hard Problems. [[Yang et al. | ACML | 2018]](http://proceedings.mlr.press/v95/yang18a/yang18a.pdf)

    `Dynamic programming` `TSP`

* Applying deep learning and reinforcement learning to traveling salesman problem [[Miki et al. | iCCECE | 2018]](https://ieeexplore.ieee.org/document/8659266)

* Learning heuristics for the tsp by policy gradient [[CPAIOR | 2018]](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_12)
    
    `GAT` `RL` `Autoregressive` `2OPT Local search`

* Graph neural networks: A review of methods and applications [[arXiv | 2018]](https://arxiv.org/pdf/1812.08434.pdf)

* An Efficient Graph Convolutional Network Technique for the Travelling Salesman Problem. [[Joshi et al. | arXiv | 2019]](https://arxiv.org/pdf/1906.01227.pdf) [[Code]](https://github.com/chaitjo/graph-convnet-tsp)
    
    `Graph ConvNet` `TSP` `Non-autoregressive` `Superviced` `Concorde` `Beam search`

* Attention, Learn to Solve Routing Problems! [[ICLR | 2019]](https://arxiv.org/pdf/1803.08475.pdf)
    
    `GAT` `REINFORCE` `Autoregressive` `TSP`

* On Learning Paradigms for the Travelling Salesman Problem [[arXiv | 2019]](https://arxiv.org/pdf/1910.07210.pdf)
    
    `TSP`

* Solving Traveling Salesman Problem with Image-based Classification [[Miki and Ebara | ICTAI | 2019]](https://ieeexplore.ieee.org/document/8995285)
    `Pixel-mapped Classification Network` `CNN` `TSP`



## Unsupervised learning

## Related papers

* The Graph Neural Network Model [[Scarselli et al. |IEEE | 2009]](https://ieeexplore.ieee.org/document/4700287) 
    
    `GNN`

* Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation [[Cho et al. | EMNLP | 2014]](https://arxiv.org/pdf/1406.1078.pdf)

    `Seq2Seq` `NMT`

* Sequence to Sequence Learning with Neural Networks [[Sutskever et al. | NIPS   2014]](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)

    `Seq2Seq` `NMT`
    
* Effective Approaches to Attention-based Neural Machine Translation. [[Luong et al. | EMNLP | 2015]](https://arxiv.org/pdf/1508.04025.pdf)

    `Seq2Seq` `Attention` `NMT`

* Neural Machine Translation by Jointly Learning to Align and Translate [[Bahdanau et al. | ICLR | 2015]](https://arxiv.org/pdf/1409.0473.pdf)

    `Seq2Seq` `Attention` `NMT`




## Solvers
* Concorde [[Site]](http://www.math.uwaterloo.ca/tsp/concorde/)
* LKH3 [[Site]](http://akira.ruc.dk/~keld/research/LKH-3/)
* Gurobi [[Site]](https://www.gurobi.com/resource/traveling-salesman-problem/)


## Datasets
* TSPLIB [[Paper]](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.3.4.376) [[Site]](http://elib.zib.de/pub/mp-testdata/tsp/tsplib/tsplib.html)


