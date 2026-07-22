# MRH-GCL

# MRH-GCL: Multi-Relational Hierarchical Graph Contrastive Learning for Drug Repositioning
This repository contains the official implementation of MRH-GCL, a novel drug repositioning method that integrates multiple biological entities (drugs, diseases, proteins) and employs hierarchical graph contrastive learning to predict potential drug–disease associations.

# Running Experiments
python main.py -id 0 -da Bdataset -sp results -se 42 -fo 10 -ep 2000 -lr 0.001 -wd 1e-5 -pa 200 -hf 256 -dp 0.3 -k 20 -cl_lambda 0.1 -cl_temp 0.5

# Citation
If you use this code, please cite our paper (details to be added upon publication).
