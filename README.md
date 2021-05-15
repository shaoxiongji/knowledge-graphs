# Knowledge Graphs
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub issues](https://img.shields.io/github/issues/shaoxiongji/knowledge-graphs)](https://github.com/shaoxiongji/knowledge-graphs/issues)
[![GitHub forks](https://img.shields.io/github/forks/shaoxiongji/knowledge-graphs)](https://github.com/shaoxiongji/knowledge-graphs/network)
[![GitHub stars](https://img.shields.io/github/stars/shaoxiongji/knowledge-graphs)](https://github.com/shaoxiongji/knowledge-graphs/stargazers)
[![Twitter](https://img.shields.io/twitter/url?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fshaoxiongji%2Fknowledge-graphs)

A collection of knowledge graph papers, codes, and reading notes.

- [Knowledge Graphs](#knowledge-graphs)
  - [Survey](#survey)
  - [Papers by venues](#papers-by-venues)
  - [Papers by categories](#papers-by-categories)
  - [Data](#data)
    - [General Knowledge Graphs](#general-knowledge-graphs)
    - [Domain-specific Data](#domain-specific-data)
    - [Entity Recognition](#entity-recognition)
    - [Other Collections](#other-collections)
  - [Libraries, Softwares and Tools](#libraries-softwares-and-tools)
    - [KRL Libraries](#krl-libraries)
    - [Knowledge Graph Database](#knowledge-graph-database)
    - [Others](#others)
    - [Interactive APP](#interactive-app)
  - [Courses, Tutorials and Seminars](#courses-tutorials-and-seminars)
    - [Courses](#courses)
  - [Related Repos](#related-repos)
  - [Acknowledgements](#acknowledgements)


## Survey
__A Survey on Knowledge Graphs: Representation, Acquisition and Applications__. IEEE TNNLS 2021. _Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu_. [[Paper](https://arxiv.org/pdf/2002.00388)] 

__Knowledge Graphs__. Preprint 2020. _Aidan Hogan, Eva Blomqvist, Michael Cochez, Claudia d'Amato, Gerard de Melo, Claudio Gutierrez, José Emilio Labra Gayo, Sabrina Kirrane, Sebastian Neumaier, Axel Polleres, Roberto Navigli, Axel-Cyrille Ngonga Ngomo, Sabbir M. Rashid, Anisa Rula, Lukas Schmelzeisen, Juan Sequeda, Steffen Staab, Antoine Zimmermann_. [[Paper](https://arxiv.org/abs/2003.02320)] 

__Knowledge Representation Learning: A Quantitative Review__. Preprint 2018. _Lin, Yankai and Han, Xu and Xie, Ruobing and Liu, Zhiyuan and Sun, Maosong_. [[Paper](https://arxiv.org/pdf/1812.10901)]

__Knowledge graph embedding: A survey of approaches and applications__. TKDE 2017. _Wang, Quan and Mao, Zhendong and Wang, Bin and Guo, Li_. [[Paper](https://persagen.com/files/misc/Wang2017Knowledge.pdf)]

__Knowledge graph refinement: A survey of approaches and evaluation methods__. Semantic Web 2017. _Paulheim, Heiko_. [[Paper](http://www.semantic-web-journal.net/system/files/swj1167.pdf)]

__A review of relational machine learning for knowledge graphs__. Proceedings of the IEEE 2015. _Nickel, Maximilian and Murphy, Kevin and Tresp, Volker and Gabrilovich, Evgeniy_. [[Paper](https://arxiv.org/pdf/1503.00759)]

## Papers by venues
| Year      | WWW                           | AAAI                            |  ACL  | 
| --------  | --------                      | --------                        |  --------                        |              
| 2020      | [20](./conferences/www20.md)  | [28](./conferences/aaai20.md)   |  [53](./conferences/acl20.md)    |

## Papers by categories
- [Knowledge Graph Embedding](./papers/KG-embedding.md)
- [Cross-Modal KG Embedding](./papers/KG-cross-modal.md)
- Knowledge Acquisition
  - [Knowledge Graph Completion](./papers/KG-KGC.md)
  - [Relation Extraction](./papers/KG-RE.md)
  - [Entity Discovery](./papers/KG-entity.md)
- Knowledge-aware Applications
  - [Natural Language Understanding](./papers/KG-applications.md#natural-langauge-understanding)
  - [Commonsense Knowledge](./papers/KG-applications.md#commonsense-knowledge)
  - [Question Answering](./papers/KG-applications.md#question-answering)
  - [Dialogue Systems](./papers/KG-applications.md#dialogue-systems)
  - [Recommendation Systems](./papers/KG-applications.md#recommendation-systems)
  - [Information Retrieval](./papers/KG-applications.md#information-retrieval)
- [Temporal Knowledge Graph](./papers/KG-temporal.md)
- [Knowledge Graph Reasoning](./papers/KG-reasoning.md)
- [One/few-Shot and Zero-Shot Learning](./papers/KG-few-shot.md)
- [Domain-specific Knowledge Graphs](./papers/KG-domain.md)
- [KG Database Systems](./papers/KG-database.md)

## Data
### General Knowledge Graphs
- WordNet, https://wordnet.princeton.edu
- OpenCyc, https://www.cyc.com/opencyc/
- Cyc, https://www.cyc.com
- YAGO, http://www.mpii.mpg.de/∼suchanek/yago
- DBpedia, https://wiki.dbpedia.org/develop/datasets
- Freebase, https://developers.google.com/freebase/
- NELL, http://rtw.ml.cmu.edu/rtw/
- Wikidata, https://www.wikidata.org/wiki
- Probase IsA, https://concept.research.microsoft.com/Home/Download
- Google KG, https://developers.google.com/knowledge-graph
- A large-scale Chinese knowledge graph from [OwnThink](https://github.com/ownthink/KnowledgeGraph)
- GDELT（Global Database of Events, Language, and Tone）[Web](https://www.gdeltproject.org)

### Domain-specific Data
__OpenKG knowledge graphs about the novel coronavirus COVID-19__
- 新冠百科图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-baike)] Knowledge graph from encyclopedia[[Link](http://www.openkg.cn/dataset/2019-ncov-baike)]

- 新冠科研图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-research)] Knowledge graph of COVID-19 research [[Link](http://www.openkg.cn/dataset/2019-ncov-research)]

- 新冠临床图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-clinic)] Clinical knowledge graph [[Link](http://www.openkg.cn/dataset/2019-ncov-clinic)]

- 新冠英雄图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-hero)] Knowledge graph of people, experts, and heroes [[Link](http://www.openkg.cn/dataset/2019-ncov-hero)]

- 新冠热点事件图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-event)] Knowledge graph of public events [[Link](http://www.openkg.cn/dataset/2019-ncov-event)]

__COVID❋GRAPH  COVID-19 virus__
[[Web](http://www.odbms.org/2020/03/we-build-a-knowledge-graph-on-covid-19/)]

__KgBase COVID-19 knowledge graph__ [[Web](https://covid19.kgbase.com)]
__Academic graphs__
- OAG, Open Academic Graph, https://www.aminer.cn/open-academic-graph

### Entity Recognition
CORD-19, a comprehensieve named entity annotation dataset, CORD-NER, on the COVID-19 Open Research Dataset Challenge (CORD-19) corpus [[Data](https://xuanwang91.github.io/2020-03-20-cord19-ner/)]

### Other Collections
Baidu BROAD datasets [[Web](https://ai.baidu.com/broad/introduction)]

__ASER: A Large-scale Eventuality Knowledge Graph__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380107)]


## Libraries, Softwares and Tools
### KRL Libraries
[Grakn](https://github.com/graknlabs/kglib), Grakn Knowledge Graph Library (ML R&D) https://grakn.ai

[AmpliGraph](https://github.com/Accenture/AmpliGraph), Python library for Representation Learning on Knowledge Graphs https://docs.ampligraph.org

[OpenKE](https://github.com/thunlp/OpenKE), An Open-Source Package for Knowledge Embedding (KE)

[Fast-TransX](https://github.com/thunlp/Fast-TransX), An Efficient implementation of TransE and its extended models for Knowledge Representation Learning

[scikit-kge](https://github.com/mnick/scikit-kge), Python library to compute knowledge graph embeddings

[OpenNRE](https://github.com/thunlp/OpenNRE), An Open-Source Package for Neural Relation Extraction (NRE)

### Knowledge Graph Database
[akutan](https://github.com/eBay/akutan), A distributed knowledge graph store

### Others
- [OpenNRE](https://github.com/thunlp/OpenNRE)

### Interactive APP
Knowledge graph APP, Simple knowledge graph applications can be easily built using JSON data managed entirely via a GraphQL layer. [[Github](https://github.com/epistemik-co/staple-api-kg-demo)] [[Website](http://demo.staple-api.org)]

## Courses, Tutorials and Seminars
### Courses
- Stanford CS 520 Knowledge Graphs: How should AI explicitly represent knowledge? _Vinay K. Chaudhri, Naren Chittar, Michael Genesereth_. [[Web](https://web.stanford.edu/class/cs520/)]
- Stanford CS 224W: Machine Learning with Graphs. _Jure Leskovec_. [[Web](http://web.stanford.edu/class/cs224w/index.html)]
- University of Bonn: Analysis of Knowledge Graphs. _Jens Lehmmann_. [[Web](https://sewiki.iai.uni-bonn.de/teaching/lectures/kga/2017/start)] [[GitHub](https://github.com/SmartDataAnalytics/Knowledge-Graph-Analysis-Programming-Exercises)]
- Knowledge Graphs. _Harald Sack, Mehwish Alam_. [[Web](https://open.hpi.de/courses/knowledgegraphs2020)]


## Related Repos
A repo about knowledge graph in Chinese - [husthuke/awesome-knowledge-graph](https://github.com/husthuke/awesome-knowledge-graph)

A repo about NLP, KG, Dialogue Systems in Chinese - [lihanghang/NLP-Knowledge-Graph](https://github.com/lihanghang/NLP-Knowledge-Graph)

Top-level Conference Publications on Knowledge Graph - [wds-seu/Knowledge-Graph-Publications](https://github.com/wds-seu/Knowledge-Graph-Publications)

Geospatial Knowledge Graphs - [semantic-geospatial](https://github.com/laurentlefort/semantic-geospatial/wiki/Geospatial-Knowledge-Graphs)

## Acknowledgements

Acknowledgments give to the following people who comment or contribute to this repository (listed chronologically).

- [DonaldTsang](https://github.com/DonaldTsang)
- [NYXFLOWER](https://github.com/NYXFLOWER)
- [Arun-George-Zachariah](https://github.com/Arun-George-Zachariah)  

__[⬆](#awesome-knowledge-graph)__
