---
layout: default
title: Benchmarking
---

We present two classification experiments performed using the 2019 version of the dataset to infer the main crop types present in each image. In the first experiment, *static classification*, we treated each individual image as a training instance (static image classification). In the second experiment, *dynamic classification* we explored the use of a temporal image series as an input. 

<p align="center"><img src="figures/benchmarking/classification_experiments.png" alt="Classification Experiment" width="1000"></p>
 

___

Tables showing results for both experiments are figured below.

### Static Classification

[Table for Static Classification Results]

### Dynamic Classification

The deep learning models used for the dynamic classification task include the [* 3 Dimensional Convolutional Network (3DCNN)*](https://arxiv.org/abs/2007.13224) and the [*Long-Term Recurrent Convolutional Networks (LRCN)*](https://arxiv.org/abs/1411.4389).    



| Model                     | Precision     | Recall          | F1-Score        | Accuracy       |
| :----------------         | :------:      | :------:        | :------:        | :------:       | 
| *Dynamic classification*  |               |                 |                 |                |       
| LRCN-64 (RGB)             | 0.610 ± 0.017 |  0.637 ± 0.015  |  0.617 ± 0.012  |  0.774 ± 0.014 |    

___





The deep learning models used for the dynamic classification task include the [* 3 Dimensional Convolutional Network (3DCNN)*](https://arxiv.org/abs/2007.13224) and the [*Long-Term Recurrent Convolutional Networks (LRCN)*](https://arxiv.org/abs/1411.4389).   

The deep learning models used for the static classification task include the [*ResNet-50*](https://arxiv.org/abs/1512.03385), the [*DenseNet*](https://arxiv.org/abs/1608.06993) and the [*EfficientNet-B0*](https://arxiv.org/abs/1905.11946).


<table style="border-collapse: collapse; table-layout: fixed; width: 100%;">
  <tr>
    <th style="border: 1px solid black; text-align: center;">Models/Metrics</th>
    <th style="border: 1px solid black; text-align: center;">Precision</th>
    <th style="border: 1px solid black; text-align: center;">Recall</th>
    <th style="border: 1px solid black; text-align: center;">F1-Score</th>
    <th style="border: 1px solid black; text-align: center;">Accuracy</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (RGB)</td>
    <td style="border: 1px solid black; text-align: center;">0.610 ± 0.017</td>
    <td style="border: 1px solid black; text-align: center;">0.637 ± 0.015</td>
    <td style="border: 1px solid black; text-align: center;">0.617 ± 0.013</td>
    <td style="border: 1px solid black; text-align: center;"><strong>0.774 ± 0.014</strong></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;">0.030 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.100 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.040 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.277 ± 0.006</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;">0.030 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.100 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.040 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
   

