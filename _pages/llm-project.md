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

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Methodology</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<strong>Data:</strong>
<ul style="margin-top: 0.5em;">
  <li>N=200 LLM-API generated personality profiles across controlled cultural conditions under fixed item order. </li>
</ul>

<strong>Analysis:</strong>
<ul style="margin-top: 0.5em;">
  <li>Geometric representations of personality item score space (i.e., the SPD manifolds) were constructed for each API response from each cultural context. The tangent space mapped SPD manifolds are compared with BigFive scores as well as Eigenvalues from the covariance structure. </li>
  <li>UMAP was used for dimensionality reduction and visualization;</li>
  <li>Unsupervised clustering was applied to evaluate classification accuracy.</li>
</ul>

<strong>Ablation:</strong>
<ul style="margin-top: 0.5em;">
  <li>Results were compared across raw personality scores, eigenvalues, and alternative dimension-reduction methods</li>
</ul>

<strong>Tools:</strong>
<ul style="margin-top: 0.5em;">
  <li>GPT-4o API via R, custom visualization, version-controlled reproducible framework</li>
</ul>
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Geometric Analysis</h3>

<figure>
  <img src="/assets/images/yy/Combined_Ablation_Study_Analysis.png" alt="Combined Ablation Study Analysis" style="max-width:120%;height:auto;margin-left:-10%;">
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

<strong>Other Findings (available upon request):</strong>

<div style="margin-top:0.5em;">
<em>Order Effects:</em><br>
Controlled ablation experiments demonstrate that prompt order and randomization systematically alter the geometric organization of LLM-simulated personalities.
</div>

<div style="margin-top:0.5em;">
<em>Human vs. LLM Comparison:</em><br>
Geometric alignment analysis between LLM-generated personality representations and human personality data reveals structural similarities and divergences at the covariance level.
</div>

</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Publication Status</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<strong>Manuscript in preparation for NeurIPS 2026</strong><br>
<em>"How LLMs Encode Stereotypes: Rotating Personality Structures, Not Just Shifting Scores"</em>
</div>

