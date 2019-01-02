# Knowledge Graph

A curated list of knowledge graph papers and reading notes.

- [Knowledge Graph](#knowledge-graph)
  - [Relation Extraction](#relation-extraction)
  - [KG Embedding](#kg-embedding)
  - [One-shot KG](#one-shot-kg)
  - [Dynamic knowledge graph](#dynamic-knowledge-graph)
  - [Question answering](#question-answering)
  - [Conversation Generation](#conversation-generation)
  
## Relation Extraction
__Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning__  
```@EMNLP2018```  
distance supervised relation extraction  
Motivation: false annotation, inner-sentence noise, random feature extraction is not robust  
Proposed method:  
- STP: Sub-Tree Parser
- BGRU: Bidirectional GRU, entity-wise neural extractor 
- transfer learning: entity classification -> relation extraction 

Experiments: held-out evaluation, manual evaluation 

## KG Embedding
__Co-training Embedding of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment__  
```@IJCAI18```  
inter-language links, ILLs   
multilingual KG  
semi-supervised  
Proposed method: 
- KGEM: knowledge model(TransE), alignment model(MTransE).
- DEM: attentive gated recurrent unit encoder(AGRU), cross-lingual embedding
- KDCoE: iterative co-training  

Datasets: DBPedia -> WK3160k  
Experiments: cross-lingual entity aligment & zero-shot aligment(Hit@1, Hit@10, MRR), cross-lingual knowledge completion (proportion of ranks no larger than 10 Hit@10, mean reciprocal rank MRR)

__Enhanced Network Embeddings via Exploiting Edge Labels__  
```@CIKM2018```  
Motivation: network structure, semantic information of edge  
Proposed method:
- structural loss: context node
- relational loss: edges 

Experiments: multi-label node classification  
Datasets: ArnetMiner, AmazonReviews 

__Scalable Rule Learning via Learning Representation__  
```@IJCAI2018```  
Definitions: closed-pathrule, support degree of r, standard confidence, head coverage  
Proposed method:
- sampling method
- argument embedding 
- co-occurrence socre function
- rule evaluation

Datasets: FB15K-237, FB75K, YAGO2s, Wikidata, DBpedia 3.8 

## One-shot KG
__One-Shot Relational Learning for Knowledge Graphs__  
```EMNLP2018```  
Motivation: long-tail in KG, one-shot setting, metric learning  
Proposed method:
- neighbor encoder: subgraph, one-hop neighbor set, encoding
- matching processor: LSTM encoding, similarity 

Datasets: NELL-one, Wiki-One derived from NELL, Wikidata

## Dynamic knowledge graph
__HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding__  
```@EMNLP18```  
Code: https://github.com/malllabiisc/HyTE  
Method: graph embedding method considering temporal scopes, represent time as a hyperplane  
Experiments: link prediction, temporal scoping  
Datasets: YAGO11k, Wikidata12k  (with time annotations)

## Question answering
__Commonsense for Generative Multi-hop Question Answering Tasks__  
```@EMNLP18```  
Method: ConceptNet multi-hop path from common sense  
Experiments: generative QA  
Datasets: NarrativeQA  
Baseline model: embedding layer, reasoning layer, model layer(self-attention, BiLSTM), answer layer (pointer-generator decoder)  
Commonsense: multi-hop path, PMI socring, choose path like beam search  


__EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs__  
```@ISWC18```  
Challenge for knowledge base question answering: 
1. identification and linking of entities
2. identification and linking of relations
3. identification of query intent
4. generating formal query

Preprocessing: keyword tokenizer, entity relation predictor, candidate generation  
Disambiguation: 1) GTSP solver 2) connection density, adaptive learning  
Dataset: LC-QuAD

__Pattern-revising Enhanced Simple Question Answering over Knowledge Bases__  
```@COLING2018```  
subject-predicate ranking  
pattern extraction, pattern revising, joint fact selection  
Datasets: SimpleQuestions, freebase(FB2M, FB5M)

__Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks__  
```@NAACL2018```   
Motivation: LSTM fine-tuning -> comparable performance  
Proposed methods: 
- entity detection: CRF with features engineering
- entity linking: n-gram inverse indexing, Levenshtein Distance 
- relation prediction: RNNs, CNNs, logistic regression (TF-IDF, bi-gram, word embedding, relation words)
- evidence integration: m entities and n relations -> 1 entity-relation 

Datasets: SimpleQuestions
Experiments: entity linking, relation prediction, end2end QA  

## Conversation Generation  
__Commonsense Knowledge Aware Conversation Generation with Graph Attention__   
```@IJCAI2918```  
Problems: OOV  -> commonsense KG -> triplet without semantic meaning of subgraph  
Proposed Mehtod: commonsense knowledge aware conversational model, CCM 
- subgraph
- static graph attention
- dynamic graph attention  
- encoder-decoder seq2seq  

Datasets: ConceptNet, reddit post-response  
Metirc: perplexity, entity score, crowdsourcing(appropriateness, informativeness)  