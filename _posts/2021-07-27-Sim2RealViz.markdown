---
layout: post
title: "Sim2RealViz"
fulltitle: "Sim2RealViz: Visualizing the Sim2Real Gap in Robot Ego-Pose Estimation"
date: 2021-07-27 13:32:20 +0300
description: "Sim2RealViz, is a visual analytics tool to assist experts in understanding and reducing this gap for robot ego-pose estimation tasks, i.e. the estimation of a robot’s position using trained models"

img: sim2realViz.png
fig-caption: " Using Sim2RealViz, the Sim2Real gap of a Data Augmentation model can be compared against other models (e. g., Vanilla or Fine-tuned) and displayed on the real-world environment mapalong with its performance metrics. In particular,Sim2RealVIZ shows ① this model is particularly effective in simulation but we identified errors in the environment, such as the model failing to regress its position because of a closed-door that was opened in training. Such an error can then be selected by instance on the map ② to identify key features extracted by the model either as superimposed on the heat-map ③ or as a first-person view. ④"

authors: "Théo Jaunet, Guillaume Bono, Romain Vuillemot, Christian Wolf"

conf: XAI4Debugging @ NeurIPS 2021

teaser: sim2realViz.png
git: https://github.com/Theo-Jaunet/sim2realViz
test: ok
paper: https://arxiv.org/pdf/2109.11801.pdf

bibtex_first: "@article{jaunet2021sim2real,"
bibtex_end: "}"
bibtex_content: "author={Jaunet, Theo and Bono, Guillaume and Vuillemot, Romain and Wolf, Christian},

title = {Sim2RealViz: Visualizing the Sim2Real Gap in Robot Ego-Pose Estimation},

journal = {{arXiv preprint arXiv:2109.11801.},

year = {2021},
"




---


## Abstract

The Robotics community has started to heavily rely on increasingly realistic 3D simulators for large-scale training of robots on massive amounts of data. But once robots are deployed in the real-world, the simulation gap, as well as changes in the real-world (e.g. lights, objects displacements) lead to errors. In this paper, we introduce SIM2REALVIZ, a visual analytics tool to assist experts in understanding and reducing this gap for robot ego-pose estimation tasks, i. e.  the estimation of a robot’s position using trained models.SIM2REALVIZ displays details of a given model and the performance of its instances in both simulation and real-world. Experts can identify environment differences that impact model predictions at a given location and explore through direct interactions with the model hypothesis to fix it. We detail the design of the tool, and case studies related to the exploit of the regression to the mean bias and how it can be addressed, and how models are perturbed by vanishing landmarks such as bikes.








