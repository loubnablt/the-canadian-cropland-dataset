---
layout: default
title: Benchmarking
---

We present two classification experiments performed using the 2019 version of the dataset to infer the main crop types present in each image. In the first experiment, *static classification*, we treated each individual image as a training instance (static image classification). In the second experiment, *dynamic classification* we explored the use of a temporal image series as an input. 

<p align="center"><img src="/figures/benchmarking/classification_experiments.png" alt="Classification Experiment" width="1000"></p>
 

___

Tables showing results for both experiments are figured below.

### Static Classification

The deep learning models used for the static classification task include the [*ResNet-50*](https://arxiv.org/abs/1512.03385), the [*DenseNet*](https://arxiv.org/abs/1608.06993) and the [*EfficientNet-B0*](https://arxiv.org/abs/1905.11946).     

   
| Model                     | Precision     | Recall          | F1-Score        | Accuracy       |
| :----------------         | :------:      | :------:        | :------:        | :------:       | 
| *Static classification*   |               |                 |                 |                |       
| DENSENET-121 (RGB)        | 0.327 ± 0.064 |  0.330 ± 0.030  |  0.273 ± 0.058  | 0.403 ± 0.045  |    



### Dynamic Classification

The deep learning models used for the dynamic classification task include the [* 3 Dimensional Convolutional Network (3DCNN)*](https://arxiv.org/abs/2007.13224) and the [*Long-Term Recurrent Convolutional Networks (LRCN)*](https://arxiv.org/abs/1411.4389).    



| Model                     | Precision     | Recall          | F1-Score        | Accuracy       |
| :----------------         | :------:      | :------:        | :------:        | :------:       | 
| *Dynamic classification*  |               |                 |                 |                |       
| LRCN-64 (RGB)             | 0.610 ± 0.017 |  0.637 ± 0.015  |  0.617 ± 0.012  |  0.774 ± 0.014 |    

___



