# LSTM-NA
Network Alignment by Long Short Term Memory

In bioinformatics, the discovery of protein-protein interaction networks alignment is of great importance due to their utilization in identifying the cellular pathways, finding new medicines, and disease recognition. Most current methods require particular considerations such as the application of seed and extend strategy, and local mapping or side information. In this study, we try to propose an efficient alignment that does not have the above limitations. In this regard, we describe the network alignment issue in the form of a classification problem for the very first time and introduce a deep network that finds the alignment of nodes present in two networks. We call this method LSTM-NA, which means network alignment using Long Short Term Memory or LSTM. The suggested solution consists of three steps; in the first phase, we obtain the sequence and topological similarities from the networks’ structure. For the second phase, the dataset needed for the transformation of the problem into a classification problem is created from obtained properties. In the third phase, we predict the nodes’ alignment between two networks using deep learning. The LSTM-NA architecture is implemented using Keras deep learning API in python. For examination of the efficiency of our suggested method, we selected five biological species from protein-protein interaction (PPI) datasets of the Biogrid websites. The suggested LSTM-NA method is compared with three classification approaches of Support Vector Machine, K-Nearest Neighbors, and Linear Discriminant Analysis. The experimental results indicate the efficiency of the suggested LSTM-NA method and 100% accuracy in PPI networks alignment prediction. 

You can run all programs and see results for all biological species. The "Train_LSTM-NA_SC-AT_Biogrid.ipynb" program used to train the model in the Biogrid dataset. The "Train_LSTM-NA_EC-SC_Isobase.ipynb" used to train the model in Isobase dataset. The "test-tune_model_of_LSTM-NA_*.ipynb" files used to test the LSTM-NA tuned model.  


This project implemented by Elham Mahdipour, Ph.D. Graduate of Artificial Intelligence at Yazd University, Yazd, Iran. She is Faculty Member of Computer Engineering Department at Khavaran Institute of Higher Education, Mashhad, Iran.

The supervisor is Dr. Mohammad Ghasemzadeh, associate Prof. of Computer Engineering department at Yazd University. 

Please feel free and contact to me: e.mahdipour@profs.khi.ac.ir/ elham.mahdipour@gmail.com

All right reserved by the authors.
