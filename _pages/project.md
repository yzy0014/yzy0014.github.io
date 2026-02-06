---
title:  ""
layout: publications
permalink: /Project/
author_profile: true
comments: false
geometry: margin=1in
fontfamily: mathpazo
fontsize: 8pt
spacing: single
---

<h2 style="font-family:Times New Roman; font-size:1.2em;">Research Projects</h2>

<h3 style="font-family:Times New Roman; font-size:1em;">Epileptic Brain Dynamics via Neural Network Latent Space Analysis</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
Building on zebrafish calcium imaging data, this project employs our novel spatiotemporal feature extraction and preprocessing pipeline combined with advanced machine learning and dynamical systems analysis to investigate epileptic seizure dynamics. This unique preprocessing approach significantly improved classification accuracy compared to raw data analysis. Using neural network latent space trajectories, we uncovered a novel "spatial stability vs. directional chaos" paradigm that fundamentally characterizes ictal (seizure) and interictal (normal) brain states.
</div>

<figure>
  <img src="/assets/images/yy/tp_full_balanced_umap_animation.gif" alt="UMAP Latent Space Trajectory Animation" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">Animated trajectory through neural network latent space (1995 frames). Red points indicate ictal phases, blue points indicate interictal phases. Orange triangles mark misclassified frames. The visualization shows 64-dimensional latent vectors reduced to 2D using UMAP.</figcaption>
</figure>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Key Findings:</strong>
<ul>
  <li><strong>High Classification Accuracy:</strong> Achieved 82.6% accuracy in distinguishing ictal vs. interictal brain states using unsupervised K-means clustering on UMAP-reduced latent space</li>
  <li><strong>Metastable Dynamics Framework:</strong> Seizure transitions follow stochastic metastable dynamics rather than deterministic patterns, with noise-induced phase transitions resembling thermodynamic phase changes</li>
</ul>
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Details & Resources:</strong>
<ul>
  <li><strong>Data Source:</strong> Calcium fluorescence imaging videos from zebrafish larvae (1995 frames, balanced ictal/interictal phases)</li>
  <li><strong>Novel Preprocessing:</strong> Custom spatiotemporal feature extraction pipeline that significantly outperformed raw data approaches - balanced standardization achieved 82.6% accuracy vs. lower performance with raw data or standard z-score normalization</li>
  <li><strong>Methods:</strong> Autoencoder neural networks (64-dimensional latent space), UMAP dimensionality reduction (optimized through testing 16 different combinations), K-means clustering, comprehensive physics-based trajectory analysis (18 physical quantities including velocity, acceleration, angular velocity, curvature, energy metrics)</li>
  <li><strong>Tools:</strong> Python (PyTorch for neural network training), R (UMAP, statistical analysis, visualization with ggplot2 and gganimate), circular statistics for angular analysis</li>
</ul>
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Clinical Implications:</strong>
<ul>
  <li><strong>Novel Biomarkers:</strong> Angular velocity patterns and stability ratios provide new quantitative metrics for seizure characterization</li>
  <li><strong>Treatment Paradigm Shift:</strong> Findings suggest targeting brain state attractor landscapes rather than event triggers may be more effective than traditional seizure prevention approaches</li>
  <li><strong>Personalized Medicine:</strong> Individual-specific dynamical models could enable personalized intervention strategies based on unique brain state dynamics</li>
</ul>
</div>