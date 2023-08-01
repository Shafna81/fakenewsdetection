# fakenewsdetection
Source code of paper "Performance Analysis of Transformer Based Models (BERT, ALBERT and RoBERTa) in Fake News Detection"

#Datasets
This research uses 3 datasets that are combined into one. The first dataset is a dataset obtained from Mendeley, that can be accessed on the https://data.mendeley.com/datasets/p3hfgr5j3m/1. The next dataset is a dataset derived from github, Hoax News Classification, that can be accessed at https://github.com/pierobeat/Hoax-NewsClassification. While the last dataset is a dataset obtained through scrapping on https://turnbackhoax.id page. The scrapping results can be accessed at https://github.com/JibranFawaid/turnbackhoax-dataset.
The research stages when training and testing are carried out with the Python programming language in the Pytorch library. The BERT, ALBERT, and RoBERTa models were trained using Google Collaboration Pro with Python 3 runtime specifications, 25.5 GB of System RAM, T4 GPU hardware accelerator with 15 GB of GPU RAM, 166.8 GB of disk. To maintain consistency, we use a value of random seed 12 for all models.
