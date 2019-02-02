# MARS

Graphical data representation is an elegant approach to encode relational information and extract effective patterns in large knowledge-base, such as biological and healthcare system, social network as well as security. In the graph analytical system performance, it is paramount important to optimize the performance of the subgraph query processing as it is the basic module of various graph analytics tasks and more importantly it involves the NP-Complete subgraph isomorphism processing. Although, numerous approaches have been proposed in the literature to improve the subgraph query processing, surprisingly, most of the state-of-the-works did not properly address the recurring subgraph query, which is very common in various graph analytical system. Thus the performance of the graph analytical system can substantially be improved by designing a recurring subgraph caching model which minimize the recomputation of graph query in the large graphical data. Therefore, in this work we proposed, MARS: Multi-level balanced caching approach, to improve the subgraph processing and thus enhance the performance of graph analytics.

 In our proposed approach, MARS, self-balancing binary search tree and multi-level hashing have been employed to address the recurring subgraph query problem. We also employed a multi-level structural subgraph query hashing models which store the recurring graph query results in a self-balanced binary search tree to reduce recomputation of subgraph query in the large graph data. Moreover, we also introduce a dynamic balanced graph query caching admission policy to store the recurring query results. In the performance analysis, it has been shown that our proposed approach, MARS, outperforms the state-of-the-art-works by a good margin. The time complexity of MARS is $O(N)$ in the best case scenario compared to VF2 which performs in $O(N*V^2)$ complexity in the best case scenario. In the extensive performance analysis, MARS outperforms the baseline models when tested with 10%,25%,50% and 75% recurring queries.
