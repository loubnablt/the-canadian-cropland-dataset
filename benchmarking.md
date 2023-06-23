---
layout: default
title: Benchmarking
---
We present two classification experiments performed using the 2019 version of the dataset to infer the main crop types present in each image. In the first experiment, *static classification*, we treated each individual image as a training instance (static image classification). In the second experiment, *dynamic classification* we explored the use of a temporal image series as an input. 
s
<img src="figures/classification_experiments.png" alt="Classification Experiment" width="1000">
 
___

Tables showing results for both experiments are figured below.

### Static Classification

[Table for Static Classification Results]

### Dynamic Classification

[Table for Dynamic Classification Results]



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
   

