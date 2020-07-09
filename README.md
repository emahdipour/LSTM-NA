# LSTM-NA
Network Alignment by Long Short Term Memory

In bioinformatics, the discovery of protein-protein interaction networks is of great importance due to their utilization in identifying the cellular pathways, finding new medicines, and disease recognition. Most current methods require particular considerations such as the application of seed and extend strategy, and local mapping or side information. In this study, we try to propose an efficient alignment that does not have the above limitations. In this regard, we describe the network alignment issue in the form of a classification problem for the very first time and introduce a deep network that finds the alignment of nodes present in two networks. We call this method LSTM-NA, which means network alignment using Long Short Term Memory or LSTM. The suggested solution consists of three steps; in the first phase, we obtain the sequence and topological similarities from the networks’ structure. For the second phase, the dataset needed for the transformation of the problem into a classification problem is created from obtained properties. In the third phase, we predict the nodes’ alignment between two networks using deep learning. The LSTM-NA architecture is implemented using Keras deep learning API in python. For examination of the efficiency of our suggested method, we selected five biological species from protein-protein interaction (PPI) datasets of the Biogrid/Isobase websites. The suggested LSTM-NA method is compared with three classification approaches of Support Vector Machine, K-Nearest Neighbors, and Linear Discriminant Analysis. The experimental results indicate the efficiency of the suggested LSTM-NA method and 100% accuracy in PPI networks alignment prediction. 


This project implemented by Elham Mahdipour, Ph.D. candidate of Artificial Intelligence at Yazd University, Yazd, Iran. 

The supervisor is Dr. Mohammad Ghasemzadeh, associate Prof. of Computer Engineering department at Yazd University. 

Please feel free and contact to me: elham.mahdipour@stu.yazd.ac.ir/ elham.mahdipour@gmail.com

All right reserved by the authors.
