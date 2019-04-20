# Awesome Knowledge Graph
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of knowledge graph papers, codes, and reading notes.

- [Awesome Knowledge Graph](#awesome-knowledge-graph)
  - [Knowledge Graph Embedding](#knowledge-graph-embedding)
  - [Cross-Modal KG Embedding](#cross-modal-kg-embedding)
    - [Textual Desciption](#textual-desciption)
    - [Type Information](#type-information)
    - [Logic Rules](#logic-rules)
    - [Relational Path](#relational-path)
    - [Visual Information](#visual-information)
  - [Knowledge Acquisition](#knowledge-acquisition)
    - [Knowledge Graph Completion](#knowledge-graph-completion)
    - [Relation Extraction](#relation-extraction)
    - [Relation Classification](#relation-classification)
    - [Entity Alignment](#entity-alignment)
  - [Knownwledge-aware Applications](#knownwledge-aware-applications)
    - [Recommendation System](#recommendation-system)
    - [Question Answering](#question-answering)
    - [Conversation Generation](#conversation-generation)
    - [Software Engineering](#software-engineering)
    - [Other Applications](#other-applications)
  - [Dynamic Knowledge Graph](#dynamic-knowledge-graph)
  - [Knowledge Graph Reasoning](#knowledge-graph-reasoning)
  - [One/few-Shot and Zero-Shot](#onefew-shot-and-zero-shot)


## Knowledge Graph Embedding
__Variational Quantum Circuit Model for Knowledge Graph Embedding__. Advanced Quantum Technologies 2019. _Yunpu Ma, Volker Tresp, Liming Zhao, and Yuyi Wang_. [[Paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/qute.201800078)]

__Interaction Embeddings for Prediction and Explanation in Knowledge Graphs__. WSDM 2019. _Wen Zhang, Bibek Paudel, Wei Zhang, Abraham Bernstein, Huajun Chen_. [[Paper](https://www.zora.uzh.ch/id/eprint/162876/1/interaction-embeddings-prediction_merlin_version.pdf)]

__Does William Shakespeare Really Write Hamlet? Knowledge Representation Learning with Confidence__. AAAI 2018. _Ruobing Xie, Zhiyuan Liu, Fen Lin, and Leyu Lin_. [[Paper](https://arxiv.org/pdf/1705.03202.pdf)] [[Code](https://github.com/thunlp/CKRL)]

__Convolutional 2d knowledge graph embeddings__. AAAI 2018. _Dettmers, Tim and Minervini, Pasquale and Stenetorp, Pontus and Riedel, Sebastian_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/17366/15884)]

__Towards Understanding the Geometry of Knowledge Graph Embedding__. ACL 2018. _Chandrahas, Aditya Sharma and Partha Talukdar_. [[Paper](http://www.aclweb.org/anthology/P18-1012)] [[Code](https://github.com/malllabiisc/kg-geometry)] [[Note](./notes/embedding/kg-geometry.md)]   

__Co-training Embedding of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment__. IJCAI 2018, _Chen, Muhao, Yingtao Tian, Kai-Wei Chang, Steven Skiena, and Carlo Zaniolo_. [[Paper](https://arxiv.org/pdf/1806.06478.pdf)] [[Note](./notes/embedding/co-training.md)]   

__Scalable Rule Learning via Learning Representation__. IJCAI 2018. _Omran, Pouya Ghiasnezhad, Kewen Wang, and Zhe Wang._ [[Paper](https://www.ijcai.org/proceedings/2018/0297.pdf)] [[Note](./notes/embedding/rule-learning.md)]  

__KBGAN: Adversarial Learning for Knowledge Graph Embeddings__. NAACL 2018. _Cai, Liwei, and William Yang Wang_. [[Paper](https://arxiv.org/pdf/1711.04071.pdf)] [[Code](https://github.com/cai-lw/KBGAN)] [[Note](./notes/embedding/KBGAN.md)]  

__Embedding Logical Queries on Knowledge Graphs__. NIPS 2018. _William L. Hamilton, Payal Bajaj, Marinka Zitnik, Dan Jurafsky, and Jure Leskovec_. [[Paper](http://papers.nips.cc/paper/7473-embedding-logical-queries-on-knowledge-graphs.pdf)] [[Code](https://github.com/williamleif/graphqembed)]

__SimpIE Embedding for Link Prediction in Knowledge Graphs__. NIPS 2018. _Seyed Mehran Kazemi, David Poole_. [[Paper](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs)] [[Code](https://github.com/Mehran-k/SimplE)]

__Differentiating Concepts and Instances for Knowledge Graph Embedding__. EMNLP 2018. _Xin Lv, Lei Hou, Juanzi Li, Zhiyuan Liu_. [[Paper](http://aclweb.org/anthology/D18-1222)] [[Code](http://github.com/davidlvxin/TransC)]

__Analogical inference for multi-relational embeddings__. ICML 2017. _Liu, Hanxiao and Wu, Yuexin and Yang, Yiming_. [[Paper](https://arxiv.org/pdf/1705.02426.pdf)] [[Code](https://github.com/quark0/ANALOGY)]

__On the equivalence of holographic and complex embeddings for link prediction__. ACL 2017. _Hayashi, Katsuhiko and Shimbo, Masashi_. [[Paper](https://arxiv.org/pdf/1702.05563.pdf)]

__Holographic embeddings of knowledge graphs__. AAAI 2016. _Nickel, Maximilian and Rosasco, Lorenzo and Poggio, Tomaso_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewFile/12484/11828)]

__Complex embeddings for simple link prediction__. ICML 2016. _Trouillon, Théo and Welbl, Johannes and Riedel, Sebastian and Gaussier, Éric and Bouchard, Guillaume_. [[Paper](http://proceedings.mlr.press/v48/trouillon16.pdf)] [[Code](https://github.com/ttrouill/complex)]

__Embedding entities and relations for learning and inference in knowledge bases__. ICLR 2015. _Yang, Bishan and Yih, Wen-tau and He, Xiaodong and Gao, Jianfeng and Deng, Li_. [[Paper](https://arxiv.org/pdf/1412.6575.pdf)]

__Relation extraction with matrix factorization and universal schemas__. NAACL 2013. _Riedel, Sebastian and Yao, Limin and McCallum, Andrew and Marlin, Benjamin M_. [[Paper](http://www.aclweb.org/anthology/N13-1008)]

__A latent factor model for highly multi-relational data__. NIPS 2012. _Jenatton, Rodolphe and Roux, Nicolas L and Bordes, Antoine and Obozinski, Guillaume R_. [[Paper](https://papers.nips.cc/paper/4744-a-latent-factor-model-for-highly-multi-relational-data.pdf)]

__Factorizing YAGO: scalable machine learning for linked data__. ICML 2012. _Nickel, Maximilian and Tresp, Volker and Kriegel, Hans-Peter_. [[Paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.383.2015&rep=rep1&type=pdf)]

__A Three-Way Model for Collective Learning on Multi-Relational Data__. WWW 2011. _Nickel, Maximilian and Tresp, Volker and Kriegel, Hans-Peter_. [[Paper](http://www.dbs.ifi.lmu.de/~tresp/papers/p271.pdf)]

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

__[⬆](#awesome-knowledge-graph)__
## Cross-Modal KG Embedding
### Textual Desciption 
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

__[⬆](#awesome-knowledge-graph)__
## Knowledge Acquisition 
### Knowledge Graph Completion
__An Open-World Extention to Knowledge Graph Completion MOdels__. AAAI 2019. _Haseeb Shah, Johannes Villmow, Adrian Ulges, Ulrich Schwanecke, Faisal Shafait_. [[Paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-ShahH.6029.pdf)] [[Code](http://github.com/haseebs/OWE)]

__Embedding Multimodal Relational Data for Knowledge Base Completion__. EMNLP 2018. _Pezeshkpour, Pouya, Liyan Chen, and Sameer Singh._ [[Paper](https://arxiv.org/pdf/1809.01341.pdf)] [[Code](https://github.com/pouyapez/mkbe)] [[Note](./notes/completion/mkbe.md)]  

__Expanding Holographic Embeddings for Knowledge Completion__. NIPS 2018. _Yexiang Xue, Yang Yuan, Zhitian Xu, and Ashish Sabharwal_. [[Paper](http://papers.nips.cc/paper/7701-expanding-holographic-embeddings-for-knowledge-completion)]

__M-Walk: Learning to Walk over Graphs using Monte Carlo Tree Search__. NIPS 2018. Yelong Shen, Jianshu Chen, Po-Sen Huang, Yuqing Guo, Jianfeng Gao. [[Paper](http://papers.nips.cc/paper/7912-m-walk-learning-to-walk-over-graphs-using-monte-carlo-tree-search)]

__Compositional Vector Space Models for Knowledge Base Completion__. ACL-IJCNLP 2015. _Neelakantan, Arvind and Roth, Benjamin and McCallum, Andrew_. [[Paper](http://anthology.aclweb.org/P/P15/P15-1016.pdf)]

__An Interpretable Knowledge Transfer Model for Knowledge Base Completion__. ACL 2017. _Xie, Qizhe and Ma, Xuezhe and Dai, Zihang and Hovy, Eduard_. [[Paper](https://arxiv.org/pdf/1704.05908)]

__A novel embedding model for knowledge base completion based on convolutional neural network__. NAACL 2018. _Nguyen, Dai Quoc and Nguyen, Tu Dinh and Nguyen, Dat Quoc and Phung, Dinh_. [[Paper](https://arxiv.org/pdf/1712.02121)]

__ProjE: Embedding projection for knowledge graph completion__. AAAI 2017. _Shi, Baoxu and Weninger, Tim_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14279/13906)] [[Code](https://github.com/nddsg/ProjE)]

__TuckER: Tensor Factorization for Knowledge Graph Completion__. _Balažević, Ivana and Allen, Carl and Hospedales, Timothy M_.
[[Paper](https://arxiv.org/pdf/1901.09590.pdf)] [[Code](https://github.com/ibalazevic/TuckER)]

__Open-world knowledge graph completion__. AAAI 2018. _Shi, Baoxu and Weninger, Tim_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16055/15901)] [[Code](https://github.com/bxshi/ConMask)]

__On Multi-Relational Link Prediction with Bilinear Models__. AAAI 2018. _Wang, Yanjie and Gemulla, Rainer and Li, Hui_. [[Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16900/16722)] [[Code](http://dws.informatik.uni-mannheim.de/en/resources/software/tf/)]


### Relation Extraction
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

### Entity Alignment 
__Bootstrapping Entity Alignment with Knowledge Graph Embedding__.  IJCAI 2018. _Zequn Sun, Wei Hu, Qingheng Zhang and Yuzhong Qu._ [[Paper](https://www.ijcai.org/proceedings/2018/0611.pdf)] [[Code](https://github.com/nju-websoft/BootEA)] [[Note](./notes/embedding/BootEA.md)]  

__Cross-lingual entity alignment via joint attribute-preserving embedding__. ISWC 2017. _Sun, Zequn and Hu, Wei and Li, Chengkai_. [[Paper](https://arxiv.org/pdf/1708.05045)] 


__[⬆](#awesome-knowledge-graph)__
## Knownwledge-aware Applications
### Recommendation System
__Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation__. WWW 2019. _Wang, Hongwei, Fuzheng Zhang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://arxiv.org/pdf/1901.08907.pdf)] [[Code](https://github.com/hwwang55/MKR)]

__Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preference__. WWW 2019. _Yixin Cao, Xiang Wang, Xiangnan He, Zikun Hu, Tat-Seng Chua_.
[[Paper](https://www.comp.nus.edu.sg/~xiangnan/papers/www19-KGRec.pdf)] [[Code](https://github.com/TaoMiner/joint-kg-recommender)] [[Code](https://github.com/TaoMiner/joint-kg-recommender)]

__Explianable Reasoning over Knowledge Graphs for Recommendation__. AAAI 2019. _Wang, Xiang and Wang, Dingxian and Xu, Canran and He, Xiangnan and Cao, Yixin and Chua, Tat-Seng_. [[Paper](https://arxiv.org/abs/1811.04540)] [[Code](https://github.com/eBay/KPRN)]  

__Exploring High-Order User Preference on the Knowledge Graph for Recommender Systems__. TOIS 2019. _Hongwei Wang, Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://dl.acm.org/citation.cfm?id=3312738)]

__RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems__. CIKM 2018. _Hongwei Wang, Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://dl.acm.org/citation.cfm?id=3271739)]


### Question Answering

__Dialog-to-Action: Conversational Question Answering Over a Large-Scale Knowledge Base__. NIPS 2018. _Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin_. [[Paper](http://papers.nips.cc/paper/7558-dialog-to-action-conversational-question-answering-over-a-large-scale-knowledge-base)]

__Commonsense for Generative Multi-hop Question Answering Tasks__. EMNLP 2018. _Bauer, Lisa, Yicheng Wang, and Mohit Bansal._ [[Paper](https://arxiv.org/pdf/1809.06309.pdf)] [[Code](https://github.com/yicheng-w/CommonSenseMultiHopQA)] [[Note](./notes/QA/multi-hop.md)]  

__EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs__. ISWC 2018. _Dubey, Mohnish, Debayan Banerjee, Debanjan Chaudhuri, and Jens Lehmann._ [[Paper](https://arxiv.org/pdf/1801.03825.pdf)] [[Note](./notes/QA/EARL.md)]  

__Pattern-revising Enhanced Simple Question Answering over Knowledge Bases__. COLING 2018. _Hao, Yanchao, Hao Liu, Shizhu He, Kang Liu, and Jun Zhao._ [[Paper](http://www.aclweb.org/anthology/C18-1277)] [[Note](./notes/QA/pattern-revising.md)]  

__Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks__. NAACL 2018. _Mohammed, Salman, Peng Shi, and Jimmy Lin._ [[Paper](https://arxiv.org/pdf/1712.01969.pdf)] [[Note](./notes/QA/strong-baselines.md)]     

__Transliteration Better than Translation? Answering Code-mixed Questions over a Knowledge Base__. ACL 2018. _Gupta, Vishal, Manoj Chinnakotla, and Manish Shrivastava._ [[Paper](http://www.aclweb.org/anthology/W18-3205)] [[Note](./notes/QA/code-mixed.md)]  

__TEQUILA: Temporal Question Answering over Knowledge Bases__. CIKM 2018. _Zhen Jia, Abdalghani Abujabal, Rishiraj Saha Roy, Jannik Strötgen, Gerhard Weikum_. [[Paper](https://dl.acm.org/citation.cfm?id=3269247&dl=ACM&coll=DL)]

### Conversation Generation  
__Commonsense Knowledge Aware Conversation Generation with Graph Attention__. IJCAI 2018. _Zhou, Hao, Tom Young, Minlie Huang, Haizhou Zhao, Jingfang Xu, and Xiaoyan Zhu._ [[Paper](https://www.ijcai.org/proceedings/2018/0643.pdf)] [[Note](./notes/conversation/commonsense.md)]    

### Software Engineering

__HDSKG: harvesting domain specific knowledge graph from content of webpages__. SANER 2017. _Zhao, Xuejiao and Xing, Zhenchang and Kabir, Muhammad Ashad and Sawada, Naoya and Li, Jing and Lin, Shang-Wei_. [[Paper](https://dr.ntu.edu.sg/bitstream/handle/10220/42426/Finalmain.pdf?sequence=1&isAllowed=y)]

__Improving API Caveats Accessibility by Mining API Caveats Knowledge Graph__. CSME 2018. _Li, Hongwei and Li, Sirui and Sun, Jiamou and Xing, Zhenchang and Peng, Xin and Liu, Mingwei and Zhao, Xuejiao_. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8530028)]

__DeepWeak: reasoning common software weaknesses via knowledge graph embedding__. SANER 2018. _Han, Zhuobing and Li, Xiaohong and Liu, Hongtao and Xing, Zhenchang and Feng, Zhiyong_. [[Paper](https://ieeexplore.ieee.org/abstract/document/8330232)]

__The structure and dynamics of knowledge network in domain-specific Q&A sites: a case study of stack overflow__. Empirical Software Engineering 2017. _Ye, Deheng and Xing, Zhenchang and Kapre, Nachiket_ [[Paper](https://link.springer.com/article/10.1007/s10664-016-9430-z)]

__Predicting semantically linkable knowledge in developer online forums via convolutional neural network__. ICASE 2016. _Xu, Bowen and Ye, Deheng and Xing, Zhenchang and Xia, Xin and Chen, Guibin and Li, Shanping_. [[Paper](https://ieeexplore.ieee.org/iel7/7579013/7582735/07582745.pdf)]

__Mining Analogical Libraries in Q&A Discussions — Incorporating Relational and Categorical Knowledge into Word Embedding__. SANER 2016. _Chunyang Chen, Sa Gao, and Zhenchang Xing_. [[Paper](https://chunyang-chen.github.io/publication/analogical_libraries.pdf)]

__TechLand: Assisting technology landscape inquiries with insights from stack overflow__. ICSME 2016. _Chen, Chunyang and Xing, Zhenchang and Han, Lei_. [[Paper](http://ccywch.github.io/chenchunyang.github.io/publication/techLand.pdf)]


### Other Applications
__Knowledge-aware Assessment of Severity of Suicide Risk for Early Intervention__. WWW 2019. _Gaur, Manas, Amanuel Alambo, Joy Prakash Sain, Ugur Kursuncu, Krishnaprasad Thirunarayan, Ramakanth Kavuluru, Amit Sheth, Randon S. Welton, and Jyotishman Pathak._ [[Paper](http://knoesis.org/sites/default/files/Suicide_Paper.pdf)] 

__Jointly Modeling Inter-Slot Relations by Random Walk on Knowledge Graphs for Unsupervised Spoken Language Understanding__. NAACL-HLT 2015. _Yun-Nung Chen, William Yang Wang, Alex Rudnicky_. [[Paper](http://www.cs.ucsb.edu/~william/papers/NAACL15_InterSlotRelation.pdf)]

__Hybrid Knowledge Routed Modules for Large-scale Object Detection__. NIPS 2018. _Chenhan Jiang, Hang Xu, Xiaodan Liang, and Liang Lin_. [[Paper](http://papers.nips.cc/paper/7428-hybrid-knowledge-routed-modules-for-large-scale-object-detection)] [[Code](https://github.com/chanyn/HKRM)]

__[⬆](#awesome-knowledge-graph)__
## Dynamic Knowledge Graph
__HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding__. EMNLP 2018. _Dasgupta, Shib Sankar, Swayambhu Nath Ray, and Partha Talukdar._ [[Paper](http://www.aclweb.org/anthology/D18-1225)] [[Code](https://github.com/malllabiisc/HyTE)] [[Note](./notes/dynamic/HyTe.md)]  

__[⬆](#awesome-knowledge-graph)__
## Knowledge Graph Reasoning
__Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering__. NIPS 2018. _Medhini Narasimhan, Svetlana Lazebnik, Alex Schwing_. [[Paper](http://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering)] 

__Symbolic Graph Reasoning Meets Convolutions__. NIPS 2018. _Xiaodan Liang, Zhiting HU, Hao Zhang, Liang Lin, and Eric P. Xing_. [[Paper](http://papers.nips.cc/paper/7456-symbolic-graph-reasoning-meets-convolutions)]

__Variational Knowledge Graph Reasoning__. NAACL-HLT 2018. _Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Yang Wang_. [[Paper](https://arxiv.org/abs/1803.06581)] 

__DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning__. EMNLP 2017. _Wenhan Xiong, Thien Hoang, William Yang Wang_. [[Paper](http://www.cs.ucsb.edu/~william/papers/DeepPath.pdf)] [[Code](https://github.com/xwhan/DeepPath)]

__Efficient Inference and Learning in a Large Knowledge Base: Reasoning with Extracted Information using a Locally Groundable First-Order Probabilistic Logic__. MLJ 2015. _William Yang Wang, Kathryn Mazaitis, Ni Lao, William W. Cohen_. [[Paper](http://www.cs.ucsb.edu/~william/papers/ProPPR_MLJ_sub.pdf)] [[Code](https://github.com/TeamCohen/ProPPR/)]

__Reasoning with neural tensor networks for knowledge base completion__. NIPS 2013. _Socher, Richard and Chen, Danqi and Manning, Christopher D and Ng, Andrew_. [[Paper](https://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion.pdf)]

__Probabilistic reasoning via deep learning: Neural association models__. arXiv 2016. _Liu, Quan and Jiang, Hui and Evdokimov, Andrew and Ling, Zhen-Hua and Zhu, Xiaodan and Wei, Si and Hu, Yu_. [[Paper](https://arxiv.org/pdf/1603.07704.pdf)]

__Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks__. EACL 2017. _Das, Rajarshi and Neelakantan, Arvind and Belanger, David and McCallum, Andrew_. [[Paper](https://arxiv.org/pdf/1607.01426.pdf)] [[Code](https://rajarshd.github.io/ChainsofReasoning/)]

__Differentiable learning of logical rules for knowledge base reasoning__. NIPS 2017. _Yang, Fan and Yang, Zhilin and Cohen, William W_. [[Paper](https://papers.nips.cc/paper/6826-differentiable-learning-of-logical-rules-for-knowledge-base-reasoning.pdf)]

__Go for a walk and arrive at the answer: Reasoning over paths in knowledge bases using reinforcement learning__. ICLR 2017. _Das, Rajarshi and Dhuliawala, Shehzaad and Zaheer, Manzil and Vilnis, Luke and Durugkar, Ishan and Krishnamurthy, Akshay and Smola, Alex and McCallum, Andrew_. [[Paper](https://arxiv.org/pdf/1711.05851)]

__[⬆](#awesome-knowledge-graph)__
## One/few-Shot and Zero-Shot
__One-Shot Relational Learning for Knowledge Graphs__. EMNLP 2018. _Xiong, Wenhan, Mo Yu, Shiyu Chang, Xiaoxiao Guo, and William Yang Wang._ [[Paper](https://arxiv.org/pdf/1808.09040)] [[Code](https://github.com/xwhan/One-shot-Relational-Learning)] [[Note](./notes/few-shot/one-shot-relational.md)]  

__Multi-Label Zero-Shot Learning with Structured Knowledge Graphs__. CVPR 2018. _Chung-Wei Lee, Wei Fang, Chih-Kuan Yeh, Yu-Chiang Frank Wang_. [[Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lee_Multi-Label_Zero-Shot_Learning_CVPR_2018_paper.pdf)]

__Rethinking Knowledge Graph Propagation for Zero-Shot Learning__. 2018. _Kampffmeyer, Michael and Chen, Yinbo and Liang, Xiaodan and Wang, Hao and Zhang, Yujia and Xing, Eric P_. [[Paper](https://arxiv.org/pdf/1805.11724.pdf)] [[Code](https://github.com/cyvius96/adgpm)]

__Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs__. CVPR 2018. _Xiaolong Wang, Yufei Ye, Abhinav Gupta_. [[Paper](https://arxiv.org/pdf/1803.08035.pdf)] [[Code](https://github.com/JudyYe/zero-shot-gcn)]

__Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification__. AAAI 2019. _Tianyu Gao, Xu Han, Zhiyuan Liu, Maosong Sun_. [[Paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-GaoTianyu.915.pdf)] [[Code](http://github.com/thunlp/HATT-Proto)]

__[⬆](#awesome-knowledge-graph)__