---
author: Samareh Samadi
title: CVPR 2020
date: July 15, 2019
---
# Domain Adaptation
![](DA_Classification.JPG)

# Reveiw
<img src="DA_Reveiw.png" width="80%">


# DFA
* Discriminative Feature Alignment:mproving Transferability of Unsupervised Domain Adaptation by Gaussian-guided Latent Alignment
![Idea](DAL_idea.JPG)

# Network
![](DAL_net.JPG)

# Related Work
* Maximum Classifier Discrepancy for Unsupervised Domain Adaptation
* CVPR 2018

# Step A
* Train Genrator and Classifiers
![](DA_StepA.jpg)

# Step B
![](DA_StepB.JPG)

# Step C
![](DA_StepC.JPG)

# Algorithm
![](DAL_Alg1.JPG)

# Performance
![](DAL_Res.JPG)

# JoCoR 
* Combating Noisy Labels by Agreement:
A Joint Training Method with Co-Regularization
![](JoCor.jpg)

# Algorithm
![Algorithm](JoCor_Algorithm.jpg)

# [Learning to Learn Single Domain Generalization](https://arxiv.org/pdf/2003.13216.pdf)
* idea: adversarial domain augmentation to solve this Outof-Distribution (OOD) generalization problem -> cast the model
training in a meta-learning scheme and use a Wasserstein
Auto-Encoder (WAE) to relax the widely used worst-case
constraint

![Adversarial Domain Augmentation](ADA_idea.JPG)

#
$$L_{ADA}=L_{task}(\theta;\bold{x})-\alpha L_{const}(\theta;\bold{z})+ \beta L_{relax}(\si;\bold{x})$$

$$L_{task}(y,\hat{y})=- \sum_i y_i log\hat{y}_i$$

$$L_{const}=\frac{1}{2}|z-z^+|_2^2 +\infty. \textbf{1}{y \neq y^+}$$

WAE, training $$\min_\si [|G(Q(\bold{x})) − x|^2 + \lambda D_e(Q(\bold{x}), P(\bold{e}))]$$ $$D_e$$: could be Maximum Mean Discrepancy (MMD) or GANs

$$L_{relax}=| x^+ - V(x^+) |^2$$
# عنوان اول {dir=rtl}

<div dir=rtl>این متن فارسی باید راست به چپ نشان داده شود.</div>


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEwNTg0OTkwNV19
-->
