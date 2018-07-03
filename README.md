# imdb_fasttext
This example demonstrates the use of fasttext for text classification
Based on Joulin et al's paper:
Bags of Tricks for Efficient Text Classification
https://arxiv.org/abs/1607.01759
Results on IMDB datasets with uni and bi-gram embeddings:
    Uni-gram: 88.13% test accuracy after 5 epochs. 8s/epoch on i7 cpu.
    Bi-gram : 90.56% test accuracy after 5 epochs. 2s/epoch on GTx 980M gpu.
