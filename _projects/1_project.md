---
layout: page
title: COVID-19 X-Ray Detection
description: Detecting COVID-19, Pneumonia and Healthy X-Rays using PyTorch and Wandb
img: assets/img/xray_lung.png
importance: 2
category: computer vision
related_publications: false
---

The github repository for this project can be found [here](github.com/tharrmeehan/COVID19-XRay-Detection).

The goal of this project was to detect if a person has COVID-19, Pneumonia or if they are healthy by looking at their X-Ray images. A pretrained ResNet18 model was used for this task. The dataset was provided by Mendely Data and can be found [here](https://data.mendeley.com/datasets/dvntn9yhd2/1). 

PyTorch was used for model creation and traning. The model was done locally and wandb was used for tracking the model training process and visualizing the results. An example can be found [here](https://wandb.ai/tharrmeehan/XRay-COVID?nw=nwusertharrmeehan). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/xray_wandb.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    How the probabilities look like in wandb
</div>