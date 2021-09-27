---
layout: post
title: "Sim2RealViz"
fulltitle: "Sim2RealViz: Visualizing the Sim2Real Gap in Robot Ego-Pose Estimation"
date: 2021-07-27 13:32:20 +0300
description: "Sim2RealViz, is a visual analytics tool to assist experts in understanding and reducing this gap for robot ego-pose estimation tasks, i.e. the estimation of a robot’s position using trained models"

img: sim2realViz.png
fig-caption: " Using Sim2RealViz, the Sim2Real gap of a Data Augmentation model can be compared against other models (e. g., Vanilla or Fine-tuned) and displayed on the real-world environment mapalong with its performance metrics. In particular,Sim2RealVIZ shows ① this model is particularly effective in simulation but we identified errors in the environment, such as the model failing to regress its position because of a closed-door that was opened in training. Such an error can then be selected by instance on the map ② to identify key features extracted by the model either as superimposed on the heat-map ③ or as a first-person view. ④"

authors: "Théo Jaunet, Guillaume Bono, Romain Vuillemot, Christian Wolf"

conf: research report

teaser: sim2realViz.png
git: https://github.com/sim2realviz/sim2real
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

Visual Question Answering systems target answering open-ended textual questions given input images. They are a testbed for learning high-level reasoning with a primary use in HCI, for instance assistance for the visually impaired. Recent research has shown that state-of-the-art models tend to produce answers exploiting biases and shortcuts in the training data, and sometimes do not even look at the input image, instead of performing the required reasoning steps. We present VisQA, a visual analytics tool that
explores this question of reasoning vs. bias exploitation. It exposes the key element of state-of-the-art neural models --- attention maps in transformers. Our working hypothesis is that reasoning steps leading to model predictions are observable from attention distributions, which are particularly useful for visualization. The design process of VisQA was motivated by well-known bias examples from the fields of deep learning and vision-language reasoning and evaluated in two ways. First, as a result of a collaboration of three fields, machine learning, vision and language reasoning, and data analytics, the work lead to a direct impact on the design and training of a neural model for VQA, improving model performance as a consequence. Second, we also report on the design of VisQA, and a goal-oriented evaluation of VisQA targeting the analysis of a model decision process from multiple experts, providing evidence that it makes the inner workings of models accessible to users.










