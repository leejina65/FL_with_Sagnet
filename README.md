# SagFL : FL_with_Sagnet

## Introduction
With the increasing use of edge devices, research on data security and efficient communication costs in deep learning is becoming crucial. While federated learning addresses some of these challenges, it is difficult to achieve high performance due to the non-independent and identically distributed (Non-IID) nature of user data. To overcome this, we propose a novel model called SagFL by combining the state-of-the-art domain generalization technique, SAGNet, with federated learning (FedAvg). In particular, we investigate the training performance of the SagFL model using non-IID data distributions. This approach aims to address the generalization issues inherent in such diverse datasets and enhance the overall performance of federated learning.


## Information
* Federated Learning with Sagnet

By combining the Sagnet model with the best Domain Generalization performance through dataset Pacs with FedAvg, a federated learning learning algorithm that performs global updates by performing local updates several times, SagFL is implemented.


## Requirement
* Python
* Pytorch
* Torchvision

---- The files used are in ```src```. 

---- Main file is  ```federated_main.py```.


## Data
##### Pacs (4 domain)
filename : ```dataset```
- Photo (1,670 images)
- Art Painting (2,048 images)
- Cartoon (2,344 images)
- Sketch (3,929 images)

