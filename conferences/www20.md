# Knowledge Graphs at The Web Conference 2020 (WWW'20)

Knowledge graph is a hot topic in the Web Conference 2020, with tasks of entity alignment, relation extraction, knowledge graph completion and refinement intensively studied. 
This paper list briefs those nice works. 

Some interesting findings: 

1) Many papers propose methods exploiting rich information such as [multi-type entities and neighborhood information](https://dl.acm.org/doi/abs/10.1145/3366423.3380289), [structural information and correlation](https://dl.acm.org/doi/abs/10.1145/3366423.3380257) and [user-item interaction](https://dl.acm.org/doi/abs/10.1145/3366423.3380155);

2) Low resource settings are paid great attention, for example, relation extraction by [Zhou et al.](https://dl.acm.org/doi/abs/10.1145/3366423.3380282), [MetaNER](https://dl.acm.org/doi/abs/10.1145/3366423.3380127) and [KGC with adversarial network](https://dl.acm.org/doi/abs/10.1145/3366423.3380089);

3) Rule mining is also an interesting direction, with papers like [NERO](https://dl.acm.org/doi/abs/10.1145/3366423.3380282) and [KGist](https://dl.acm.org/doi/abs/10.1145/3366423.3380189);

4) Graph neural networks and adversarial learning are definitely among the most popular topics, such as [[He et al.]](https://dl.acm.org/doi/abs/10.1145/3366423.3380155) and [[Cao et al.]](https://arxiv.org/pdf/2002.06397.pdf).

Last but not least, there are a paper on [storage architecture](https://dl.acm.org/doi/abs/10.1145/3366423.3380246), a resource article of [event knowledge graph](https://dl.acm.org/doi/abs/10.1145/3366423.3380107), and three downstream applications of [recommendation](https://dl.acm.org/doi/abs/10.1145/3366423.3380098), [QA](https://dl.acm.org/doi/abs/10.1145/3366423.3380197), and [keyword search](https://dl.acm.org/doi/abs/10.1145/3366423.3380110).

_Ads.: Know more about knowledge graphs, please check out our recent survey entitled [A Survey on Knowledge Graphs: Representation, Acquisition and Applications](https://arxiv.org/pdf/2002.00388)!_

## Entity Alignment
__Collective Multi-type Entity Alignment Between Knowledge Graphs__
WWW 2020. _Zhu et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380289)]
> Motivation: the sparsity of different knowledge graphs and alignment of multi-type entities 
> jointly aligns multiple types of entities, collectively leverages the neighborhood information and generalizes to unlabeled entity types

## Entity Discovery
__MetaNER: Named Entity Recognition with Meta-Learning__
WWW 2020. _Li et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380127)]
> Meta-learning approach for domain adaptation in NER

__Novel Entity Discovery from Web Tables__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380205)]
> leverage the content in such tables to discover new entities, properties, and relationships


## Entity Linking
__High Quality Candidate Generation and Sequential Graph Attention Network for Entity Linking__
WWW 2020. _Fang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380146)]
> considering the differences between candidate entities, promote the quality of candidates; utilize the topical coherence among the referred entities, distinguish candidate entities, capture the relevance between the current mention and its subsequent entities

__Dynamic Graph Convolutional Networks for Entity Linking__
WWW 2020. _Wu et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380192)]
> Motivation: structured graph for a set of entities depends on the contextual information of the given document and adaptively changes on different aggregation layers of GCN
> Dynamic GCN

## Relation Extraction
__NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction__
WWW 2020. _Zhou et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380282)]
> neural soft rule matching

__LOREM: Language-consistent Open Relation Extraction from Unstructured Text__. 
WWW 2020. _Harting et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380252)]
> Language-consistent multi-lingual Open Relation Extraction Model

## KGC
__Beyond Triplets: Hyper-Relational Knowledge Graph Embedding for Link Prediction__
WWW 2020. _Rosso et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380257)]
> captures not only the primary structural information of the KG encoded in the triplets, but also the correlation between each triplet and its associated key-value pairs.

__Generalizing Tensor Decomposition for N-ary Relational Knowledge Bases__
WWW 2020. _Liu et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380188)]
> generalize tensor decomposition for n-ary relational KBs


__Relation Adversarial Network for Low Resource Knowledge Graph Completion__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380089)] 
> low resource relations + adversarial network 
> Adversarial transfer learning: weighted relation adversarial network; learn relation-invariant features more transferable from source relations to target relations; relation-gated mechanism fully relaxes the shared label space assumptions


__Mining Implicit Entity Preference from User-Item Interaction Data for Knowledge Graph Completion via Adversarial Learning__
WWW 2020. _He et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380155)]
> leverage rick user-item interaction data
> adversarial learning, collaborative learning, graph neural networks

__Open Knowledge Enrichment for Long-tail Entities__.
WWW 2020. _Cao et al._. 
[[Paper](https://arxiv.org/pdf/2002.06397.pdf)] [[Code](https://github.com/nju-websoft/OKELE/)]
> OKELE, enrich long-tail entities from the open Web, that is search the Web to find a set of true facts of a given long-tail entity; 
> three steps: property prediction, value extraction, fact verification
> open knowledge enrichment on long-tail entities; GNN and graph attention; fact verification model based on a  PGM with conjugate priors; 

## KG Refinement 
__What is Normal, What is Strange, and What is Missing in a Knowledge Graph: Unified Characterization via Inductive Summarization__
WWW 2020. _Belth et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380189)]
> KGist, Knowledge Graph Inductive SummarizaTion
> learns a summary of inductive rules that best compress the KG according to the Minimum Description Length principle—a formulation that we are the first to use in the context of KG rule mining.


__Correcting Knowledge Base Assertions__.
WWW 2020. _Chen et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380226)]
> correction framework combines lexical matching, semantic embedding, soft constraint mining and semantic consistency checking.


__Expanding Taxonomies with Implicit Edge Semantics__
WWW 2020. _Manzoor et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380271)]
> taxonomies with heterogeneous edge semantics unobserved

## Storage Architecture 
__Adaptive Low-level Storage of Very Large Knowledge Graphs__.
WWW 2020. _Urbani et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380246)]
> a novel storage structure for very large KGs on centralized systems


## Dataset
__ASER: A Large-scale Eventuality Knowledge Graph__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380107)]
> ASER (activities, states, events, and their relations), a large-scale eventuality knowledge graph extracted from more than 11-billion-token unstructured textual data. 


## Recommendation
__Reinforced Negative Sampling over Knowledge Graph for Recommendation__
WWW 2020. _Wang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380098)]
> a reinforcement learning agent to explore high-quality negatives
> Motivation: item knowledge graph for inferring informative and factual negative samples
> Knowledge Graph Policy Network (KGPolicy): reinforcement learning agent to explore high-quality negatives; matrix factorization 


## KGQA
__Complex Factoid Question Answering with a Free-Text Knowledge Graph__ 
WWW 2020. _Zhao et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380197)]


## Keyword Search
__Keyword Search over Knowledge Graphs via Static and Dynamic Hub Labelings__
WWW 2020. _Shi et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380110)]