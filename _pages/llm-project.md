---
title: " "
layout: publications
permalink: /LLM-Project/
author_profile: true
comments: false
geometry: margin=1in
fontfamily: mathpazo
fontsize: 8pt
spacing: single
---

<h2 style="font-family:Times New Roman; font-size:1.2em;">LLM Bias Encoding Through Personality Structure Rotation</h2>

<div style="font-family:Times New Roman; font-size:0.75em; margin-bottom:1.5em;">
This study examines how large language models encode cultural stereotypes in personality simulation. We find that stereotype representation operates primarily through rotations of covariance structures in personality space, rather than through simple mean shifts in trait scores.
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Key Findings</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<ul style="margin-top: 0.5em;">
  <li><strong>Bias Encoding Mechanism: </strong> Cultural stereotypes are encoded via rotation of the personality matrix on a high-dimensional manifold</li>
  <li><strong>Classification Performance: </strong>Clustering based on Big Five personality scores achieved 99.5% accuracy across cultural samples. Geometric manifold representations achieved 97.41% accuracy. In contrast, clustering using personality eigenvalues yielded 50% accuracy.</li>
  <li><strong>Methodological Comparision:</strong> A five-method ablation study demonstrates the relative performance of geometric versus traditional statistical approaches in detecting cultural identities.</li>
</ul>
</div>


<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Geometric Analysis</h3>

<figure>
  <img src="/assets/images/yy/Combined_Ablation_Study_Analysis.png" alt="Combined Ablation Study Analysis" style="max-width:140%;height:auto;margin-left:5%;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">Comprehensive ablation study comparing five methods for detecting cultural identities in LLM-simulated personalities</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Dimensions_True_Labels.png" alt="BigFive Score Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;"><strong>BigFive Scores:</strong> UMAP visualizations of BigFive Score structure across cultural groups</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Manifold_True_Labels.png" alt="SPD Manifold Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;"><strong>SPD Manifold:</strong>UMAP visualizations of Riemannian geometry-based clustering achieved 97.41% accuracy in cultural identity detection</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Eigenvalues_True_Labels.png" alt="Eigenvalues Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;"><strong>Eigenvalues:</strong> Analysis of UMAP visualizations of item-dimension covariance structure orientation across groups</figcaption>
</figure>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Interpretation</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">

<strong>Encoding Mechanism:</strong>
<div style="margin-top:0.5em; margin-bottom:1em;">
The current project indicates that LLMs encode cultural stereotypes primarily through rotation of personality covariance structures on a high-dimensional manifold, rather than through simple mean shifts in trait scores.
</div>

