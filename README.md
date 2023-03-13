# ANLPA2


### Neural Networks
* Data preprocessing: noise and punctuation removal, tokenization
* Word Embeddings: pretrained 300 dimensional word2vec ([link](https://fasttext.cc/docs/en/english-vectors.html))
* Deep Network: LSTM, biLSTM, CNN 

| Approach            | F1-Score |
| :------------------ | :------: |
| LSTM + w2v_wiki     | 0.7395   |
| biLSTM + w2v_wiki   | 0.7414   |
| CNN + w2v_wiki      | 0.7580   |

### Transfer learning with BERT
Finetuning BERT for text classification

| Approach            | F1-Score |
| :------------------ | :------: |
| finetuned BERT      | 0.8320   |
