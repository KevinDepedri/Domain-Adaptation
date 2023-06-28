# <p align="center">Deep Learning - Unsupervised Domain Adaptation</p> 

Unsupervised domain adaptation (UDA) is the task of training a statistical model on labeled data from a source domain to achieve better performance on data from a target domain, with access to only unlabeled data in the target domain.

The application of UDA techniques is essential to tackle the problem known as domain shift, which refers to the drop in performances that a neural network can be subjected to when it is dealing with different train and testing domain. In particular, this problem arises when a neural network has been trained over a source domain, and then it has been deployed at inference time over a target domain, which presents a shifted distribution with respect to the training domain.

The distribution of the used target dataset could be shifted intentionally (for example using real world pictures for the training, while using sketches for the testing), or it could be shifted in an unintentional way (for example due to changes in the environment where the pictures are acquired). Generally, when we refer to UDA, we are working with a source domain which is composed of fully-labeled samples, and with a target domain which is composed of unlabeled samples.
The goal of UDA techniques is to reduce as much as possible the drop in performances to which the neural networks are subjected as previously described

This repository is a student project developed by Kevin Depedri and Matteo Brugnera for the "Machine Learning - Deep Learning" course of the Master in Artificial Intelligent Systems at the University of Trento, a.y. 2022-2023.

The goal of this project is to build, train and evaluate a deep learning framework on a standard setting of Unsupervised Domain Adaptation (UDA).
