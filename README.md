## This Repo is for CSE 256 LIGN 256 - Statistical Natural Lang Proc - Nakashole [FA24] PA3
### Author: [Zhecheng Li](https://github.com/Lizhecheng02) && Professor: [Ndapa Nakashole](https://ndapa.us/)

### Prepare Data
All datasets are already in the GitHub repo.

### Run Codes
Run ``PA3_CSE256.ipynb`` directly. (It is recommended to use GPUs such as the NVIDIA RTX 3090)

### Tips
When using a full transformer encoder model like BERT to obtain sentence embeddings, you need to normalize the generated embeddings. This is because pre-trained language models like BERT are not the same as sentence transformer models (e.g., bge, gte), which are specifically trained for calculating cosine similarity and have already been normalized during training and inference.

### Questions

You are welcome to discuss any issues you encounter while running this GitHub repository. Feel free to either open an issue or contact me directly at **zhl186@ucsd.edu**.