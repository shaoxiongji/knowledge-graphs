Motivation: multilingual KG; low coverage of entity alignment; literal description of entities   
Method: 1) KGEM: knowledge model(TransE), alignment model(MTransE); 2) DEM: attentive gated recurrent unit encoder(AGRU), cross-lingual embedding; 3) KDCoE: iterative co-training.  
Datasets: WK3160k extracted from DBPedia  
Experiments: cross-lingual entity aligment & zero-shot aligment(Hit@1, Hit@10, MRR), cross-lingual knowledge completion (proportion of ranks no larger than 10 Hit@10, mean reciprocal rank MRR)
