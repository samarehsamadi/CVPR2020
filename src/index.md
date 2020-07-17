---
author: Samareh Samadi
title: CVPR 2020
date: July 15, 2019
---
# Domain Adaptation
![](DA_Classification.JPG)

# Review
* Deep Visual Unsupervised Domain Adaptation for Classification Tasks: A Survey
<img src="DA_Reveiw.png" width="70%">


# DFA
* Discriminative Feature Alignment: Improving Transferability of Unsupervised Domain Adaptation by Gaussian-guided Latent Alignment
![Idea](DAL_idea.JPG)

# Network
<img src="DAL_net.JPG" width="70%">

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
<img src="JoCor_Algorithm.jpg" width="60%">

# [ADA](https://arxiv.org/pdf/2003.13216.pdf)
* Learning to Learn Single Domain Generalization
<img src="ADA_idea.JPG" width="70%">

#
$$x^+_{t+1} \rightarrow x^+_t +\gamma \Delta_{x^+_t} L_{ADA}(θ, ψ; x^+_t, z^+_t)$$
$$L_{ADA}=L_{task}(\theta;\bf{x})-\alpha L_{const}(\theta;\bf{z})+ \beta L_{relax}(\psi;\bf{x})$$

#
$$L_{task}(y,\hat{y})=- \sum_i y_i log\hat{y}_i$$

$$L_{const}=\frac{1}{2}|z-z^+|_2^2 +\infty. \textbf{1} \{ y \neq y^+ \}$$

$$\min_\psi [|G(Q(\bf{x})) − x|^2 + \lambda D_e(Q(\bf{x}), P(\bf{e}))]$$

$$L_{relax}=| x^+ - V(x^+) |^2$$

# Relax
![](ADA_relax.JPG)

# عنوان اول {dir=rtl}

<div dir=rtl>این متن فارسی باید راست به چپ نشان داده شود.</div>


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEwNTg0OTkwNV19
-->
