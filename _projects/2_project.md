---
layout: page
title: Broadening 3D-CAD to People who are Blind
description: an assistive design tool that provides textual, creative feedback on 3D object resemblance, eliminating the need for a physical 3D printout and reducing the design iteration time for designers who are blind.
img: assets/img/cs230-example-title.png
importance: 2
category: academic
---

This project was a group effort, submitted for CS 230: Deep Learning (Stanford University, Spring 2022).

<b>Abstract</b>
3D CAD design is an essential component of making education and several engineering domains. However, this design process remains generally inaccessible to makers and designers who are blind and visually impaired, as it often requires the designer who is blind to 3D print a physical version of the model to receive any haptic feedback on it before iterating again to incorporate design improvements.
We propose a tool incorporating a deep learning network, inspired by the PointNet architecture, that provides textual/verbal creative feedback on the object resemblance of the designed 3D mode using multi-label classification, eliminating the need for a physical 3D printout and reducing the design iteration time and resource requirements. The network is trained on the ModelNet40 dataset with the tuning of three hyperparameters: learning rate, regularization, and batch size.
Additional data augmentation efforts can provide room for improvement in future work.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cs230-pipeline.png" title="Proposed Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The proposed tool’s experimental pipeline, consisting of User Interface, Application Script, Training Pipeline, and Dataset blocks.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cs230-training.png" title="Proposed Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The classification results of a 3D CAD model of a cup at three consecutive stages of the design process: (a) a sealed cylinder model (b) a hollow cylinder model (c) a misaligned cylinder model.
</div>
