---
title: "SinGAN — Single‑Image Generative Modeling"
excerpt: "Implemented SinGAN with a custom loss to compare patch distributions; explorations in single‑image generation and multi‑scale training.<img src='/images/portfolio/singan.png'>"
collection: portfolio
---


title: "SinGAN — Single‑Image Generative Modeling"
excerpt: "Implemented SinGAN with a custom loss to compare patch distributions; explorations in single‑image generation and multi‑scale training.
<img src='/images/portfolio/image041.jpg'>"
collection: portfolio
date: 2024-10-01
category: "Generative Models"
tags: ["SinGAN", "Generative Models", "Computer Vision", "PyTorch"]

We reimplemented with 2 collegues “SinGAN: Learning a Generative Model From a Single Natural Image” : the objective of SinGAN is to compare patch distributions across scales, enabling realistic texture and structure synthesis from a single input image.
Stack: PyTorch, scikit-image, 
The technical aspect are that they used multi‑scale pyramids, adversarial training, we also study patch statistics.

Objective: reproduce and extend SinGAN with custom loss shaping for patch‑level fidelity.

Results: faithful single‑image generation and scale‑aware texture synthesis; ablations on patch loss variants.