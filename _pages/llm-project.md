---
title: "LLM Stereotype Encoding Research"
layout: publications
permalink: /LLM-Project/
author_profile: true
comments: false
geometry: margin=1in
fontfamily: mathpazo
fontsize: 8pt
spacing: single
---

<h2 style="font-family:Times New Roman; font-size:1.2em;">LLM Stereotype Encoding Through Personality Structure Rotation</h2>

<div style="font-family:Times New Roman; font-size:0.75em; margin-bottom:1.5em;">
This project investigates how large language models encode cultural stereotypes, revealing that LLMs primarily operate through rotating covariance structures in personality space rather than simple mean score shifts. The research challenges traditional assumptions about AI bias and proposes novel mathematical frameworks for understanding stereotype representation in neural language models.
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Research Overview</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
Traditional approaches to understanding AI bias focus on mean score differences across demographic groups. However, our research reveals a more sophisticated mechanism: LLMs encode cultural stereotypes primarily through rotations of covariance structures in personality space. This finding has profound implications for AI fairness, alignment, and the development of more culturally sensitive language models.
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Key Findings</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<ul style="margin-top: 0.5em;">
  <li><strong>Covariance Structure Rotation:</strong> LLMs encode stereotypes by rotating the covariance matrix of personality traits rather than simply shifting mean values</li>
  <li><strong>High Classification Accuracy:</strong> Achieved 97.41% clustering accuracy using Riemannian geometry on SPD (Symmetric Positive Definite) manifolds</li>
  <li><strong>Methodological Innovation:</strong> Developed novel ablation study comparing five different methods for cultural identity detection</li>
  <li><strong>Theoretical Framework:</strong> Established mathematical foundations for understanding stereotype encoding in high-dimensional personality spaces</li>
</ul>
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Methodology & Analysis</h3>

<figure>
  <img src="/assets/images/yy/Combined_Ablation_Study_Analysis.png" alt="Combined Ablation Study Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">Comprehensive ablation study comparing five methods for detecting cultural identities in LLM-simulated personalities</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Dimensions_True_Labels.png" alt="UMAP Dimensions Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">UMAP dimensional reduction visualization showing personality space structure across cultural groups</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Manifold_True_Labels.png" alt="UMAP Manifold Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">Manifold-based clustering demonstrating 97.41% accuracy in cultural identity detection using Riemannian geometry</figcaption>
</figure>

<figure style="margin-top: 2em;">
  <img src="/assets/images/yy/UMAP_Eigenvalues_True_Labels.png" alt="UMAP Eigenvalues Analysis" style="max-width:100%;height:auto;">
  <figcaption style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em;">Eigenvalue-based analysis of personality covariance structures across cultural groups</figcaption>
</figure>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Technical Details</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<strong>Data Collection:</strong>
<ul style="margin-top: 0.5em;">
  <li>200 GPT-4o generated personality profiles across diverse cultural identities</li>
  <li>Systematic sampling across multiple demographic dimensions</li>
  <li>Controlled experimental conditions to ensure methodological rigor</li>
</ul>

<strong>Analytical Methods:</strong>
<ul style="margin-top: 0.5em;">
  <li><strong>Riemannian Geometry:</strong> Analysis on SPD manifolds for covariance structure comparison</li>
  <li><strong>UMAP Dimensionality Reduction:</strong> Visualization of high-dimensional personality spaces</li>
  <li><strong>Ablation Studies:</strong> Systematic comparison of five different detection methods</li>
  <li><strong>Cultural Identity Detection:</strong> Novel algorithms for identifying encoded stereotypes</li>
</ul>

<strong>Tools & Implementation:</strong>
<ul style="margin-top: 0.5em;">
  <li>Analysis conducted with GPT-4o API integration</li>
  <li>Python/R implementation with specialized statistical libraries</li>
  <li>Custom visualization tools for manifold analysis</li>
  <li>Reproducible research framework with version control</li>
</ul>
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Implications & Future Work</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
This research opens several important avenues for future investigation:

<ul style="margin-top: 0.5em;">
  <li><strong>AI Fairness:</strong> New approaches to bias detection and mitigation in language models</li>
  <li><strong>Cultural Sensitivity:</strong> Framework for developing more culturally aware AI systems</li>
  <li><strong>Theoretical Foundations:</strong> Mathematical models for understanding stereotype representation</li>
  <li><strong>Practical Applications:</strong> Tools for auditing and improving LLM behavior across cultures</li>
</ul>
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Publication Status</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
<strong>Manuscript in preparation for ICML 2025</strong><br>
<em>"How LLMs Encode Stereotypes: Rotating Personality Structures, Not Just Shifting Scores"</em>

This work represents a significant contribution to the understanding of bias mechanisms in large language models and provides novel theoretical and practical frameworks for addressing cultural representation in AI systems.
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:2em; padding:1em; background-color:#f9f9f9; border-left:4px solid #4a4a4a;">
<strong>Related Work:</strong> This research connects to broader investigations in AI alignment and cultural representation, including work on <a href="/Publications/">philosophical frameworks for AI alignment</a> and <a href="/Research/">cross-cultural AI ethics</a>.
</div>