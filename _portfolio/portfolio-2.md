---
title: "Melanoma Detection — ISIC Pipeline"
excerpt: "End‑to‑end pipeline: U‑Net segmentation, feature embedding + ABCDE rules, and classical ML classification on ISIC.<br/><img src='/images/segmentation_melanoma.png'>"
collection: portfolio
category: "Medical Imaging"
tags: ["ISIC", "U-Net", "Segmentation", "scikit-learn"]
---

I built a melanoma detection workflow using the ISIC dataset: lesion segmentation with U‑Net, handcrafted and embedded features aligned with ABCDE rules, and classification with scikit‑learn (Random Forest classification).
Focus areas: preprocessing, segmentation quality, and feature‑based interpretability for decision support.

# Technical aspect: 
U‑Net segmentation, color/shape/texture descriptors, classical ML classifiers.

# Results: 
Improved lesion isolation and consistent feature extraction for downstream classification. I achieved a balanced accuracy of 0.544 with Random Forests on handcrafted features which rank me in the top 25% of challenge participants. 