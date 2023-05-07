---
title: "Deep-Steiner: Learning to Solve the Euclidean Steiner Tree Problem"
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-27041-3_16'
---

Siqi Wang, Yifan Wang, Guangmo Tong

EAI WiCON

The Euclidean Steiner tree problem seeks the min-cost network to connect a collection of target locations, and it underlies many applications of wireless networks. In this paper, we present a study on solving the Euclidean Steiner tree problem using reinforcement learning enhanced by graph representation learning. Different from the commonly studied connectivity problems like travelling salesman problem or vehicle routing problem where the search space is finite, the Euclidean Steiner tree problem requires to search over the entire Euclidean space, thereby making the existing methods not applicable. In this paper, we design discretization methods by leveraging the unique characteristics of the Steiner tree, and propose new training schemes for handling the dynamic Steiner points emerging during the incremental construction. Our design is examined through a sanity check using experiments on a collection of datasets, with encouraging results demonstrating the utility of our method as an alternative to classic combinatorial methods.

[pdf](https://arxiv.org/abs/2209.09983) [code](https://github.com/cdslabamotong/stratLearner)
