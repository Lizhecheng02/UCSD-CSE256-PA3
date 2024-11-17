## This Repo is for CSE 256 LIGN 256 - Statistical Natural Lang Proc - Nakashole [FA24] PA3
### Author: [Zhecheng Li](https://github.com/Lizhecheng02) && Professor: [Ndapa Nakashole](https://ndapa.us/)

### Prepare Data
All datasets are already in the GitHub repo.

### Run Codes
Run ``PA3_CSE256.ipynb`` directly (recommend to use GPUs such as RTX3090).

### Tips
When using a full transformer encoder model like BERT to obtain sentence embeddings, you need to normalize the generated embeddings. This is because pre-trained language models like BERT are not the same as sentence transformer models (e.g., bge, gte), which are specifically trained for calculating cosine similarity and have already been normalized during training and inference.