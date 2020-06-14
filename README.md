# Awesome Knowledge Graph
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of knowledge graph papers, codes, and reading notes.

- [Awesome Knowledge Graph](#awesome-knowledge-graph)
  - [Survey](#survey)
  - [Papers by venues](#papers-by-venues)
  - [Knowledge Graph Embedding](#knowledge-graph-embedding)
  - [Cross-Modal KG Embedding](#cross-modal-kg-embedding)
    - [Textual Description](#textual-description)
    - [Type Information](#type-information)
    - [Logic Rules](#logic-rules)
    - [Relational Path](#relational-path)
    - [Visual Information](#visual-information)
  - [Knowledge Acquisition](#knowledge-acquisition)
    - [Knowledge Graph Completion](#knowledge-graph-completion)
    - [Knowledge Graph Refinement](#knowledge-graph-refinement)
    - [Relation Extraction](#relation-extraction)
    - [Relation Classification](#relation-classification)
    - [Entity Recognition](#entity-recognition)
    - [Entity Alignment](#entity-alignment)
    - [Entity Disambiguation](#entity-disambiguation)
    - [Entity Typing](#entity-typing)
  - [Knowledge-aware Applications](#knowledge-aware-applications)
    - [Natural Language Understanding](#natural-language-understanding)
    - [Commonsense Knowledge](#commonsense-knowledge)
    - [Question Answering](#question-answering)
    - [Dialogue Systems](#dialogue-systems)
    - [Recommendation System](#recommendation-system)
    - [Information Retrieval](#information-retrieval)
    - [Healthcare](#healthcare)
    - [Software Engineering](#software-engineering)
    - [Computer Vision](#computer-vision)
    - [Other Applications](#other-applications)
  - [Temporal Knowledge Graph](#temporal-knowledge-graph)
  - [Knowledge Graph Reasoning](#knowledge-graph-reasoning)
  - [One/few-Shot and Zero-Shot Learning](#onefew-shot-and-zero-shot-learning)
  - [Domain-specific Knowledge Graphs](#domain-specific-knowledge-graphs)
    - [Geospatial Knowledge Graphs](#geospatial-knowledge-graphs)
  - [KG Database Systems](#kg-database-systems)
  - [Data](#data)
    - [General Knowledge Graphs](#general-knowledge-graphs)
    - [Domain-specific Data](#domain-specific-data)
    - [Entity Recognition](#entity-recognition-1)
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
__A Survey on Knowledge Graphs: Representation, Acquisition and Applications__. Preprint 2020. _Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu_. [[Paper](https://arxiv.org/pdf/2002.00388)] [[专知](https://mp.weixin.qq.com/s/0f5E82utl-faCpmvrDoPEg)]

__Knowledge Graphs__. Preprint 2020. _Aidan Hogan, Eva Blomqvist, Michael Cochez, Claudia d'Amato, Gerard de Melo, Claudio Gutierrez, José Emilio Labra Gayo, Sabrina Kirrane, Sebastian Neumaier, Axel Polleres, Roberto Navigli, Axel-Cyrille Ngonga Ngomo, Sabbir M. Rashid, Anisa Rula, Lukas Schmelzeisen, Juan Sequeda, Steffen Staab, Antoine Zimmermann_. [[Paper](https://arxiv.org/abs/2003.02320)] [[专知](https://mp.weixin.qq.com/s/X0Aoy8blwE3lUMZUTxbFhA)]

__Knowledge Representation Learning: A Quantitative Review__. Preprint 2018. _Lin, Yankai and Han, Xu and Xie, Ruobing and Liu, Zhiyuan and Sun, Maosong_. [[Paper](https://arxiv.org/pdf/1812.10901)]

__Knowledge graph embedding: A survey of approaches and applications__. TKDE 2017. _Wang, Quan and Mao, Zhendong and Wang, Bin and Guo, Li_. [[Paper](https://persagen.com/files/misc/Wang2017Knowledge.pdf)]

__Knowledge graph refinement: A survey of approaches and evaluation methods__. Semantic Web 2017. _Paulheim, Heiko_. [[Paper](http://www.semantic-web-journal.net/system/files/swj1167.pdf)]

__A review of relational machine learning for knowledge graphs__. Proceedings of the IEEE 2015. _Nickel, Maximilian and Murphy, Kevin and Tresp, Volker and Gabrilovich, Evgeniy_. [[Paper](https://arxiv.org/pdf/1503.00759)]

## Papers by venues
| Year      | WWW                           | AAAI                          |
| --------  | --------                      | --------                      |   
| 2020      | [20](./conferences/www20.md)  | [28](./conferences/aaai20.md)   |

## Knowledge Graph Embedding
__Relation Embedding with Dihedral Group in Knowledge Graph__. ACL 2019. _Xu, Canran and Li, Ruijiang_. [[Paper](https://arxiv.org/pdf/1906.00687)]

__RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space__. ICLR 2019. _Zhiqing Sun and Zhi-Hong Deng and Jian-Yun Nie and Jian Tang_. [[Paper](https://arxiv.org/pdf/1902.10197)] [[Code](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding)]

__Logic Attention Based Neighborhood Aggregation for Inductive Knowledge Graph Embedding__. AAAI 2019. _Wang, Peifeng and Han, Jialong and Li, Chenliang and Pan, Rong_. [[Paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-WangPeifeng.2685.pdf)]

__Embedding Uncertain Knowledge Graphs__. AAAI 2019.
_Chen et al._ [[Paper](https://arxiv.org/abs/1811.10667)]

__TransGate: Knowledge Graph Embedding with Shared Gate Structure__. AAAI 2019.
_Yuan et al._ [[Paper](https://aaai.org/ojs/index.php/AAAI/article/view/4169/4047)]

__Improved Knowledge Graph Embedding using Background Taxonomic Information__. AAAI 2019.
_Fatemi et al._ [[Paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4231/4109)]

__Validation of Growing Knowledge Graphs by Abductive Text Evidences__. AAAI 2019.
_Du et al._ [[Paper](https://aaai.org/ojs/index.php/AAAI/article/view/4130/4008)]


__Variational Quantum Circuit Model for Knowledge Graph Embedding__. Advanced Quantum Technologies 2019. _Yunpu Ma, Volker Tresp, Liming Zhao, and Yuyi Wang_. [[Paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/qute.201800078)]

__Interaction Embeddings for Prediction and Explanation in Knowledge Graphs__. WSDM 2019. _Wen Zhang, Bibek Paudel, Wei Zhang, Abraham Bernstein, Huajun Chen_. [[Paper](https://www.zora.uzh.ch/id/eprint/162876/1/interaction-embeddings-prediction_merlin_version.pdf)]

__Does William Shakespeare Really Write Hamlet? Knowledge Representation Learning with Confidence__. AAAI 2018. _Ruobing Xie, Zhiyuan Liu, Fen Lin, and Leyu Lin_. [[Paper](https://arxiv.org/pdf/1705.03202.pdf)] [[Code](https://github.com/thunlp/CKRL)]

__TorusE: Knowledge graph embedding on a lie group__. AAAI 2018. _Ebisu, Takuma and Ichise, Ryutaro_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/16227/15885)]

__Convolutional 2d knowledge graph embeddings__. AAAI 2018. _Dettmers, Tim and Minervini, Pasquale and Stenetorp, Pontus and Riedel, Sebastian_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/17366/15884)]

__Towards Understanding the Geometry of Knowledge Graph Embedding__. ACL 2018. _Chandrahas, Aditya Sharma and Partha Talukdar_. [[Paper](http://www.aclweb.org/anthology/P18-1012)] [[Code](https://github.com/malllabiisc/kg-geometry)] [[Note](./notes/embedding/kg-geometry.md)]   

__Co-training Embedding of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment__. IJCAI 2018, _Chen, Muhao, Yingtao Tian, Kai-Wei Chang, Steven Skiena, and Carlo Zaniolo_. [[Paper](https://arxiv.org/pdf/1806.06478.pdf)] [[Note](./notes/embedding/co-training.md)]   

__Scalable Rule Learning via Learning Representation__. IJCAI 2018. _Omran, Pouya Ghiasnezhad, Kewen Wang, and Zhe Wang._ [[Paper](https://www.ijcai.org/proceedings/2018/0297.pdf)] [[Note](./notes/embedding/rule-learning.md)]  

__KBGAN: Adversarial Learning for Knowledge Graph Embeddings__. NAACL 2018. _Cai, Liwei, and William Yang Wang_. [[Paper](https://arxiv.org/pdf/1711.04071.pdf)] [[Code](https://github.com/cai-lw/KBGAN)] [[Note](./notes/embedding/KBGAN.md)]  

__Embedding Logical Queries on Knowledge Graphs__. NIPS 2018. _William L. Hamilton, Payal Bajaj, Marinka Zitnik, Dan Jurafsky, and Jure Leskovec_. [[Paper](http://papers.nips.cc/paper/7473-embedding-logical-queries-on-knowledge-graphs.pdf)] [[Code](https://github.com/williamleif/graphqembed)]

__SimpIE Embedding for Link Prediction in Knowledge Graphs__. NIPS 2018. _Seyed Mehran Kazemi, David Poole_. [[Paper](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs)] [[Code](https://github.com/Mehran-k/SimplE)]

__Differentiating Concepts and Instances for Knowledge Graph Embedding__. EMNLP 2018. _Xin Lv, Lei Hou, Juanzi Li, Zhiyuan Liu_. [[Paper](http://aclweb.org/anthology/D18-1222)] [[Code](http://github.com/davidlvxin/TransC)]

__Analogical inference for multi-relational embeddings__. ICML 2017. _Liu, Hanxiao and Wu, Yuexin and Yang, Yiming_. [[Paper](https://arxiv.org/pdf/1705.02426.pdf)] [[Code](https://github.com/quark0/ANALOGY)]

__Poincaré embeddings for learning hierarchical representations__. NIPS 2017. _Nickel, Maximillian and Kiela_.[[Paper](https://papers.nips.cc/paper/7213-poincare-embeddings-for-learning-hierarchical-representations.pdf)] [[Code](https://github.com/facebookresearch/poincare-embeddings)]

__On the equivalence of holographic and complex embeddings for link prediction__. ACL 2017. _Hayashi, Katsuhiko and Shimbo, Masashi_. [[Paper](https://arxiv.org/pdf/1702.05563.pdf)]

__Modeling relational data with graph convolutional networks__. European Semantic Web Conference 2017. _Schlichtkrull, Michael and Kipf, Thomas N and Bloem, Peter and Van Den Berg, Rianne and Titov, Ivan and Welling, Max_. [[Paper](https://arxiv.org/pdf/1903.02188)]

__Holographic embeddings of knowledge graphs__. AAAI 2016. _Nickel, Maximilian and Rosasco, Lorenzo and Poggio, Tomaso_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewFile/12484/11828)]

__Complex embeddings for simple link prediction__. ICML 2016. _Trouillon, Théo and Welbl, Johannes and Riedel, Sebastian and Gaussier, Éric and Bouchard, Guillaume_. [[Paper](http://proceedings.mlr.press/v48/trouillon16.pdf)] [[Code](https://github.com/ttrouill/complex)]

__Embedding entities and relations for learning and inference in knowledge bases__. ICLR 2015. _Yang, Bishan and Yih, Wen-tau and He, Xiaodong and Gao, Jianfeng and Deng, Li_. [[Paper](https://arxiv.org/pdf/1412.6575.pdf)]

__Effective blending of two and three-way interactions for modeling multi-relational data__. ECML-KDD 2014. _García-Durán, Alberto and Bordes, Antoine and Usunier, Nicolas_. [[Paper](https://link.springer.com/chapter/10.1007/978-3-662-44848-9_28)]

__Relation extraction with matrix factorization and universal schemas__. NAACL 2013. _Riedel, Sebastian and Yao, Limin and McCallum, Andrew and Marlin, Benjamin M_. [[Paper](http://www.aclweb.org/anthology/N13-1008)]

__A latent factor model for highly multi-relational data__. NIPS 2012. _Jenatton, Rodolphe and Roux, Nicolas L and Bordes, Antoine and Obozinski, Guillaume R_. [[Paper](https://papers.nips.cc/paper/4744-a-latent-factor-model-for-highly-multi-relational-data.pdf)]

__Factorizing YAGO: scalable machine learning for linked data__. ICML 2012. _Nickel, Maximilian and Tresp, Volker and Kriegel, Hans-Peter_. [[Paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.383.2015&rep=rep1&type=pdf)]

__A Three-Way Model for Collective Learning on Multi-Relational Data__. ICML 2011. _Nickel, Maximilian and Tresp, Volker and Kriegel, Hans-Peter_. [[Paper](http://www.dbs.ifi.lmu.de/~tresp/papers/p271.pdf)]

__Modelling relational data using bayesian clustered tensor factorization__. NIPS 2009. _Sutskever, Ilya and Tenenbaum, Joshua B and Salakhutdinov, Ruslan R_. [[Paper](https://papers.nips.cc/paper/3863-modelling-relational-data-using-bayesian-clustered-tensor-factorization.pdf)]

__Translating embeddings for modeling multi-relational data__. NIPS 2013. _Bordes, Antoine and Usunier, Nicolas and Garcia-Duran, Alberto and Weston, Jason and Yakhnenko, Oksana_. [[Paper](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf)]

__Knowledge graph embedding by translating on hyperplanes__. AAAI 2014. _Wang, Zhen and Zhang, Jianwen and Feng, Jianlin and Chen, Zheng_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8531/8546)]

__Learning entity and relation embeddings for knowledge graph completion__. AAAI 2015. _Lin, Yankai and Liu, Zhiyuan and Sun, Maosong and Liu, Yang and Zhu, Xuan_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9571/9523)] [[Code](http://github.com/mrlyk423/relation)]

__STransE: a novel embedding model of entities and relationships in knowledge bases__. NAACL 2016. _Nguyen, Dat Quoc and Sirts, Kairit and Qu, Lizhen and Johnson, Mark_. [[Paper](https://arxiv.org/pdf/1606.08140.pdf)]

__Knowledge graph embedding via dynamic mapping matrix__. ACL 2015. _Ji, Guoliang and He, Shizhu and Xu, Liheng and Liu, Kang and Zhao, Jun_. [[Paper](http://www.aclweb.org/anthology/P15-1067)]

__A translation-based knowledge graph embedding preserving logical property of relations__. NAACL 2016. _Yoon, Hee-Geun and Song, Hyun-Je and Park, Seong-Bae and Park, Se-Young_. [[Paper](http://www.aclweb.org/anthology/N16-1105)]

__Knowledge graph completion with adaptive sparse transfer matrix__. AAAI 2016. _Ji, Guoliang and Liu, Kang and He, Shizhu and Zhao, Jun_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewFile/11982/11693)]

__TransA: An adaptive approach for knowledge graph embedding__. AAAI 2015. _Xiao, Han and Huang, Minlie and Hao, Yu and Zhu, Xiaoyan_. [[Paper](https://arxiv.org/pdf/1509.05490.pdf)]

__Knowledge graph embedding by flexible translation__. KR 2016. _Feng, Jun and Huang, Minlie and Wang, Mingdong and Zhou, Mantong and Hao, Yu and Zhu, Xiaoyan_. [[Paper](https://www.aaai.org/ocs/index.php/KR/KR16/paper/viewFile/12887/12520)]

__Learning to represent knowledge graphs with gaussian embedding__. CIKM 2015. _He, Shizhu and Liu, Kang and Ji, Guoliang and Zhao, Jun_. [[Paper](http://ir.ia.ac.cn/bitstream/173211/20634/1/Learning%20to%20Represent%20Knowledge%20Graphs%20with%20Gaussian%20Embedding.pdf)]

__From one point to a manifold: Orbit models for knowledge graph embedding__. IJCAI 2016. _Xiao, Han and Huang, Minlie and Zhu, Xiaoyan_. [[Paper](https://www.ijcai.org/Proceedings/16/Papers/190.pdf)]

__Composing relationships with translations__. EMNLP 2015. _García-Durán, Alberto and Bordes, Antoine and Usunier, Nicolas_. [[Paper](http://www.aclweb.org/anthology/D15-1034)] [[Code](https://github.com/glorotxa/SME)]

__A semantic matching energy function for learning with multi-relational data__. Machine Learning 2014. _Bordes, Antoine and Glorot, Xavier and Weston, Jason and Bengio, Yoshua_. [[Paper](https://arxiv.org/pdf/1301.3485)]

__[⬆](#awesome-knowledge-graph)__
## Cross-Modal KG Embedding
### Textual Description
__Knowledge graph and text jointly embedding__. EMNLP 2015. _Wang, Zhen and Zhang, Jianwen and Feng, Jianlin and Chen, Zheng_. [[Paper](https://www.aclweb.org/anthology/D14-1167)]

__Aligning knowledge and text embeddings by entity descriptions__. EMNLP 2015. _Zhong, Huaping and Zhang, Jianwen and Wang, Zhen and Wan, Hai and Chen, Zheng_. [[Paper](https://www.aclweb.org/anthology/D15-1031)]

__Joint semantic relevance learning with text data and graph knowledge__. ACL-IJCNLP Workshop 2015. _Zhang, Dongxu and Yuan, Bin and Wang, Dong and Liu, Rong_. [[Paper](https://www.aclweb.org/anthology/W15-4004)]

__SSP: semantic space projection for knowledge graph embedding with text descriptions__. AAAI 2017. _Xiao, Han and Huang, Minlie and Meng, Lian and Zhu, Xiaoyan_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewPDFInterstitial/14306/14084)]

__Representation learning of knowledge graphs with entity descriptions__. AAAI 2016. _Xie, Ruobing and Liu, Zhiyuan and Jia, Jia and Luan, Huanbo and Sun, Maosong_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/12216/12004)] [[Code](https://github.com/xrb92/DKRL)]

__Distributed representation learning for knowledge graphs with entity descriptions__. PRL 2017. _Fan, Miao and Zhou, Qiang and Zheng, Thomas Fang and Grishman, Ralph_. [[Paper](https://www.sciencedirect.com/science/article/pii/S0167865516302380)]

__Text-enhanced representation learning for knowledge graph__. IJCAI 2016. _Wang, Zhigang and Li, Juan-Zi_. [[Paper](https://www.ijcai.org/Proceedings/16/Papers/187.pdf)]

__Knowledge Representation Learning with Entities, Attributes and Relations__. IJCAI 2016. [[Paper](http://nlp.csai.tsinghua.edu.cn/~lyk/publications/ijcai2016_krear.pdf)] [[Code](https://github.com/thunlp/KR-EAR)]


### Type Information
__Type-constrained representation learning in knowledge graphs__. ISWC 2015. _Krompass, Denis and Baier, Stephan and Tresp, Volker_. [[Paper](https://arxiv.org/pdf/1508.02593)]

__Typed tensor decomposition of knowledge bases for relation extraction__. EMNLP 2014. _Chang, Kai-Wei and Yih, Wen-tau and Yang, Bishan and Meek, Christopher_. [[Paper](https://www.aclweb.org/anthology/D14-1165)]

__Semantically smooth knowledge graph embedding__. ACL 2015. _Guo, Shu and Wang, Quan and Wang, Bin and Wang, Lihong and Guo, Li_. [[Paper](https://www.aclweb.org/anthology/P15-1009)]

__Entity hierarchy embedding__. ACL 2015. _Hu, Zhiting and Huang, Poyao and Deng, Yuntian and Gao, Yingkai and Xing, Eric_. [[Paper](https://www.aclweb.org/anthology/P15-1125)]

__Representation Learning of Knowledge Graphs with Hierarchical Types__. IJCAI 2016. _Xie, Ruobing and Liu, Zhiyuan and Sun, Maosong_. [[Paper](http://nlp.csai.tsinghua.edu.cn/~xrb/publications/IJCAI-16_type.pdf)]

__Knowledge graph embedding with hierarchical relation structure__. EMNLP 2018. _Zhang, Zhao and Zhuang, Fuzhen and Qu, Meng and Lin, Fen and He, Qing_. [[Paper](https://www.aclweb.org/anthology/D18-1358)]

### Logic Rules
__AMIE: association rule mining under incomplete evidence in ontological knowledge bases__. WWW 2013. _Galárraga, Luis Antonio and Teflioudi, Christina and Hose, Katja and Suchanek, Fabian_. [[Paper](http://luisgalarraga.de/docs/amie.pdf))]

__Knowledge graph identification__. ISWC 2013. _Pujara, Jay and Miao, Hui and Getoor, Lise and Cohen, William_. [[Paper](https://link.springer.com/content/pdf/10.1007/978-3-642-41335-3_34.pdf)]

__Knowledge base completion using embeddings and rules__. IJCAI 2015. _Wang, Quan and Wang, Bin and Guo, Li_. [[Paper](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/download/10798/10921)]

__Injecting logical background knowledge into embeddings for relation extraction__. NAACL 2015. _Rocktäschel, Tim and Singh, Sameer and Riedel, Sebastian_. [[Paper](https://www.aclweb.org/anthology/N15-1118)]

__Low-Dimensional Embeddings of Logic__. ACL 2014. _Rocktäschel, Tim and Bošnjak, Matko and Singh, Sameer and Riedel, Sebastian_. [[Paper](https://www.aclweb.org/anthology/W14-2409)]

__Learning first-order logic embeddings via matrix factorization__. IJCAI 2016. _Wang, William Yang and Cohen, William W_. [[Paper](http://www.cs.cmu.edu/~yww/papers/ijcai2016.pdf)]

__Jointly embedding knowledge graphs and logical rules__. EMNLP 2016. _Guo, Shu and Wang, Quan and Wang, Lihong and Wang, Bin and Guo, Li_. [[Paper](https://www.aclweb.org/anthology/D16-1019)]

__Knowledge Graph Embedding with Iterative Guidance from Soft Rules__. AAAI 2018. _Guo, Shu and Wang, Quan and Wang, Lihong and Wang, Bin and Guo, Li_.
[[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16369/16011)] [[Code](https://github.com/iieir-km/RUGE)]

__Lifted rule injection for relation embeddings__. EMNLP 2016. _Demeester, Thomas and Rocktäschel, T and Riedel, S_. [[Paper](https://www.aclweb.org/anthology/D16-1146)]

### Relational Path
__Random walk inference and learning in a large scale knowledge base__. EMNLP 2011. _Lao, Ni and Mitchell, Tom and Cohen, William W_. [[Paper](https://aclanthology.info/pdf/D/D11/D11-1049.pdf)]

__Relational retrieval using a combination of path-constrained random walks__. Machine Learning 2010. _Lao, Ni and Cohen, William W_. [[Paper](https://link.springer.com/content/pdf/10.1007/s10994-010-5205-8.pdf)]

__Modeling relation paths for representation learning of knowledge bases__. EMNLP 2015. _Lin, Yankai and Liu, Zhiyuan and Luan, Huanbo and Sun, Maosong and Rao, Siwei and Liu, Song_. [[Paper](https://arxiv.org/pdf/1506.00379.pdf)] [[Code](https://github.com/mrlyk423/relation_extraction)]

__Context-dependent knowledge graph embedding__. EMNLP 2015. _Luo, Yuanfei and Wang, Quan and Wang, Bin and Guo, Li_. [[Paper](https://www.aclweb.org/anthology/D15-1191)]

__Compositional learning of embeddings for relation paths in knowledge base and text__. ACL 2016. _Toutanova, Kristina and Lin, Victoria and Yih, Wen-tau and Poon, Hoifung and Quirk, Chris_. [[Paper](http://www.aclweb.org/anthology/P16-1136)]

__GAKE: graph aware knowledge embedding__. COLING 2016. _Feng, Jun and Huang, Minlie and Yang, Yang and Zhu, Xiaoyan_. [[Paper](http://www.aclweb.org/anthology/C16-1062)]

__Traversing Knowledge Graphs in Vector Space__. EMNLP 2015. _Guu, Kelvin and Miller, John and Liang, Percy_. [[Paper](https://arxiv.org/pdf/1506.01094)]


### Visual Information
__Image-embodied knowledge representation learning__. IJCAI 2017. _Xie, Ruobing and Liu, Zhiyuan and Luan, Huanbo and Sun, Maosong_. [[Paper](https://www.ijcai.org/proceedings/2017/0438.pdf)]

__Answering Visual-Relational Queries in Web-Extracted Knowledge Graphs__.
Automated Knowledge Base Construction 2019. _Oñoro-Rubio et al._ [[Paper](https://arxiv.org/pdf/1709.02314.pdf)]
__[⬆](#awesome-knowledge-graph)__
## Knowledge Acquisition
### Knowledge Graph Completion
__Beyond Triplets: Hyper-Relational Knowledge Graph Embedding for Link Prediction__
WWW 2020. _Rosso et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380257)]

__Generalizing Tensor Decomposition for N-ary Relational Knowledge Bases__
WWW 2020. _Liu et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380188)]

__Relation Adversarial Network for Low Resource Knowledge Graph Completion__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380089)]

__Mining Implicit Entity Preference from User-Item Interaction Data for Knowledge Graph Completion via Adversarial Learning__
WWW 2020. _He et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380155)]

__Open Knowledge Enrichment for Long-tail Entities__.
WWW 2020. _Cao et al._.
[[Paper](https://arxiv.org/pdf/2002.06397.pdf)] [[Code](https://github.com/nju-websoft/OKELE/)]

__LENA: Locality-Expanded Neural Embedding for Knowledge Base Completion__. AAAI 2019.
_Kong et al._ [[Paper](https://aaai.org/ojs/index.php/AAAI/article/view/4144/4022)] [[Code](https://github.com/fskong/LENA)]

__On Completing Sparse Knowledge Graph with Transitive Relation Embedding__. AAAI 2019.
_Zhou et al._ [[Paper](https://aaai.org/ojs/index.php/AAAI/article/view/4173/4051)]

__End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion__. AAAI 2019. _Shang, Chao and Tang, Yun and Huang, Jing and Bi, Jinbo and He, Xiaodong and Zhou, Bowen_. [[Paper](https://arxiv.org/pdf/1811.04441)]

__An Open-World Extention to Knowledge Graph Completion MOdels__. AAAI 2019. _Haseeb Shah, Johannes Villmow, Adrian Ulges, Ulrich Schwanecke, Faisal Shafait_. [[Paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4162/4040)] [[Code](http://github.com/haseebs/OWE)]

__Embedding Multimodal Relational Data for Knowledge Base Completion__. EMNLP 2018. _Pezeshkpour, Pouya, Liyan Chen, and Sameer Singh._ [[Paper](https://arxiv.org/pdf/1809.01341.pdf)] [[Code](https://github.com/pouyapez/mkbe)] [[Note](./notes/completion/mkbe.md)]  

__Shared Embedding Based Neural Networks for Knowledge Graph Completion__. CIKM 2018. _Guan, Saiping and Jin, Xiaolong and Wang, Yuanzhuo and Cheng, Xueqi_. [[Paper](https://dl.acm.org/citation.cfm?id=3271704)]

__Expanding Holographic Embeddings for Knowledge Completion__. NIPS 2018. _Yexiang Xue, Yang Yuan, Zhitian Xu, and Ashish Sabharwal_. [[Paper](http://papers.nips.cc/paper/7701-expanding-holographic-embeddings-for-knowledge-completion)]

__M-Walk: Learning to Walk over Graphs using Monte Carlo Tree Search__. NIPS 2018. Yelong Shen, Jianshu Chen, Po-Sen Huang, Yuqing Guo, Jianfeng Gao. [[Paper](http://papers.nips.cc/paper/7912-m-walk-learning-to-walk-over-graphs-using-monte-carlo-tree-search)]

__Translating Embeddings for Knowledge Graph Completion with Relation Attention Mechanism__. IJCAI 2018. _Qian, Wei and Fu, Cong and Zhu, Yu and Cai, Deng and He, Xiaofei_. [[Paper](https://www.ijcai.org/proceedings/2018/0596.pdf)]

__Compositional Vector Space Models for Knowledge Base Completion__. ACL-IJCNLP 2015. _Neelakantan, Arvind and Roth, Benjamin and McCallum, Andrew_. [[Paper](http://anthology.aclweb.org/P/P15/P15-1016.pdf)]

__An Interpretable Knowledge Transfer Model for Knowledge Base Completion__. ACL 2017. _Xie, Qizhe and Ma, Xuezhe and Dai, Zihang and Hovy, Eduard_. [[Paper](https://arxiv.org/pdf/1704.05908)]

__A novel embedding model for knowledge base completion based on convolutional neural network__. NAACL 2018. _Nguyen, Dai Quoc and Nguyen, Tu Dinh and Nguyen, Dat Quoc and Phung, Dinh_. [[Paper](https://arxiv.org/pdf/1712.02121)]

__ProjE: Embedding projection for knowledge graph completion__. AAAI 2017. _Shi, Baoxu and Weninger, Tim_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14279/13906)] [[Code](https://github.com/nddsg/ProjE)]

__TuckER: Tensor Factorization for Knowledge Graph Completion__. _Balažević, Ivana and Allen, Carl and Hospedales, Timothy M_.
[[Paper](https://arxiv.org/pdf/1901.09590.pdf)] [[Code](https://github.com/ibalazevic/TuckER)]

__Open-world knowledge graph completion__. AAAI 2018. _Shi, Baoxu and Weninger, Tim_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16055/15901)] [[Code](https://github.com/bxshi/ConMask)]

__On Multi-Relational Link Prediction with Bilinear Models__. AAAI 2018. _Wang, Yanjie and Gemulla, Rainer and Li, Hui_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16900/16722)] [[Code](http://dws.informatik.uni-mannheim.de/en/resources/software/tf/)]

__Inferring missing entity type instances for knowledge base completion: New dataset and methods__. NAACL 2016. _Neelakantan, Arvind and Chang, Ming-Wei_. [[Paper](https://arxiv.org/pdf/1504.06658)]

__Spring-Electrical Models For Link Prediction__. WSDM 2019. _Kashinskaya, Yana and Samosvat, Egor and Artikov, Akmal_. [[Paper](https://dl.acm.org/citation.cfm?id=3290961)]

### Knowledge Graph Refinement
__What is Normal, What is Strange, and What is Missing in a Knowledge Graph: Unified Characterization via Inductive Summarization__
WWW 2020. _Belth et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380189)]


__Correcting Knowledge Base Assertions__.
WWW 2020. _Chen et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380226)]

__Expanding Taxonomies with Implicit Edge Semantics__
WWW 2020. _Manzoor et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380271)]

### Relation Extraction
__NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction__
WWW 2020. _Zhou et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380282)]

__LOREM: Language-consistent Open Relation Extraction from Unstructured Text__.
WWW 2020. _Harting et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380252)]

__Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks__. NAACL 2019. _Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, Huajun Chen_. [[Paper](https://arxiv.org/abs/1903.01306)]  

__Discovering Correlations between Sparse Features in Distant Supervision for Relation Extraction__. WSDM 2019. _Qu, Jianfeng and Ouyang, Dantong and Hua, Wen and Ye, Yuxin and Zhou, Xiaofang_. [[Paper](https://dl.acm.org/citation.cfm?id=3291004)]

__A Hierarchical Framework for Relation Extraction with Reinforcement Learning__. AAAI 2019. _Takanobu, Ryuichi and Zhang, Tianyang and Liu, Jiexi and Huang, Minlie_. [[Paper](https://arxiv.org/pdf/1811.03925.pdf)] [[Code](https://github.com/truthless11/HRL-RE)]

__Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning__. EMNLP 2018. _Liu, Tianyi, Xinsong Zhang, Wanhao Zhou, and Weijia Jia._ [[Paper](https://arxiv.org/pdf/1808.06738.pdf)] [[Note](./notes/RE/inner-sentence.md)]  

__DSGAN: Generative Adversarial Training for Robust Distant Supervision Relation Extraction__. ACL 2018. _Pengda Qin, Weiran Xu, William Yang Wang_. [[Paper](https://arxiv.org/pdf/1805.09929.pdf)]

__Deep Residual Learning for Weakly-Supervised Relation Extraction__. EMNLP 2017. _Yi Yao Huang, William Yang Wang_. [[Paper](http://www.cs.ucsb.edu/~william/papers/ResCNN.pdf)]
[[Code](https://github.com/darrenyaoyao/ResCNN_RelationExtraction)]

__Incorporating Relation Paths in Neural Relation Extraction__. EMNLP 2017. _Zeng, Wenyuan and Lin, Yankai and Liu, Zhiyuan and Sun, Maosong_. [[Paper](http://www.aclweb.org/anthology/D17-1186)] [[Code](http://github.com/thunlp/PathNRE)]

__Knowledge-based weak supervision for information extraction of overlapping relations__. ACL 2011. _Hoffmann, Raphael and Zhang, Congle and Ling, Xiao and Zettlemoyer, Luke and Weld, Daniel S_. [[Paper](http://www.aclweb.org/anthology/P11-1055)]

__Learning syntactic patterns for automatic hypernym discovery__. NIPS 2005. _Snow, Rion and Jurafsky, Daniel and Ng, Andrew Y_. [[Paper](http://papers.nips.cc/paper/2659-learning-syntactic-patterns-for-automatic-hypernym-discovery.pdf)]

__Distant supervision for relation extraction without labeled data__. ACL 2009. _Mintz, Mike and Bills, Steven and Snow, Rion and Jurafsky, Dan_. [[Paper](https://www.aclweb.org/anthology/P09-1113)]

__Modeling relations and their mentions without labeled text__. ECML 2010. _Riedel, Sebastian and Yao, Limin and McCallum, Andrew_. [[Paper](https://link.springer.com/content/pdf/10.1007/978-3-642-15939-8_10.pdf)]

__Multi-instance multi-label learning for relation extraction__. EMNLP 2012. _Surdeanu, Mihai and Tibshirani, Julie and Nallapati, Ramesh and Manning, Christopher D_. [[Paper](http://www.aclweb.org/anthology/D12-1042)]

__Connecting Language and Knowledge Bases with Embedding Models for Relation Extraction__. EMNLP 2013. _Weston, Jason and Bordes, Antoine and Yakhnenko, Oksana and Usunier, Nicolas_. [[Paper](https://arxiv.org/pdf/1307.7973.pdf)]

__Distant supervision for relation extraction with matrix completion__. ACL 2014. _Fan, Miao and Zhao, Deli and Zhou, Qiang and Liu, Zhiyuan and Zheng, Thomas Fang and Chang, Edward Y_. [[Paper](http://www.aclweb.org/anthology/P14-1079)]

__Semantic compositionality through recursive matrix-vector spaces__. EMNLP 2012. _Socher, Richard and Huval, Brody and Manning, Christopher D and Ng, Andrew Y_. [[Paper](https://aclanthology.info/pdf/D/D12/D12-1110.pdf)]

__End-to-End Relation Extraction using LSTMs on Sequences and Tree Structures__. ACL 2016. _Miwa, Makoto and Bansal, Mohit_. [[Paper](http://www.aclweb.org/anthology/P16-1105)]

__Relation Classification via Convolutional Deep Neural Network__. COLING 2014. _Zeng, Daojian and Liu, Kang and Lai, Siwei and Zhou, Guangyou and Zhao, Jun_. [[Paper](http://anthology.aclweb.org/C/C14/C14-1220.pdf)]

__Classifying relations via long short term memory networks along shortest dependency paths__. EMNLP 2015. _Xu, Yan and Mou, Lili and Li, Ge and Chen, Yunchuan and Peng, Hao and Jin, Zhi_. [[Paper](http://www.aclweb.org/anthology/D15-1206)]

__Classifying Relations by Ranking with Convolutional Neural Networks__. ACL 2015. _dos Santos, Cicero and Xiang, Bing and Zhou, Bowen_. [[Paper](http://www.anthology.aclweb.org/P/P15/P15-1061.pdf)]

__Distant supervision for relation extraction via piecewise convolutional neural networks__. EMNLP 2015. _Zeng, Daojian and Liu, Kang and Chen, Yubo and Zhao, Jun_. [[Paper](http://www.aclweb.org/anthology/D15-1203)]

__Neural relation extraction with selective attention over instances__. ACL 2016. _Lin, Yankai and Shen, Shiqi and Liu, Zhiyuan and Luan, Huanbo and Sun, Maosong_. [[Paper](http://www.aclweb.org/anthology/P16-1200)] [[Code](http://github.com/thunlp/NRE)]

__Adversarial training for relation extraction__. EMNLP 2017. _Wu, Yi and Bamman, David and Russell, Stuart_. [[Paper](https://www.aclweb.org/anthology/D17-1187)] [[Code](https://github.com/jxwuyi/AtNRE)]

__Relation Extraction with Multi-instance Multi-label Convolutional Neural Networks__. COLING 2016. _Jiang, Xiaotian and Wang, Quan and Li, Peng and Wang, Bin_. [[Paper](https://www.aclweb.org/anthology/C16-1139)]

__Jointly Extracting Relations with Class Ties via Effective Deep Ranking__. ACL 2017. _Ye, Hai and Chao, Wenhan and Luo, Zhunchen and Li, Zhoujun_ [[Paper](https://www.aclweb.org/anthology/P17-1166)]

__A soft-label method for noise-tolerant distantly supervised relation extraction__. EMNLP 2017. _Liu, Tianyu and Wang, Kexiang and Chang, Baobao and Sui, Zhifang_. [[Paper](https://www.aclweb.org/anthology/D17-1189)]

__Distant supervision for relation extraction with sentence-level attention and entity descriptions__. AAAI 2017. _Ji, Guoliang and Liu, Kang and He, Shizhu and Zhao, Jun_. [[Paper](https://www.aaai.org/Conferences/AAAI/2017/PreliminaryPapers/14-JiG-14491.pdf)]

__Attention-based convolutional neural network for semantic relation extraction__. COLING 2016. _Shen, Yatian and Huang, Xuanjing_. [[Paper](https://www.aclweb.org/anthology/C16-1238)]

__Neural knowledge acquisition via mutual attention between knowledge graph and text__. AAAI 2018. _Han, Xu and Liu, Zhiyuan and Sun, Maosong_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16691/16013)] [[Code](https://github.com/thunlp/JointNRE)] Also for KGC.

__Cooperative Denoising for Distantly Supervised Relation Extraction__. COLING 2018. _Lei, Kai and Chen, Daoyuan and Li, Yaliang and Du, Nan and Yang, Min and Fan, Wei and Shen, Ying_. [[Paper](https://www.aclweb.org/anthology/C18-1036)]

__Hierarchical Relation Extraction with Coarse-to-Fine Grained Attention__. EMNLP 2018. _Han, Xu and Yu, Pengfei and Liu, Zhiyuan and Sun, Maosong and Li, Peng_. [[Paper](https://www.aclweb.org/anthology/D18-1247)] [[Code](https://github.com/thunlp/HNRE)]

__Large scaled relation extraction with reinforcement learning__. AAAI 2018. _Zeng, Xiangrong and He, Shizhu and Liu, Kang and Zhao, Jun_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16257/16125)]

__Robust Distant Supervision Relation Extraction via Deep Reinforcement Learning__. ACL 2018. _Qin, Pengda and Weiran, XU and Wang, William Yang_. [[Paper](https://www.aclweb.org/anthology/P18-1199)]

__Incorporating vector space similarity in random walk inference over knowledge bases__. EMNLP 2014. _Gardner, Matt and Talukdar, Partha and Krishnamurthy, Jayant and Mitchell, Tom_. [[Paper](https://www.aclweb.org/anthology/D14-1044)]

### Relation Classification
__Bidirectional recurrent convolutional neural network for relation classification__. ACL 2016. _Cai, Rui and Zhang, Xiaodong and Wang, Houfeng_. [[Paper](https://www.aclweb.org/anthology/P16-1072)]

__Attention-based bidirectional long short-term memory networks for relation classification__. ACL 2016. _Zhou, Peng and Shi, Wei and Tian, Jun and Qi, Zhenyu and Li, Bingchen and Hao, Hongwei and Xu, Bo_. [[Paper](https://www.aclweb.org/anthology/P16-2034)]

__Reinforcement learning for relation classification from noisy data__. AAAI 2018. _Feng, Jun and Huang, Minlie and Zhao, Li and Yang, Yang and Zhu, Xiaoyan_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/17151/16140)]

### Entity Recognition
__Multi-grained Named Entity Recognition__. ACL 2019. _Xia, Congying and Zhang, Chenwei and Yang, Tao and Li, Yaliang and Du, Nan and Wu, Xian and Fan, Wei and Ma, Fenglong and Philip, S Yu_. [[Paper](https://arxiv.org/abs/1906.08449)]

__Neural architectures for named entity recognition__. NAACL 2017. _Lample, Guillaume and Ballesteros, Miguel and Subramanian, Sandeep and Kawakami, Kazuya and Dyer, Chris_. [[Paper](https://arxiv.org/pdf/1603.01360)] [[Cdde](https://github.com/glample/tagger)] [[Code](https://github.com/clab/stack-lstm-ner)]

__Named entity recognition with bidirectional LSTM-CNNs__. TACL 2016. _Chiu, Jason PC and Nichols, Eric_. [[Paper](https://www.mitpressjournals.org/doi/pdf/10.1162/tacl_a_00104)]

__Novel Entity Discovery from Web Tables__
WWW 2020. _Zhang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380205)]

__MetaNER: Named Entity Recognition with Meta-Learning__
WWW 2020. _Li et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380127)]

### Entity Alignment
__Collective Multi-type Entity Alignment Between Knowledge Graphs__
WWW 2020. _Zhu et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380289)]

__Entity Alignment between Knowledge Graphs Using Attribute Embeddings__. AAAI 2019. _Trsedya, Bayu Distiawan and Qi, Jianzhong and Zhang, Rui_. [[Paper](https://people.eng.unimelb.edu.au/jianzhongq/papers/AAAI2019_EntityAlignment.pdf)] [[Code](https://bitbucket.org/bayudt/kba/src/master/)]

__Multi-view Knowledge Graph Embedding for Entity Alignment__. IJCAI 2019. _Zhang, Qingheng and Sun, Zequn and Hu, Wei and Chen, Muhao and Guo, Lingbing and Qu, Yuzhong_. [[Paper](https://arxiv.org/pdf/1906.02390.pdf)] [[Code](https://github.com/nju-websoft/MultiKE)]

__Co-training embeddings of knowledge graphs and entity descriptions for cross-lingual entity alignment__. IJCAI 2018. _Chen, Muhao and Tian, Yingtao and Chang, Kai-Wei and Skiena, Steven and Zaniolo, Carlo_. [[Paper](https://www.ijcai.org/proceedings/2018/0556.pdf)]

__Bootstrapping Entity Alignment with Knowledge Graph Embedding__.  IJCAI 2018. _Zequn Sun, Wei Hu, Qingheng Zhang and Yuzhong Qu._ [[Paper](https://www.ijcai.org/proceedings/2018/0611.pdf)] [[Code](https://github.com/nju-websoft/BootEA)] [[Note](./notes/embedding/BootEA.md)]  

__Cross-lingual Knowledge Graph Alignment via Graph Convolutional Networks__. EMNLP 2018.
_Zhichun Wang, Qingsong Lv, Xiaohan Lan, Yu Zhang_. [[Paper](http://www.aclweb.org/anthology/D18-1032)]

__Cross-lingual entity alignment via joint attribute-preserving embedding__. ISWC 2017. _Sun, Zequn and Hu, Wei and Li, Chengkai_. [[Paper](https://arxiv.org/pdf/1708.05045)]

__Iterative entity alignment via joint knowledge embeddings__. IJCAI 2017. _Zhu, Hao and Xie, Ruobing and Liu, Zhiyuan and Sun, Maosong_. [[Paper](https://www.ijcai.org/proceedings/2017/0595.pdf)] [[Code](https://github.com/thunlp/IEAJKE)]

__Multilingual knowledge graph embeddings for cross-lingual knowledge alignment__. IJCAI 2017. _Chen, Muhao and Tian, Yingtao and Yang, Mohan and Zaniolo, Carlo_. [[Paper](https://www.ijcai.org/proceedings/2017/0209.pdf)]

__Aligning Knowledge Base and Document Embedding Models Using Regularized Multi-Task Learning__. ISWC 2018. _Baumgartner, Matthias and Zhang, Wen and Paudel, Bibek and Dell’Aglio, Daniele and Chen, Huajun and Bernstein, Abraham_. [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-00671-6_2)]


### Entity Disambiguation
__High Quality Candidate Generation and Sequential Graph Attention Network for Entity Linking__
WWW 2020. _Fang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380146)]

__Dynamic Graph Convolutional Networks for Entity Linking__
WWW 2020. _Wu et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380192)]

__Improving Entity Linking by Modeling Latent Relations between Mentions__. ACL 2018. _Le, Phong and Titov, Ivan_. [[Paper](https://arxiv.org/pdf/1804.10637)]

__Deep Joint Entity Disambiguation with Local Neural Attention__. EMNLP 2017. _Ganea, Octavian-Eugen and Hofmann, Thomas_. [[Paper](https://arxiv.org/pdf/1704.04920)]

__Design challenges for entity linking__. TACL 2015. _Ling, Xiao and Singh, Sameer and Weld, Daniel S_. [[Paper](https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00141)]

__Leveraging deep neural networks and knowledge graphs for entity disambiguation__. 2015. _Huang, Hongzhao and Heck, Larry and Ji, Heng_. [[Paper](https://arxiv.org/pdf/1504.07678.pdf)]

__Entity disambiguation by knowledge and text jointly embedding__. CoNLL 2016. _Fang, Wei and Zhang, Jianwen and Wang, Dilin and Chen, Zheng and Li, Ming_. [[Paper](https://www.aclweb.org/anthology/K16-1026)]

__End-to-End Neural Entity Linking__. CoNLL 2018.
_Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann_
[[Paper](https://arxiv.org/abs/1808.07699})]


### Entity Typing
__Label noise reduction in entity typing by heterogeneous partial-label embedding__. KDD 2016. _Ren, Xiang and He, Wenqi and Qu, Meng and Voss, Clare R and Ji, Heng and Han, Jiawei_. [[Paper](https://arxiv.org/pdf/1602.05307)]

__Label Embedding for Zero-shot Fine-grained Named Entity Typing__. COLING 2016. _Yukun Ma, Erik Cambria, Sa Gao_. [[Paper](https://www.aclweb.org/anthology/C16-1017)] [[Code](https://github.com/fnet-coling/ner-zero)]





__[⬆](#awesome-knowledge-graph)__
## Knowledge-aware Applications

### Natural Language Understanding
__Combining Axiom Injection and Knowledge Base Completion for Efficient Natural Language Inference__. AAAI 2019.
_Yoshikawa et al._ [[Paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4730/4608)] [[Code](https://github.com/masashi-y/abduction_kbc)]

__Deep Short Text Classification with Knowledge Powered Attention__. AAAI 2019.
_Chen et al._ [[Paper](https://arxiv.org/abs/1902.08050)]

__A neural knowledge language model__. 2016. _Ahn, Sungjin and Choi, Heeyoul and Pärnamaa, Tanel and Bengio, Yoshua_. [[Paper](https://arxiv.org/pdf/1608.00318)] [[Dataset](https://bitbucket.org/skaasj/wikifact_filmactor)]

__ERNIE: Enhanced Language Representation with Informative Entities__. ACL 2019. _Zhang, Zhengyan and Han, Xu and Liu, Zhiyuan and Jiang, Xin and Sun, Maosong and Liu, Qun_. [[Paper](https://arxiv.org/pdf/1905.07129)] [[Code](https://github.com/thunlp/ERNIE)]

__Targeted Aspect-Based Sentiment Analysis via Embedding Commonsense Knowledge into an Attentive LSTM__. AAAI 2018. _Yukun Ma, Haiyun Peng, Erik Cambria_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16541/16152)]


__Combining Knowledge with Deep Convolutional Neural Networks for Short Text Classification__. IJCAI 2017. _Wang, Jin and Wang, Zhongyuan and Zhang, Dawei and Yan, Jun_. [[Paper](http://yellowstone.cs.ucla.edu/~jinwang/jinwang_files/ijcai2017.pdf)]


### Commonsense Knowledge
__Story Ending Generation with Incremental Encoding and Commonsense Knowledge__. AAAI 2019.
_Jian Guan, Yansen Wang, Minlie Huang_. [[Paper](https://arxiv.org/abs/1808.10113)]

__Incorporating Commonsense Knowledge for Story Completion__. AAAI 2019.
_Chen et al._. [[Paper](https://arxiv.org/abs/1811.00625)]

__Simulation-Based Approach to Efficient Commonsense Reasoning in Very Large Knowledge Bases__. AAAI 2019.
_Sharma et al._ [[Paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/3936)]


### Question Answering
__Complex Factoid Question Answering with a Free-Text Knowledge Graph__
WWW 2020. _Zhao et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380197)]

__Declarative Question Answering over Knowledge Bases containing Natural Language Text with Answer Set Programming__. AAAI 2019.
_Mitra et al._ [[Paper](https://arxiv.org/abs/1905.00198)]

__Multi-Task Learning with Multi-View Attention for Answer Selection and Knowledge Base Question Answering__. AAAI 2019.
_Deng et al._ [[Paper](https://arxiv.org/abs/1812.02354)]

__An Interpretable Reasoning Network for Multi-Relation Question Answering__. COLING 2018. _Zhou, Mantong and Huang, Minlie and Zhu, Xiaoyan_. [[Paper](https://arxiv.org/abs/1801.04726)]

__Dialog-to-Action: Conversational Question Answering Over a Large-Scale Knowledge Base__. NIPS 2018. _Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin_. [[Paper](http://papers.nips.cc/paper/7558-dialog-to-action-conversational-question-answering-over-a-large-scale-knowledge-base)] [[Code](https://github.com/guoday/Dialog-to-Action)]

__Commonsense for Generative Multi-hop Question Answering Tasks__. EMNLP 2018. _Bauer, Lisa, Yicheng Wang, and Mohit Bansal._ [[Paper](https://arxiv.org/pdf/1809.06309.pdf)] [[Code](https://github.com/yicheng-w/CommonSenseMultiHopQA)] [[Note](./notes/QA/multi-hop.md)]  

__Complex Sequential Question Answering: Towards Learning to Converse Over Linked Question Answer Pairs with a Knowledge Graph__. AAAI 2018. _Amrita Saha, Vardaan Pahuja, Mitesh M. Khapra, Karthik Sankaranarayanan, Sarath Chandar_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17181/15750)]

__EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs__. ISWC 2018. _Dubey, Mohnish, Debayan Banerjee, Debanjan Chaudhuri, and Jens Lehmann._ [[Paper](https://arxiv.org/pdf/1801.03825.pdf)] [[Code](https://github.com/AskNowQA/EARL)] [[Note](./notes/QA/EARL.md)]  

__Pattern-revising Enhanced Simple Question Answering over Knowledge Bases__. COLING 2018. _Hao, Yanchao, Hao Liu, Shizhu He, Kang Liu, and Jun Zhao._ [[Paper](http://www.aclweb.org/anthology/C18-1277)] [[Note](./notes/QA/pattern-revising.md)]  

__Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks__. NAACL 2018. _Mohammed, Salman, Peng Shi, and Jimmy Lin._ [[Paper](https://arxiv.org/pdf/1712.01969.pdf)] [[Code](http://buboqa.io/)]  [[Note](./notes/QA/strong-baselines.md)]    

__Transliteration Better than Translation? Answering Code-mixed Questions over a Knowledge Base__. ACL 2018. _Gupta, Vishal, Manoj Chinnakotla, and Manish Shrivastava._ [[Paper](http://www.aclweb.org/anthology/W18-3205)] [[Note](./notes/QA/code-mixed.md)]  

__TEQUILA: Temporal Question Answering over Knowledge Bases__. CIKM 2018. _Zhen Jia, Abdalghani Abujabal, Rishiraj Saha Roy, Jannik Strötgen, Gerhard Weikum_. [[Paper](https://dl.acm.org/citation.cfm?id=3269247&dl=ACM&coll=DL)]

__Question answering over knowledge base with neural attention combining global knowledge information__. 2016. _Zhang et al._. [[Paper](https://arxiv.org/pdf/1606.00979)]

__CFO: Conditional Focused Neural Question Answering with Large-scale Knowledge Bases__. ACL 2016. _Dai et al._. [[Paper](https://www.aclweb.org/anthology/P16-1076)]

__Efficiently answering technical questions—a knowledge graph approach__. AAAI 2017. _Yang et al._. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewPDFInterstitial/14576/14085)]

__An end-to-end model for question answering over knowledge base with cross-attention combining global knowledge__. ACL 2017. _Hao et al._. [[Paper](https://www.aclweb.org/anthology/P17-1021)]

__Generating natural answers by incorporating copying and retrieving mechanisms in sequence-to-sequence learning__. ACL 2017. _He et al._. [[Paper](https://www.aclweb.org/anthology/P17-1019)]

__Neural Generative Question Answering__. IJCAI 2016. _Yin, Jun and Jiang, Xin and Lu, Zhengdong and Shang, Lifeng and Li, Hang and Li, Xiaoming_. [[Paper](https://arxiv.org/pdf/1512.01337)] [[Dataset](http://github.com/jxfeb/Generative_QA)]

### Dialogue Systems  
__Commonsense Knowledge Aware Conversation Generation with Graph Attention__. IJCAI 2018. _Zhou, Hao, Tom Young, Minlie Huang, Haizhou Zhao, Jingfang Xu, and Xiaoyan Zhu._ [[Paper](https://www.ijcai.org/proceedings/2018/0643.pdf)] [[Code](https://github.com/tuxchow/ccm)] [[Note](./notes/conversation/commonsense.md)]   

__Improving Response Selection in Multi-Turn Dialogue Systems by Incorporating Domain Knowledge__. CoNLL 2018. _Chaudhuri, Debanjan and Kristiadi, Agustinus and Lehmann, Jens and Fischer, Asja_. [[Paper](https://www.aclweb.org/anthology/K18-1048)]


__Incorporating loose-structured knowledge into conversation modeling via recall-gate LSTM__. IJCNN 2017. _Xu, Zhen and Liu, Bingquan and Wang, Baoxun and Sun, Chengjie and Wang, Xiaolong_. [[Paper](https://ieeexplore.ieee.org/iel7/7958416/7965814/07966297.pdf)]

__Lstm-based mixture-of-experts for knowledge-aware dialogues__. ACL 2016 Workshop. _Le, Phong and Dymetman, Marc and Renders, Jean-Michel_. [[Paper](https://arxiv.org/pdf/1605.01652.pdf)]

__Flexible end-to-end dialogue system for knowledge grounded conversation__. 2017. _Zhu, Wenya and Mo, Kaixiang and Zhang, Yu and Zhu, Zhangbin and Peng, Xuezheng and Yang, Qiang_. [[Paper](https://arxiv.org/pdf/1709.04264)]

### Recommendation System
__Reinforced Negative Sampling over Knowledge Graph for Recommendation__
WWW 2020. _Wang et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380098)]

__KGAT: Knowledge Graph Attention Network for Recommendation__. KDD 2019. _Xiang Wang, Xiangnan He, Yixin Cao, Meng Liu and Tat-Seng Chua_. [[Paper](https://arxiv.org/pdf/1905.07854)] [[Code](https://github.com/xiangwang1223/knowledge_graph_attention_network)]

__Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation__. WWW 2019. _Wang, Hongwei, Fuzheng Zhang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://arxiv.org/pdf/1901.08907.pdf)] [[Code](https://github.com/hwwang55/MKR)]

__Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preference__. WWW 2019. _Yixin Cao, Xiang Wang, Xiangnan He, Zikun Hu, Tat-Seng Chua_.
[[Paper](https://www.comp.nus.edu.sg/~xiangnan/papers/www19-KGRec.pdf)] [[Code](https://github.com/TaoMiner/joint-kg-recommender)]

__Explianable Reasoning over Knowledge Graphs for Recommendation__. AAAI 2019. _Wang, Xiang and Wang, Dingxian and Xu, Canran and He, Xiangnan and Cao, Yixin and Chua, Tat-Seng_. [[Paper](https://arxiv.org/abs/1811.04540)] [[Code](https://github.com/eBay/KPRN)]  

__Exploring High-Order User Preference on the Knowledge Graph for Recommender Systems__. TOIS 2019. _Hongwei Wang, Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://dl.acm.org/citation.cfm?id=3312738)]

__RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems__. CIKM 2018. _Hongwei Wang, Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://dl.acm.org/citation.cfm?id=3271739)]

__Collaborative knowledge base embedding for recommender systems__. SIGKDD 2016. _Zhang, Fuzheng and Yuan, Nicholas Jing and Lian, Defu and Xie, Xing and Ma, Wei-Ying_. [[Paper](https://www.kdd.org/kdd2016/papers/files/adf0066-zhangA.pdf)]

__Top-n recommendations from implicit feedback leveraging linked open data__. RecSys 2013. _Ostuni, Vito Claudio and Di Noia, Tommaso and Di Sciascio, Eugenio and Mirizzi, Roberto_. [[Paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.649.3358&rep=rep1&type=pdf)]

__dbrec—music recommendations using DBpedia__. ISWC 2010. _Passant, Alexandre_. [[Paper](https://link.springer.com/content/pdf/10.1007/978-3-642-17749-1_14.pdf)]

__Collaborative knowledge base embedding for recommender systems__. KDD 2016. _Zhang, Fuzheng and Yuan, Nicholas Jing and Lian, Defu and Xie, Xing and Ma, Wei-Ying_. [[Paper](https://www.kdd.org/kdd2016/papers/files/adf0066-zhangA.pdf)]

### Information Retrieval
__Keyword Search over Knowledge Graphs via Static and Dynamic Hub Labelings__
WWW 2020. _Shi et al._ [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380110)]

__Explicit semantic ranking for academic search via knowledge graph embedding__. WWW 2017. _Xiong et al._ [[Paper](http://www.cs.cmu.edu/~cx/papers/Explicit_Semantic_Ranking.pdf)]

__Joint event extraction via recurrent neural networks__. NAACL 2016. _Nguyen, Thien Huu and Cho, Kyunghyun and Grishman, Ralph_. [[Paper](https://www.aclweb.org/anthology/N16-1034)]

__Fine-grained Event Categorization with Heterogeneous Graph Convolutional Networks__. IJCAI 2019. _H. Peng, J. Li, Q. Gong, Y. Song, Y. Ning, K. Lai, and P.S. Yu_. [[Paper](https://www.ijcai.org/Proceedings/2019/0449.pdf)]


__TransNet: Translation-Based Network Representation Learning for Social Relation Extraction__. IJCAI 2017. _Tu, Cunchao and Zhang, Zhengyan and Liu, Zhiyuan and Sun, Maosong_. [[Paper](http://nlp.csai.tsinghua.edu.cn/~lzy/publications/ijcai2017_transnet.pdf)]

__Retrieving Textual Evidence for Knowledge Graph Facts__. ESWC 2019. _Gonenc Ercan, Shady Elbassuoni, and Katja Hose_. [[Paper](http://qweb.cs.aau.dk/factify/files/ESWC2019.pdf)]  

### Healthcare
__Constructing biomedical domain-specific knowledge graph with minimum supervision__ KAIS 2019. _Yuan, Jianbo and Jin, Zhiwei and Guo, Han and Jin, Hongxia and Zhang, Xianchao and Smith, Tristram and Luo, Jiebo_. [[Paper](https://link.springer.com/article/10.1007/s10115-019-01351-4)]

__Knowledge-driven Encode, Retrieve, Paraphrase for Medical Image Report Generation__. AAAI 2019. _Li, Christy Y and Liang, Xiaodan and Hu, Zhiting and Xing, Eric P_. [[Paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-LiChristy.629.pdf)]

__On the Generative Discovery of Structured Medical Knowledge__. KDD 2018. _C. Zhang, Y. Li, N. Du, W. Fan, and P.S. Yu_ [[Paper](https://dl.acm.org/doi/abs/10.1145/3219819.3220010)]

__Knowledge-aware Assessment of Severity of Suicide Risk for Early Intervention__. WWW 2019. _Gaur, Manas, Amanuel Alambo, Joy Prakash Sain, Ugur Kursuncu, Krishnaprasad Thirunarayan, Ramakanth Kavuluru, Amit Sheth, Randon S. Welton, and Jyotishman Pathak._ [[Paper](http://knoesis.org/sites/default/files/Suicide_Paper.pdf)]


### Software Engineering

__HDSKG: harvesting domain specific knowledge graph from content of webpages__. SANER 2017. _Zhao, Xuejiao and Xing, Zhenchang and Kabir, Muhammad Ashad and Sawada, Naoya and Li, Jing and Lin, Shang-Wei_. [[Paper](https://dr.ntu.edu.sg/bitstream/handle/10220/42426/Finalmain.pdf?sequence=1&isAllowed=y)]

__Improving API Caveats Accessibility by Mining API Caveats Knowledge Graph__. CSME 2018. _Li, Hongwei and Li, Sirui and Sun, Jiamou and Xing, Zhenchang and Peng, Xin and Liu, Mingwei and Zhao, Xuejiao_. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8530028)]

__DeepWeak: reasoning common software weaknesses via knowledge graph embedding__. SANER 2018. _Han, Zhuobing and Li, Xiaohong and Liu, Hongtao and Xing, Zhenchang and Feng, Zhiyong_. [[Paper](https://ieeexplore.ieee.org/abstract/document/8330232)]

__The structure and dynamics of knowledge network in domain-specific Q&A sites: a case study of stack overflow__. Empirical Software Engineering 2017. _Ye, Deheng and Xing, Zhenchang and Kapre, Nachiket_ [[Paper](https://link.springer.com/article/10.1007/s10664-016-9430-z)]

__Predicting semantically linkable knowledge in developer online forums via convolutional neural network__. ICASE 2016. _Xu, Bowen and Ye, Deheng and Xing, Zhenchang and Xia, Xin and Chen, Guibin and Li, Shanping_. [[Paper](https://ieeexplore.ieee.org/iel7/7579013/7582735/07582745.pdf)]

__Mining Analogical Libraries in Q&A Discussions — Incorporating Relational and Categorical Knowledge into Word Embedding__. SANER 2016. _Chunyang Chen, Sa Gao, and Zhenchang Xing_. [[Paper](https://chunyang-chen.github.io/publication/analogical_libraries.pdf)]

__TechLand: Assisting technology landscape inquiries with insights from stack overflow__. ICSME 2016. _Chen, Chunyang and Xing, Zhenchang and Han, Lei_. [[Paper](http://ccywch.github.io/chenchunyang.github.io/publication/techLand.pdf)]

### Computer Vision
__The More You Know: Using Knowledge Graphs for Image Classification__. CVPR 2017. _Marino, Kenneth and Salakhutdinov, Ruslan and Gupta, Abhinav_. [[Paper](https://arxiv.org/pdf/1612.04844)]

__I Know the Relationships: Zero-Shot Action Recognition via Two-Stream Graph Convolutional Networks and Knowledge Graphs__. AAAI 2019.
_Gao et al._ [[Paper](https://aaai.org/ojs/index.php/AAAI/article/view/4843/4716)] [[Code](https://github.com/junyuGao/Zero-Shot-Action-Recognition-with-Two-Stream-GCN)]

__WK-VQA: World Knowledge-enabled Visual Question Answering__
_Shah et al._ [[Paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4915/4788)]
### Other Applications

__Jointly Modeling Inter-Slot Relations by Random Walk on Knowledge Graphs for Unsupervised Spoken Language Understanding__. NAACL-HLT 2015. _Yun-Nung Chen, William Yang Wang, Alex Rudnicky_. [[Paper](http://www.cs.ucsb.edu/~william/papers/NAACL15_InterSlotRelation.pdf)]

__Hybrid Knowledge Routed Modules for Large-scale Object Detection__. NIPS 2018. _Chenhan Jiang, Hang Xu, Xiaodan Liang, and Liang Lin_. [[Paper](http://papers.nips.cc/paper/7428-hybrid-knowledge-routed-modules-for-large-scale-object-detection)] [[Code](https://github.com/chanyn/HKRM)]

__Knowledge questions from knowledge graphs__. SIGIR 2016. _Seyler, Dominic and Yahya, Mohamed and Berberich, Klaus_. [[Paper](https://arxiv.org/pdf/1610.09935)]

__One for All: Neural Joint Modeling of Entities and Events__. AAAI 2019. _Nguyen, Trung Minh and Nguyen, Thien Huu_. [[Paper](https://arxiv.org/pdf/1812.00195)]

__Linking named entities in tweets with knowledge base via user interest modeling__. KDD 2013. _Shen, Wei and Wang, Jianyong and Luo, Ping and Wang, Min_. [[Paper](http://chbrown.github.io/kdd-2013-usb/kdd/p68.pdf)]

__Knowledge Aware Conversation Generation with Reasoning on Augmented Graph__. 2019. _Zhibin Liu, Zheng-Yu Niu, Hua Wu, Haifeng Wang_. [[Paper](https://arxiv.org/pdf/1903.10245.pdf)]

__[⬆](#awesome-knowledge-graph)__
## Temporal Knowledge Graph
__HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding__. EMNLP 2018. _Dasgupta, Shib Sankar, Swayambhu Nath Ray, and Partha Talukdar._ [[Paper](http://www.aclweb.org/anthology/D18-1225)] [[Code](https://github.com/malllabiisc/HyTE)] [[Note](./notes/dynamic/HyTe.md)]

__Learning Sequence Encoders for Temporal Knowledge Graph Completion__. EMNLP 2018. _Garcia-Duran, Alberto and Dumančić, Sebastijan and Niepert, Mathias_. [[Paper](https://arxiv.org/pdf/1809.03202)] [[Code](https://github.com/nle-ml/mmkb)]

__Towards time-aware knowledge graph completion__. COLING 2016. _Jiang, Tingsong and Liu, Tianyu and Ge, Tao and Sha, Lei and Chang, Baobao and Li, Sujian and Sui, Zhifang_. [[Paper](http://aclweb.org/anthology/C16-1161)]

__Deriving validity time in knowledge graph__. WWW Workshop 2018. _Leblay, Julien and Chekol, Melisachew Wudage_. [[Paper](https://dl.acm.org/citation.cfm?id=3191639)]

__Recurrent Event Network for Reasoning over Temporal Knowledge Graphs__. ICLR 2019 Workshop. _Jin, Woojeong and Zhang, Changlin and Szekely, Pedro and Ren, Xiang_. [[Paper](https://arxiv.org/pdf/1904.05530)] [[Code](https://github.com/INK-USC/RENet)]

__Encoding temporal information for time-aware link prediction__. EMNLP 2016. _Jiang, Tingsong and Liu, Tianyu and Ge, Tao and Sha, Lei and Li, Sujian and Chang, Baobao and Sui, Zhifang_. [[Paper](https://www.aclweb.org/anthology/D16-1260)]

__Predicting the co-evolution of event and knowledge graphs__. FUSION 2016. _Estóeban, Cristobal and Tresp, Volker and Yang, Yinchong and Baier, Stephan and Krompaß, Denis_. [[Paper](https://arxiv.org/pdf/1512.06900)]

__Know-evolve: Deep temporal reasoning for dynamic knowledge graphs__. ICML 2017. _Trivedi, Rakshit and Dai, Hanjun and Wang, Yichen and Song, Le_. [[Paper](https://arxiv.org/pdf/1705.05742)]

__Acquiring temporal constraints between relations__. CIKM 2012. _Talukdar, Partha Pratim and Wijaya, Derry and Mitchell, Tom_. [[Paper](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/mitchell/ftp/pubs/talukdar-cikm12.pdf)]

__Coupled temporal scoping of relational facts__. WSDM 2012. _Talukdar, Partha Pratim and Wijaya, Derry and Mitchell, Tom_. [[Paper](http://www.cs.cmu.edu/afs/cs/user/mitchell/ftp/pubs/talukdar-wsdm12.pdf)]

__Dense event ordering with a multi-pass architecture__. TACL 2014. _Chambers, Nathanael and Cassidy, Taylor and McDowell, Bill and Bethard, Steven_. [[Paper](https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00182)]


__[⬆](#awesome-knowledge-graph)__
## Knowledge Graph Reasoning
__DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs__. NeurIPS 2019. _Ali Sadeghian, Mohammadreza Armandpour, Patrick Ding, Daisy Zhe Wang_. [[Paper](https://papers.nips.cc/paper/9669-drum-end-to-end-differentiable-rule-mining-on-knowledge-graphs.pdf)] [[Code](https://github.com/alisadeghian/DRUM)]

__Chain of Reasoning for Visual Question Answering__. NIPS 2018. _Wu, Chenfei and Liu, Jinlai and Wang, Xiaojie and Dong, Xuan_. [[Paper](https://papers.nips.cc/paper/7311-chain-of-reasoning-for-visual-question-answering.pdf)]

__Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering__. NIPS 2018. _Medhini Narasimhan, Svetlana Lazebnik, Alex Schwing_. [[Paper](http://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering)]

__Symbolic Graph Reasoning Meets Convolutions__. NIPS 2018. _Xiaodan Liang, Zhiting HU, Hao Zhang, Liang Lin, and Eric P. Xing_. [[Paper](http://papers.nips.cc/paper/7456-symbolic-graph-reasoning-meets-convolutions)]

__Variational Knowledge Graph Reasoning__. NAACL-HLT 2018. _Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Yang Wang_. [[Paper](https://arxiv.org/abs/1803.06581)]

__DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning__. EMNLP 2017. _Wenhan Xiong, Thien Hoang, William Yang Wang_. [[Paper](http://www.cs.ucsb.edu/~william/papers/DeepPath.pdf)] [[Code](https://github.com/xwhan/DeepPath)]

__Neural Symbolic Machines: Learning Semantic Parsers on Freebase with Weak Supervision__. ACL 2017. _Liang, Chen and Berant, Jonathan and Le, Quoc and Forbus, Kenneth D and Lao, Ni_. [[Paper](https://arxiv.org/pdf/1611.00020)]

__Efficient Inference and Learning in a Large Knowledge Base: Reasoning with Extracted Information using a Locally Groundable First-Order Probabilistic Logic__. MLJ 2015. _William Yang Wang, Kathryn Mazaitis, Ni Lao, William W. Cohen_. [[Paper](http://www.cs.ucsb.edu/~william/papers/ProPPR_MLJ_sub.pdf)] [[Code](https://github.com/TeamCohen/ProPPR/)]

__Reasoning with neural tensor networks for knowledge base completion__. NIPS 2013. _Socher, Richard and Chen, Danqi and Manning, Christopher D and Ng, Andrew_. [[Paper](https://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion.pdf)]

__Probabilistic reasoning via deep learning: Neural association models__. arXiv 2016. _Liu, Quan and Jiang, Hui and Evdokimov, Andrew and Ling, Zhen-Hua and Zhu, Xiaodan and Wei, Si and Hu, Yu_. [[Paper](https://arxiv.org/pdf/1603.07704.pdf)]

__Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks__. EACL 2017. _Das, Rajarshi and Neelakantan, Arvind and Belanger, David and McCallum, Andrew_. [[Paper](https://arxiv.org/pdf/1607.01426.pdf)] [[Code](https://rajarshd.github.io/ChainsofReasoning/)]

__Differentiable learning of logical rules for knowledge base reasoning__. NIPS 2017. _Yang, Fan and Yang, Zhilin and Cohen, William W_. [[Paper](https://papers.nips.cc/paper/6826-differentiable-learning-of-logical-rules-for-knowledge-base-reasoning.pdf)]

__Go for a walk and arrive at the answer: Reasoning over paths in knowledge bases using reinforcement learning__. ICLR 2017. _Das, Rajarshi and Dhuliawala, Shehzaad and Zaheer, Manzil and Vilnis, Luke and Durugkar, Ishan and Krishnamurthy, Akshay and Smola, Alex and McCallum, Andrew_. [[Paper](https://arxiv.org/pdf/1711.05851)]

__Iteratively Learning Embeddings and Rules for Knowledge Graph Reasoning__. WWW 2019. _Zhang, Wen and Paudel, Bibek and Wang, Liang and Chen, Jiaoyan and Zhu, Hai and Zhang, Wei and Bernstein, Abraham and Chen, Huajun_. [[Paper](https://arxiv.org/pdf/1903.08948)]

__Variational reasoning for question answering with knowledge graph__. AAAI 2018. _Zhang, Yuyu and Dai, Hanjun and Kozareva, Zornitsa and Smola, Alexander J and Song, Le_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16983/16176)]

__The winograd schema challenge__. Thirteenth International Conference on the Principles of Knowledge Representation and Reasoning 2012. _Levesque, Hector and Davis, Ernest and Morgenstern, Leora_. [[Paper](https://www.aaai.org/ocs/index.php/KR/KR12/paper/download/4492/4924)]

__Straight to the facts: Learning knowledge base retrieval for factual visual question answering__. ECCV 2018. _Narasimhan, Medhini and Schwing, Alexander G_. [[Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Medhini_Gulganjalli_Narasimhan_Straight_to_the_ECCV_2018_paper.pdf)]

__Inferring and executing programs for visual reasoning__. ICCV 2017. _Johnson, Justin and Hariharan, Bharath and van der Maaten, Laurens and Hoffman, Judy and Fei-Fei, Li and Lawrence Zitnick, C and Girshick, Ross_. [[Paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Johnson_Inferring_and_Executing_ICCV_2017_paper.pdf)]

__End-to-end differentiable proving__. NIPS 2017. _Rocktäschel, Tim and Riedel, Sebastian_. [[Paper](https://papers.nips.cc/paper/6969-end-to-end-differentiable-proving.pdf)]

__[⬆](#awesome-knowledge-graph)__

## One/few-Shot and Zero-Shot Learning
__One-Shot Relational Learning for Knowledge Graphs__. EMNLP 2018. _Xiong, Wenhan, Mo Yu, Shiyu Chang, Xiaoxiao Guo, and William Yang Wang._ [[Paper](https://arxiv.org/pdf/1808.09040)] [[Code](https://github.com/xwhan/One-shot-Relational-Learning)] [[Note](./notes/few-shot/one-shot-relational.md)]  

__Multi-Label Zero-Shot Learning with Structured Knowledge Graphs__. CVPR 2018. _Chung-Wei Lee, Wei Fang, Chih-Kuan Yeh, Yu-Chiang Frank Wang_. [[Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lee_Multi-Label_Zero-Shot_Learning_CVPR_2018_paper.pdf)]

__Rethinking Knowledge Graph Propagation for Zero-Shot Learning__. CVPR 2019. _Kampffmeyer, Michael and Chen, Yinbo and Liang, Xiaodan and Wang, Hao and Zhang, Yujia and Xing, Eric P_. [[Paper](https://arxiv.org/pdf/1805.11724.pdf)] [[Code](https://github.com/cyvius96/adgpm)]

__Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs__. CVPR 2018. _Xiaolong Wang, Yufei Ye, Abhinav Gupta_. [[Paper](https://arxiv.org/pdf/1803.08035.pdf)] [[Code](https://github.com/JudyYe/zero-shot-gcn)]

__Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification__. AAAI 2019. _Tianyu Gao, Xu Han, Zhiyuan Liu, Maosong Sun_. [[Paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-GaoTianyu.915.pdf)] [[Code](http://github.com/thunlp/HATT-Proto)]

__FewRel: A Large-Scale Supervised Few-Shot Relation Classification Dataset with State-of-the-Art Evaluation__. EMNLP 2018. _Han, Xu and Zhu, Hao and Yu, Pengfei and Wang, Ziyun and Yao, Yuan and Liu, Zhiyuan and Sun, Maosong_. [[Paper](https://arxiv.org/pdf/1810.10147)]

__[⬆](#awesome-knowledge-graph)__

## Domain-specific Knowledge Graphs
### Geospatial Knowledge Graphs
__Extending the YAGO2 Knowledge Graph with Precise Geospatial Knowledge__. ISWC 2019. _Nikolaos Karalis, Georgios Mandilaras, and Manolis Koubarakis_ [[Paper](http://cgi.di.uoa.gr/~koubarak/publications/2019/yago2geo_iswc2019.pdf)] [[Code](https://github.com/nkaralis/Yago_Extension)]

__Revisiting the Representation of and Need for Raw Geometries on the Linked Data Web__. CEUR Workshop Proceedings. [[Paper](http://ceur-ws.org/Vol-1809/article-04.p)]

__Design and Development of Linked Data from The National Map__. Semnantic Web Journal. _E. Lynn Usery and Dalia Varanka_ [[Paper](http://www.semantic-web-journal.net/sites/default/files/swj180_2.pdf)]

__Relaxing Unanswerable Geographic Questions Using A Spatially Explicit Knowledge Graph Embedding Model__ AGILE 2019. [[Paper](http://www.geog.ucsb.edu/~gengchen_mai/papers/2019-AGILE19_TransGeo.pdf)] [[Code](https://github.com/gengchenmai/TransGeo)]

__Enabling Spatio-Temporal Search in Open Data__. Journal of Web Semantics (JWS), Elsevier, 2018. _Sebastian Neumaier and Axel Polleres._ [[Paper](http://epub.wu.ac.at/6764/1/neumaier2018TR-enabling.pdf)]

## KG Database Systems
__Adaptive Low-level Storage of Very Large Knowledge Graphs__.
WWW 2020. _Urbani et al._. [[Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380246)]

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
- Google KG, https://developers.google.com/knowledge- graph
- A large-scale Chinese knowledge graph from [OwnThink](https://github.com/ownthink/KnowledgeGraph)
- GDELT（Global Database of Events, Language, and Tone）[Web](https://www.gdeltproject.org)

### Domain-specific Data
__OpenKG knowledge graphs about the novel coronavirus COVID-19__
- 新冠百科图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-baike)]  
Knowledge graph from encyclopedia[[Link](http://www.openkg.cn/dataset/2019-ncov-baike)]

- 新冠科研图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-research)]   
Knowledge graph of COVID-19 research [[Link](http://www.openkg.cn/dataset/2019-ncov-research)]

- 新冠临床图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-clinic)]  
Clinical knowledge graph [[Link](http://www.openkg.cn/dataset/2019-ncov-clinic)]

- 新冠英雄图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-hero)]  
Knowledge graph of people, experts, and heroes [[Link](http://www.openkg.cn/dataset/2019-ncov-hero)]

- 新冠热点事件图谱 [[链接](http://www.openkg.cn/dataset/2019-ncov-event)]  
Knowledge graph of public events [[Link](http://www.openkg.cn/dataset/2019-ncov-event)]

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
- OpenNRE, https://github.com/thunlp/OpenNRE

### Interactive APP
Knowledge graph APP, Simple knowledge graph applications can be easily built using JSON data managed entirely via a GraphQL layer. [[Github](https://github.com/epistemik-co/staple-api-kg-demo)] [[Website](http://demo.staple-api.org)]

## Courses, Tutorials and Seminars
### Courses
- Stanford CS 520 Knowledge Graphs: How should AI explicitly represent knowledge? _Vinay K. Chaudhri, Naren Chittar, Michael Genesereth_. [[Web](https://web.stanford.edu/class/cs520/)]
- Stanford CS 224W: Machine Learning with Graphs. _Jure Leskovec_. [[Web](http://web.stanford.edu/class/cs224w/index.html)]
- University of Bonn: Analysis of Knowledge Graphs. _Jens Lehmmann_. [[Web](https://sewiki.iai.uni-bonn.de/teaching/lectures/kga/2017/start)] [[GitHub](https://github.com/SmartDataAnalytics/Knowledge-Graph-Analysis-Programming-Exercises)]


## Related Repos
A repo about knowledge graph in Chinese - [husthuke/awesome-knowledge-graph](https://github.com/husthuke/awesome-knowledge-graph)

A repo about NLP, KG, Dialogue Systems in Chinese - [lihanghang/NLP-Knowledge-Graph](https://github.com/lihanghang/NLP-Knowledge-Graph)

Top-level Conference Publications on Knowledge Graph - [wds-seu/Knowledge-Graph-Publications](https://github.com/wds-seu/Knowledge-Graph-Publications)

Geospatial Knowledge Graphs - [semantic-geospatial](https://github.com/laurentlefort/semantic-geospatial/wiki/Geospatial-Knowledge-Graphs)

## Acknowledgements

Acknoledgements give to the following people who comment or contribute to this repository (listed chronologically).

- [DonaldTsang](https://github.com/DonaldTsang)
- [NYXFLOWER](https://github.com/NYXFLOWER)
- [Arun-George-Zachariah](https://github.com/Arun-George-Zachariah)  

__[⬆](#awesome-knowledge-graph)__
