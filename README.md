# Knowledge Graph

A collection of knowledge graph papers, codes, and reading notes.

- [Knowledge Graph](#knowledge-graph)
  - [Knowledge Graph Embedding](#knowledge-graph-embedding)
  - [Knowledge Graph Completion](#knowledge-graph-completion)
  - [Relation Extraction](#relation-extraction)
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

__Bootstrapping Entity Alignment with Knowledge Graph Embedding__.  IJCAI 2018. _Zequn Sun, Wei Hu, Qingheng Zhang and Yuzhong Qu._ [[Paper](https://www.ijcai.org/proceedings/2018/0611.pdf)] [[Code](https://github.com/nju-websoft/BootEA)] [[Note](./notes/embedding/BootEA.md)]  

__Does William Shakespeare Really Write Hamlet? Knowledge Representation Learning with Confidence__. AAAI 2018. _Ruobing Xie, Zhiyuan Liu, Fen Lin, and Leyu Lin_. [[Paper](https://arxiv.org/pdf/1705.03202.pdf)] [[Code](https://github.com/thunlp/CKRL)]

__Towards Understanding the Geometry of Knowledge Graph Embedding__. ACL 2018. _Chandrahas, Aditya Sharma and Partha Talukdar_. [[Paper](http://www.aclweb.org/anthology/P18-1012)] [[Code](https://github.com/malllabiisc/kg-geometry)] [[Note](./notes/embedding/kg-geometry.md)]   

__Co-training Embedding of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment__. IJCAI 2018, _Chen, Muhao, Yingtao Tian, Kai-Wei Chang, Steven Skiena, and Carlo Zaniolo_. [[Paper](https://arxiv.org/pdf/1806.06478.pdf)] [[Note](./notes/embedding/co-training.md)]   

__Enhanced Network Embeddings via Exploiting Edge Labels__. CIKM 2018. _Chen, Haochen, Xiaofei Sun, Yingtao Tian, Bryan Perozzi, Muhao Chen, and Steven Skiena._ [[Paper](https://arxiv.org/pdf/1809.05124.pdf)] [[Note](./notes/embedding/edge-labels.md)]   

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

__Context-dependent knowledge graph embedding__. EMNLP 2015. _Luo, Yuanfei and Wang, Quan and Wang, Bin and Guo, Li_. [[Paper](http://www.aclweb.org/anthology/D15-1191)]

__Compositional learning of embeddings for relation paths in knowledge base and text__. ACL 2016. _Toutanova, Kristina and Lin, Victoria and Yih, Wen-tau and Poon, Hoifung and Quirk, Chris_. [[Paper](http://www.aclweb.org/anthology/P16-1136)]

__GAKE: graph aware knowledge embedding__. COLING 2016. _Feng, Jun and Huang, Minlie and Yang, Yang and Zhu, Xiaoyan_. [[Paper](http://www.aclweb.org/anthology/C16-1062)]

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

__Modeling relation paths for representation learning of knowledge bases__. EMNLP 2015. _Lin, Yankai and Liu, Zhiyuan and Luan, Huanbo and Sun, Maosong and Rao, Siwei and Liu, Song_. [[Paper](https://arxiv.org/pdf/1506.00379.pdf)] [[Code](https://github.com/mrlyk423/relation_extraction)]

__Composing relationships with translations__. EMNLP 2015. _García-Durán, Alberto and Bordes, Antoine and Usunier, Nicolas_. [[Paper](http://www.aclweb.org/anthology/D15-1034)] [[Code](https://github.com/glorotxa/SME)]


## Knowledge Graph Completion
__Embedding Multimodal Relational Data for Knowledge Base Completion__. EMNLP 2018. _Pezeshkpour, Pouya, Liyan Chen, and Sameer Singh._ [[Paper](https://arxiv.org/pdf/1809.01341.pdf)] [[Code](https://github.com/pouyapez/mkbe)] [[Note](./notes/completion/mkbe.md)]  

__Expanding Holographic Embeddings for Knowledge Completion__. NIPS 2018. _Yexiang Xue, Yang Yuan, Zhitian Xu, and Ashish Sabharwal_. [[Paper](http://papers.nips.cc/paper/7701-expanding-holographic-embeddings-for-knowledge-completion)]

__M-Walk: Learning to Walk over Graphs using Monte Carlo Tree Search__. NIPS 2018. Yelong Shen, Jianshu Chen, Po-Sen Huang, Yuqing Guo, Jianfeng Gao. [[Paper](http://papers.nips.cc/paper/7912-m-walk-learning-to-walk-over-graphs-using-monte-carlo-tree-search)]

__Compositional Vector Space Models for Knowledge Base Completion__. ACL-IJCNLP 2015. _Neelakantan, Arvind and Roth, Benjamin and McCallum, Andrew_. [[Paper](http://anthology.aclweb.org/P/P15/P15-1016.pdf)]


## Relation Extraction
__Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks__. NAACL 2019. _Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, Huajun Chen_. [[Paper](https://arxiv.org/abs/1903.01306)]  

__Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning__. EMNLP 2018. _Liu, Tianyi, Xinsong Zhang, Wanhao Zhou, and Weijia Jia._ [[Paper](https://arxiv.org/pdf/1808.06738.pdf)] [[Note](./notes/RE/inner-sentence.md)]  

__DSGAN: Generative Adversarial Training for Robust Distant Supervision Relation Extraction__. ACL 2018. _Pengda Qin, Weiran Xu, William Yang Wang_. [[Paper](https://arxiv.org/pdf/1805.09929.pdf)]

__Deep Residual Learning for Weakly-Supervised Relation Extraction__. EMNLP 2017. _Yi Yao Huang, William Yang Wang_. [[Paper](http://www.cs.ucsb.edu/~william/papers/ResCNN.pdf)]
[[Code](https://github.com/darrenyaoyao/ResCNN_RelationExtraction)]

## Recommendation System
__Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation__. WWW 2019. _Wang, Hongwei, Fuzheng Zhang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo_. [[Paper](https://arxiv.org/pdf/1901.08907.pdf)] [[Code](https://github.com/hwwang55/MKR)]

__Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preference__. WWW 2019. _Yixin Cao, Xiang Wang, Xiangnan He, Zikun Hu, Tat-Seng Chua_.
[[Paper](https://www.comp.nus.edu.sg/~xiangnan/papers/www19-KGRec.pdf)] [[Code](https://github.com/TaoMiner/joint-kg-recommender)] [[Code](https://github.com/TaoMiner/joint-kg-recommender)]

__Explianable Reasoning over Knowledge Graphs for Recommendation__. AAAI 2019. _Wang, Xiang and Wang, Dingxian and Xu, Canran and He, Xiangnan and Cao, Yixin and Chua, Tat-Seng_. [[Paper](https://arxiv.org/abs/1811.04540)] [[Code](https://github.com/eBay/KPRN)]  




## Question Answering

__Dialog-to-Action: Conversational Question Answering Over a Large-Scale Knowledge Base__. NIPS 2018. _Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin_. [[Paper](http://papers.nips.cc/paper/7558-dialog-to-action-conversational-question-answering-over-a-large-scale-knowledge-base)]

__Commonsense for Generative Multi-hop Question Answering Tasks__. EMNLP 2018. _Bauer, Lisa, Yicheng Wang, and Mohit Bansal._ [[Paper](https://arxiv.org/pdf/1809.06309.pdf)] [[Code](https://github.com/yicheng-w/CommonSenseMultiHopQA)] [[Note](./notes/QA/multi-hop.md)]  

__EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs__. ISWC 2018. _Dubey, Mohnish, Debayan Banerjee, Debanjan Chaudhuri, and Jens Lehmann._ [[Paper](https://arxiv.org/pdf/1801.03825.pdf)] [[Note](./notes/QA/EARL.md)]  

__Pattern-revising Enhanced Simple Question Answering over Knowledge Bases__. COLING 2018. _Hao, Yanchao, Hao Liu, Shizhu He, Kang Liu, and Jun Zhao._ [[Paper](http://www.aclweb.org/anthology/C18-1277)] [[Note](./notes/QA/pattern-revising.md)]  

__Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks__. NAACL 2018. _Mohammed, Salman, Peng Shi, and Jimmy Lin._ [[Paper](https://arxiv.org/pdf/1712.01969.pdf)] [[Note](./notes/QA/strong-baselines.md)]     

__Transliteration Better than Translation? Answering Code-mixed Questions over a Knowledge Base__. ACL 2018. _Gupta, Vishal, Manoj Chinnakotla, and Manish Shrivastava._ [[Paper](http://www.aclweb.org/anthology/W18-3205)] [[Note](./notes/QA/code-mixed.md)]  

__TEQUILA: Temporal Question Answering over Knowledge Bases__. CIKM 2018. _Zhen Jia, Abdalghani Abujabal, Rishiraj Saha Roy, Jannik Strötgen, Gerhard Weikum_. [[Paper](https://dl.acm.org/citation.cfm?id=3269247&dl=ACM&coll=DL)]

## Conversation Generation  
__Commonsense Knowledge Aware Conversation Generation with Graph Attention__. IJCAI 2018. _Zhou, Hao, Tom Young, Minlie Huang, Haizhou Zhao, Jingfang Xu, and Xiaoyan Zhu._ [[Paper](https://www.ijcai.org/proceedings/2018/0643.pdf)] [[Note](./notes/conversation/commonsense.md)]    

## Software Engineering

__HDSKG: harvesting domain specific knowledge graph from content of webpages__. SANER 2017. _Zhao, Xuejiao and Xing, Zhenchang and Kabir, Muhammad Ashad and Sawada, Naoya and Li, Jing and Lin, Shang-Wei_. [[Paper](https://dr.ntu.edu.sg/bitstream/handle/10220/42426/Finalmain.pdf?sequence=1&isAllowed=y)]

__Improving API Caveats Accessibility by Mining API Caveats Knowledge Graph__. CSME 2018. _Li, Hongwei and Li, Sirui and Sun, Jiamou and Xing, Zhenchang and Peng, Xin and Liu, Mingwei and Zhao, Xuejiao_. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8530028)]

__DeepWeak: reasoning common software weaknesses via knowledge graph embedding__. SANER 2018. _Han, Zhuobing and Li, Xiaohong and Liu, Hongtao and Xing, Zhenchang and Feng, Zhiyong_. [[Paper](https://ieeexplore.ieee.org/abstract/document/8330232)]

__The structure and dynamics of knowledge network in domain-specific Q&A sites: a case study of stack overflow__. Empirical Software Engineering 2017. _Ye, Deheng and Xing, Zhenchang and Kapre, Nachiket_ [[Paper](https://link.springer.com/article/10.1007/s10664-016-9430-z)]

__Predicting semantically linkable knowledge in developer online forums via convolutional neural network__. ICASE 2016. _Xu, Bowen and Ye, Deheng and Xing, Zhenchang and Xia, Xin and Chen, Guibin and Li, Shanping_. [[Paper](https://ieeexplore.ieee.org/iel7/7579013/7582735/07582745.pdf)]

__Mining Analogical Libraries in Q&A Discussions — Incorporating Relational and Categorical Knowledge into Word Embedding__. SANER 2016. _Chunyang Chen, Sa Gao, and Zhenchang Xing_. [[Paper](https://chunyang-chen.github.io/publication/analogical_libraries.pdf)]

__TechLand: Assisting technology landscape inquiries with insights from stack overflow__. ICSME 2016. _Chen, Chunyang and Xing, Zhenchang and Han, Lei_. [[Paper](http://ccywch.github.io/chenchunyang.github.io/publication/techLand.pdf)]


## Other Applications
__Knowledge-aware Assessment of Severity of Suicide Risk for Early Intervention__. WWW 2019. _Gaur, Manas, Amanuel Alambo, Joy Prakash Sain, Ugur Kursuncu, Krishnaprasad Thirunarayan, Ramakanth Kavuluru, Amit Sheth, Randon S. Welton, and Jyotishman Pathak._ [[Paper](http://knoesis.org/sites/default/files/Suicide_Paper.pdf)] 

__Jointly Modeling Inter-Slot Relations by Random Walk on Knowledge Graphs for Unsupervised Spoken Language Understanding__. NAACL-HLT 2015. _Yun-Nung Chen, William Yang Wang, Alex Rudnicky_. [[Paper](http://www.cs.ucsb.edu/~william/papers/NAACL15_InterSlotRelation.pdf)]

__Hybrid Knowledge Routed Modules for Large-scale Object Detection__. NIPS 2018. _Chenhan Jiang, Hang Xu, Xiaodan Liang, and Liang Lin_. [[Paper](http://papers.nips.cc/paper/7428-hybrid-knowledge-routed-modules-for-large-scale-object-detection)] [[Code](https://github.com/chanyn/HKRM)]

## Dynamic Knowledge Graph
__HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding__. EMNLP 2018. _Dasgupta, Shib Sankar, Swayambhu Nath Ray, and Partha Talukdar._ [[Paper](http://www.aclweb.org/anthology/D18-1225)] [[Code](https://github.com/malllabiisc/HyTE)] [[Note](./notes/dynamic/HyTe.md)]  

## Knowledge Graph Reasoning
__Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering__. NIPS 2018. _Medhini Narasimhan, Svetlana Lazebnik, Alex Schwing_. [[Paper](http://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering)] 

__Symbolic Graph Reasoning Meets Convolutions__. NIPS 2018. _Xiaodan Liang, Zhiting HU, Hao Zhang, Liang Lin, and Eric P. Xing_. [[Paper](http://papers.nips.cc/paper/7456-symbolic-graph-reasoning-meets-convolutions)]

__Variational Knowledge Graph Reasoning__. NAACL-HLT 2018. _Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Yang Wang_. [[Paper](https://arxiv.org/abs/1803.06581)] 

__DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning__. EMNLP 2017. _Wenhan Xiong, Thien Hoang, William Yang Wang_. [[Paper](http://www.cs.ucsb.edu/~william/papers/DeepPath.pdf)] [[Code](https://github.com/xwhan/DeepPath)]

__Efficient Inference and Learning in a Large Knowledge Base: Reasoning with Extracted Information using a Locally Groundable First-Order Probabilistic Logic__. MLJ 2015. _William Yang Wang, Kathryn Mazaitis, Ni Lao, William W. Cohen_. [[Paper](http://www.cs.ucsb.edu/~william/papers/ProPPR_MLJ_sub.pdf)] [[Code](https://github.com/TeamCohen/ProPPR/)]

__Reasoning with neural tensor networks for knowledge base completion__. NIPS 2013. _Socher, Richard and Chen, Danqi and Manning, Christopher D and Ng, Andrew_. [[Paper](https://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion.pdf)]

__Probabilistic reasoning via deep learning: Neural association models__. arXiv 2016. _Liu, Quan and Jiang, Hui and Evdokimov, Andrew and Ling, Zhen-Hua and Zhu, Xiaodan and Wei, Si and Hu, Yu_. [[Paper](https://arxiv.org/pdf/1603.07704.pdf)]

__Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks__. EACL 2017. _Das, Rajarshi and Neelakantan, Arvind and Belanger, David and McCallum, Andrew_. [[Paper](https://arxiv.org/pdf/1607.01426.pdf)] [[Code](https://rajarshd.github.io/ChainsofReasoning/)]

## One/few-Shot and Zero-Shot
__One-Shot Relational Learning for Knowledge Graphs__. EMNLP 2018. _Xiong, Wenhan, Mo Yu, Shiyu Chang, Xiaoxiao Guo, and William Yang Wang._ [[Paper](https://arxiv.org/pdf/1808.09040)] [[Code](https://github.com/xwhan/One-shot-Relational-Learning)] [[Note](./notes/few-shot/one-shot-relational.md)]  

__Multi-Label Zero-Shot Learning with Structured Knowledge Graphs__. CVPR 2018. _Chung-Wei Lee, Wei Fang, Chih-Kuan Yeh, Yu-Chiang Frank Wang_. [[Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lee_Multi-Label_Zero-Shot_Learning_CVPR_2018_paper.pdf)]

__Rethinking Knowledge Graph Propagation for Zero-Shot Learning__. 2018. _Kampffmeyer, Michael and Chen, Yinbo and Liang, Xiaodan and Wang, Hao and Zhang, Yujia and Xing, Eric P_. [[Paper](https://arxiv.org/pdf/1805.11724.pdf)] [[Code](https://github.com/cyvius96/adgpm)]

__Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs__. CVPR 2018. _Xiaolong Wang, Yufei Ye, Abhinav Gupta_. [[Paper](https://arxiv.org/pdf/1803.08035.pdf)] [[Code](https://github.com/JudyYe/zero-shot-gcn)]