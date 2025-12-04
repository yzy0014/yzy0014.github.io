---
title: ""
layout: collection
permalink: /Project/
author_profile: true
comments: false
geometry: margin=1in
fontfamily: mathpazo
fontsize: 8pt
spacing: single
---


<h2 style="font-family:Times New Roman; font-size:1.2em;">Selected Research Projects</h2>

<div style="font-family:Times New Roman; font-size:0.75em;">
These projects showcase the application of statistical and computational methods to analyze complex neuroscience data, utilizing R, MATLAB, and Python.
</div>

<hr style="margin: 2em 0;">

<h3 style="font-family:Times New Roman; font-size:1em;">Project 1: fMRI Image Reconstruction</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
This project applies novel feature reconstruction techniques to fMRI data to better visualize brain activation patterns.
</div>

<figure>
  <img src="/assets/images/yy/fMRI-project.png" alt="Project 1 Image" style="max-width:100%;height:auto;">
</figure>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Figure Description:</strong>
<p style="margin-top:0.5em;">fMRI image reconstruction for a single subject using new feature reconstruction techniques:</p>
<ul style="margin-top: 0.5em;">
  <li> (a): Displays regions of activation by human voices</li>
  <li> (b): Shows regions of activation when listening to human voices compared to nature sounds</li>
  <li> (c): Displays regions of activation by nature sounds</li>
</ul>
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Details & Resources:</strong>
<ul>
  <li><strong>Methods:</strong> Feature reconstruction, statistical mapping, signal processing</li>
  <li><strong>Tools:</strong> All figures produced in R</li>
  <li><strong>Data Source:</strong> <a href="https://pubmed.ncbi.nlm.nih.gov/30676975/">OpenNEUROs Dataset</a> (Gorgolewski et al., 2017)</li>
</ul>
</div>



<hr style="margin: 2em 0;">

<h3 style="font-family:Times New Roman; font-size:1em;">Project 2: Calcium Fluoresces Imaging (CFI) of Zebrafish Larvae during Induced Seizure Sessions</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
This project involves the reconstruction, classification, and forecasting of epileptic seizure patterns using Calcium Fluoresces Imaging data.
</div>

<figure>
  <img src="/assets/images/yy/zebrafish-project.png" alt="Project 2 Image" style="max-width:100%;height:auto;">
</figure>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Figure Description:</strong>
<p style="margin-top:0.5em;">CFI imaging reconstruction of PTZ induced zebrafish seizure:</p>
<ul style="margin-top: 0.5em;">
  <li> (a): CFI heatmap with patterns of activation during Ictal and Interictal phases, respectively. </li>
  <li> (b): Temporal Dynamics of Ictal and Interictal Pattern Fit (R-squared) across five seizure cycles 
    <ul style="margin-top: 0.3em; margin-bottom: 0.3em;">
      <li>Yellow curve indicates the fit of ictal features</li>
      <li>Blue curve shows interictal features</li>
      <li>Indicate an anti-correlational network between the two phases</li>
    </ul>
    </li>
  <li> (c): Averaged CFI series curve of zebrafish larvea across five epileptic seizure cycles.  </li>
 
</ul>
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Details & Resources:</strong>
<ul>
  <li><strong>Methods:</strong> Time series analysis, pattern recognition, network mapping</li>
  <li><strong>Tools:</strong> All figures plotted in R</li>
  <li><strong>Data Source:</strong> Data provided by collaborators; see Zheng et al., (2020) (<a href="https://pubmed.ncbi.nlm.nih.gov/30676975/">details</a>)</li>
</ul>
</div>

<hr style="margin: 2em 0;">

<h3 style="font-family:Times New Roman; font-size:1em;">Project 3: LLM Stereotype Encoding Through Personality Structure Rotation</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">
This project investigates how large language models encode cultural stereotypes, revealing that LLMs primarily operate through rotating covariance structures in personality space rather than simple mean score shifts.
</div>

<figure>
  <img src="/assets/images/yy/Combined_Ablation_Study_Analysis.png" alt="Combined Ablation Study Analysis" style="max-width:100%;height:auto;">
</figure>

<figure style="margin-top: 1em;">
  <img src="/assets/images/yy/UMAP_Dimensions_True_Labels.png" alt="UMAP Dimensions Analysis" style="max-width:100%;height:auto;">
</figure>

<figure style="margin-top: 1em;">
  <img src="/assets/images/yy/UMAP_Eigenvalues_True_Labels.png" alt="UMAP Manifold Analysis" style="max-width:100%;height:auto;">
</figure>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Details & Resources:</strong>
<ul>
  <li><strong>Methods:</strong> Ablation studies, Riemannian geometry, SPD manifold analysis, UMAP dimensionality reduction, cultural identity detection</li>
  <li><strong>Tools:</strong> Analysis conducted with GPT-4o samples, figures produced in Python/R</li>
  <li><strong>Data Source:</strong> GPT-4o generated personality profiles across cultural identities</li>
  <li><strong>Status:</strong> Manuscript in preparation for ICML 2025</li>
</ul>
</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:1em;">
<strong>Figure Description:</strong>
<ul style="margin-top: 0.5em;">
  <li><strong>Combined Ablation Study:</strong> Comprehensive analysis comparing five methods for detecting cultural identities in LLM-simulated personalities</li>
  <li><strong>UMAP Dimensions Analysis:</strong> Dimensional reduction visualization showing personality space structure across cultural groups</li>
  <li><strong>UMAP Manifold Analysis:</strong> Manifold-based clustering demonstrating 97.41% accuracy in cultural identity detection using Riemannian geometry</li>
</ul>
</div>








