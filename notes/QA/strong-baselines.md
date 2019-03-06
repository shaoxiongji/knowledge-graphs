Motivation: LSTM fine-tuning -> comparable performance  
Method: entity detection: CRF with features engineering; entity linking: n-gram inverse indexing, Levenshtein Distance; relation prediction: RNNs, CNNs, logistic regression (TF-IDF, bi-gram, word embedding, relation words); evidence integration: m entities and n relations -> 1 entity-relation  
Datasets: SimpleQuestions  
Experiments: entity linking, relation prediction, end2end QA 