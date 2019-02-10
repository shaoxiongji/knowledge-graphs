# Knowledge Graph

A curated list of knowledge graph Papers and reading notes.

- [Knowledge Graph](#knowledge-graph)
  - [Knowledge Graph Embedding](#knowledge-graph-embedding)
  - [Knowledge Graph Completion](#knowledge-graph-completion)
  - [Triple Classification](#triple-classification)
  - [Relation Extraction](#relation-extraction)
  - [Knowledge Graph Reasoning](#knowledge-graph-reasoning)
  - [Recommendation System](#recommendation-system)
  - [Question Answering](#question-answering)
  - [Conversation Generation](#conversation-generation)
  - [One-shot Knowledge Graph](#one-shot-knowledge-graph)
  - [Dynamic Knowledge Graph](#dynamic-knowledge-graph)

## Knowledge Graph Embedding
__Bootstrapping Entity Alignment with Knowledge Graph Embedding__.  IJCAI 2018. _Zequn Sun, Wei Hu, Qingheng Zhang and Yuzhong Qu._ [[Paper](https://www.ijcai.org/proceedings/2018/0611.pdf)] [[Code](https://github.com/nju-websoft/BootEA)]  
Motivation: lack of enough prior alignment  
Method: bootstrapping approach to embedding-based entity alignment; alignment editing   
Datasets: DBP15K, DWY100K  

__Towards Understanding the Geometry of Knowledge Graph Embedding__. ACL 2018. _Chandrahas, Aditya Sharma and Partha Talukdar_. [[Paper](http://www.aclweb.org/anthology/P18-1012)] [[Code](https://github.com/malllabiisc/kg-geometry)]   
Motivation: to fill the gap between effectiveness of KG embeddings and their geometric understanding.  
Metrics: 1) ATM, alignment to mean; 2) Conicity; 3) VS, vector spread; 4) AVL, average vector length  
Datasets: Freebase(FB15k), WordNet(WN18)

__Co-training Embedding of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment__. IJCAI 2018, _Chen, Muhao, Yingtao Tian, Kai-Wei Chang, Steven Skiena, and Carlo Zaniolo_. [[Paper](https://arxiv.org/pdf/1806.06478.pdf)]   
Motivation: multilingual KG; low coverage of entity alignment; literal description of entities   
Method: 1) KGEM: knowledge model(TransE), alignment model(MTransE); 2) DEM: attentive gated recurrent unit encoder(AGRU), cross-lingual embedding; 3) KDCoE: iterative co-training.  
Datasets: WK3160k extracted from DBPedia  
Experiments: cross-lingual entity aligment & zero-shot aligment(Hit@1, Hit@10, MRR), cross-lingual knowledge completion (proportion of ranks no larger than 10 Hit@10, mean reciprocal rank MRR)

__Enhanced Network Embeddings via Exploiting Edge Labels__. CIKM 2018. _Chen, Haochen, Xiaofei Sun, Yingtao Tian, Bryan Perozzi, Muhao Chen, and Steven Skiena._ [[Paper](https://arxiv.org/pdf/1809.05124.pdf)]   
Motivation: network structure, semantic information of edge  
Proposed method: structural loss: context node; relational loss: edges  
Datasets: ArnetMiner, AmazonReviews  
Experiments: multi-label node classification  

__Scalable Rule Learning via Learning Representation__. IJCAI 2018. _Omran, Pouya Ghiasnezhad, Kewen Wang, and Zhe Wang._ [[Paper](https://www.ijcai.org/proceedings/2018/0297.pdf)]  
Motivation: learning first-order rules, scalable techniques  
Definitions: closed-pathrule, support degree of r, standard confidence, head coverage  
Proposed method: sampling method; argument embedding; co-occurrence socre function; rule evaluation  
Datasets: FB15K-237, FB75K, YAGO2s, Wikidata, DBpedia 3.8 

__KBGAN: Adversarial Learning for Knowledge Graph Embeddings__. NAACL 2018. _Cai, Liwei, and William Yang Wang_. [[Paper](https://arxiv.org/pdf/1711.04071.pdf)] [[Code](https://github.com/cai-lw/KBGAN)]  
Motivation: knowledge graphs typically only contain positive facts.  
Method: GAN for negtive sample generation.  
Experiments: link prediction using FB15k-237, WN18 and WN18RR  

## Knowledge Graph Completion
__Embedding Multimodal Relational Data for Knowledge Base Completion__. EMNLP 2018. _Pezeshkpour, Pouya, Liyan Chen, and Sameer Singh._ [[Paper](https://arxiv.org/pdf/1809.01341.pdf)] [[Code](https://github.com/pouyapez/mkbe)]  
Motivation: embedding triplet and multimodal data into vector space  
Methods: encoders: multimodal data into vector; decoders: generate multi-modal values  
Datasets: MovieLens-100k, YAGO-10   
Experiments: link prediction, generating text and images

## Triple Classification


## Relation Extraction
__Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning__. EMNLP 2018. _Liu, Tianyi, Xinsong Zhang, Wanhao Zhou, and Weijia Jia._ [[Paper](https://arxiv.org/pdf/1808.06738.pdf)]  
Motivation: distance supervised relation extraction; false annotation, inner-sentence noise, random feature extraction is not robust.  
Method: 1) STP: Sub-Tree Parser; BGRU: Bidirectional GRU, entity-wise neural extractor; 3) transfer learning: entity classification -> relation extraction  
Experiments: held-out evaluation, manual evaluation 

## Knowledge Graph Reasoning
__Variational Knowledge Graph Reasoning__. NAACL-HLT 2018. _Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Yang Wang_. [[Paper](https://arxiv.org/abs/1803.06581)] 


## Recommendation System


## Question Answering
__Commonsense for Generative Multi-hop Question Answering Tasks__. EMNLP 2018. _Bauer, Lisa, Yicheng Wang, and Mohit Bansal._ [[Paper](https://arxiv.org/pdf/1809.06309.pdf)] [[Code](https://github.com/yicheng-w/CommonSenseMultiHopQA)]  
Method: ConceptNet multi-hop path from common sense  
Experiments: generative QA  
Datasets: NarrativeQA  
Baseline model: embedding layer, reasoning layer, model layer(self-attention, BiLSTM), answer layer (pointer-generator decoder)  
Commonsense: multi-hop path, PMI socring, choose path like beam search  


__EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs__. ISWC 2018. _Dubey, Mohnish, Debayan Banerjee, Debanjan Chaudhuri, and Jens Lehmann._ [[Paper](https://arxiv.org/pdf/1801.03825.pdf)]  
Motivation: identification and linking of entities; identification and linking of relations; identification of query intent; generating formal query
Preprocessing: keyword tokenizer, entity relation predictor, candidate generation  
Disambiguation: 1) GTSP solver 2) connection density, adaptive learning  
Dataset: LC-QuAD

__Pattern-revising Enhanced Simple Question Answering over Knowledge Bases__. COLING 2018. _Hao, Yanchao, Hao Liu, Shizhu He, Kang Liu, and Jun Zhao._ [[Paper](http://www.aclweb.org/anthology/C18-1277)]  
Motivation: learn to rank subject-predicate pairs  
Method: pattern extraction, pattern revising, joint fact selection  
Datasets: SimpleQuestions, freebase(FB2M, FB5M)

__Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks__. NAACL 2018. _Mohammed, Salman, Peng Shi, and Jimmy Lin._ [[Paper](https://arxiv.org/pdf/1712.01969.pdf)]    
Motivation: LSTM fine-tuning -> comparable performance  
Method: entity detection: CRF with features engineering; entity linking: n-gram inverse indexing, Levenshtein Distance; relation prediction: RNNs, CNNs, logistic regression (TF-IDF, bi-gram, word embedding, relation words); evidence integration: m entities and n relations -> 1 entity-relation  
Datasets: SimpleQuestions  
Experiments: entity linking, relation prediction, end2end QA  

__Transliteration Better than Translation? Answering Code-mixed Questions over a Knowledge Base__. ACL 2018. _Gupta, Vishal, Manoj Chinnakotla, and Manish Shrivastava._ [[Paper](http://www.aclweb.org/anthology/W18-3205)]  
Task: code-mix simple questions KBQA  
Method: Triplet-Siamese-Hybrid CNN, TSHCNN; triplet inputs: 1) questions, 2) positive/negtive tuple, 3) questions and positive/negative tuple  
Datasets: SimpleQuestions (Bordes et al., 2015) dataset，75.9k/10.8k/21.7k training/validation/test  


## Conversation Generation  
__Commonsense Knowledge Aware Conversation Generation with Graph Attention__. IJCAI 2018. _Zhou, Hao, Tom Young, Minlie Huang, Haizhou Zhao, Jingfang Xu, and Xiaoyan Zhu._ [[Paper](https://www.ijcai.org/proceedings/2018/0643.pdf)] 
Problems: OOV  -> commonsense KG -> triplet without semantic meaning of subgraph  
Proposed Mehtod: commonsense knowledge aware conversational model, CCM; subgraph, static graph attention; dynamic graph attention; encoder-decoder seq2seq  
Datasets: ConceptNet, reddit post-response  
Metirc: perplexity, entity score, crowdsourcing(appropriateness, informativeness)  


## One-shot Knowledge Graph
__One-Shot Relational Learning for Knowledge Graphs__. EMNLP 2018. _Xiong, Wenhan, Mo Yu, Shiyu Chang, Xiaoxiao Guo, and William Yang Wang._ [[Paper](https://arxiv.org/pdf/1808.09040)] [[Code](https://github.com/xwhan/One-shot-Relational-Learning)]  
Motivation: long-tail in KG, one-shot setting, metric learning  
Proposed method: 1) neighbor encoder: subgraph, one-hop neighbor set, encoding; 2) matching processor: LSTM encoding, similarity  
Datasets: NELL-one, Wiki-One derived from NELL, Wikidata  

## Dynamic Knowledge Graph
__HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding__. EMNLP 2018. _Dasgupta, Shib Sankar, Swayambhu Nath Ray, and Partha Talukdar._ [[Paper](http://www.aclweb.org/anthology/D18-1225)] [[Code](https://github.com/malllabiisc/HyTE)]  
Method: graph embedding method considering temporal scopes, represent time as a hyperplane  
Experiments: link prediction, temporal scoping  
Datasets: YAGO11k, Wikidata12k  (with time annotations)