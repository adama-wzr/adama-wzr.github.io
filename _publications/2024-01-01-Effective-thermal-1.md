---
title: "Effective Thermal Conductivity Estimation Using a Convolutional Neural Network and Its Application in Topology Optimization"
collection: publications
category: manuscripts
permalink: /publication/2024-01-01-Effective-thermal-1
excerpt: 'Fast estimation of effective thermal conductivity for 2D binary structures using convolutional neural networks applied in topology optimization test cases.'
date: 2024-01-1
venue: 'Energy and AI'
paperurl: 'https://doi.org/10.1016/j.egyai.2023.100310'
citation: 'Andre Adam, Huazhen Fang, Xianglin Li, Effective thermal conductivity estimation using a convolutional neural network and its application in topology optimization, Energy and AI, Volume 15, 2024, 100310, ISSN 2666-5468, https://doi.org/10.1016/j.egyai.2023.100310.'
---

In this study, a convolutional neural network (CNN) model for predicting effective thermal conductivity inspired by the VGG networks is proposed. Trained using 130,000 unique binary images, the model achieves high predictive accuracy. The model is blind to physics, thus the predictions are purely based on the microstructure and data acquired through training. Nonetheless, it reaches unprecedented accuracy with a mean absolute percent error (MAPE) of 0.35% in testing at a thermal conductivity ratio of 10, and the accuracy drops to a MAPE of 2.35% when the thermal conductivities considered are that of aluminum and water.

This model proves quite useful when applied in topology optimization tasks, especially efficient in comparison to conventional CFD models in such tasks. The prediction time is 3 - 5 orders of magnitude faster, and the small MAPEs don't have a negative effect in the overall optimization process. This work is a proof of concenpt that predictive models based on computer vision can be extremely accurate and reliable for optimization tasks.

Two GitHub repositories stem from this work, as well as a dataset publication. They are as follows:
* [Trained CNNs](https://github.com/adama-wzr/CNN-Keff)
* [Effective Thermal Conductivity Estimation](https://github.com/adama-wzr/Keff-CFD)
* [Dataset](https://data.mendeley.com/datasets/454dsrmdyf/2)