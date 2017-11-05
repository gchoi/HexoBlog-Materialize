---
title: Ultrasound Imaging Probe Detection using Convolutional Neural Networks
date: 2017-11-05 16:16:44
---

#### <span id="1">1. Introduction</span>
In HIFU treament system imaging probe sometimes gets damages due to HIFU reflection signals when the treament head is exposed to strong reflectors like air.

Thus, it is important to be able to detect in what circumstances the treatment head is exposed to avoid the damage.

In this project we applied the deep convolution neural networks to classify the treatment head state by the image input with which we can prevent HIFU transducer from transmitting when it is classified as air.

#### <span id="2">2. Methodolody</span>
* Collect images CNN can be trained on.
* Construct CNN model.
* Train.
* Test & Validation.

![Ratio between image classes](/images/projects/001-image-probe-protection/03-ratio-image-classification.png)
![Vectorize image pixel data](/images/projects/001-image-probe-protection/04-vectorize-image.png)
![CNN model structure](/images/projects/001-image-probe-protection/05-network-structure.png)
