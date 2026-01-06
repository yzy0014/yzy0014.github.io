---
title: "Epileptic Brain Dynamics: A Neural Network Latent Space Analysis"
date: 2026-01-06
permalink: /posts/2026/01/epileptic-brain-dynamics/
tags:
  - neuroscience
  - epilepsy
  - neural networks
  - UMAP
  - zebrafish
excerpt: "Revealing the 'spatial stability vs. directional chaos' paradigm in epileptic seizures through neural network latent space trajectory analysis."
---

<div style="font-family:Times New Roman; font-size:0.75em; margin-bottom:1.5em;">
Using advanced machine learning and dynamical systems analysis, we uncovered a novel paradigm characterizing epileptic brain states: <strong>spatial stability vs. directional chaos</strong>. This research builds on our previous zebrafish spatiotemporal analysis, applying neural network latent representations and UMAP dimensionality reduction to reveal fundamental differences in how seizures and normal brain activity unfold over time.
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">The Core Discovery</h3>

![UMAP Animation](/assets/images/yy/tp_full_balanced_umap_animation.gif)

<div style="font-family:Times New Roman; font-size:0.7em; font-style:italic; margin-top:0.5em; margin-bottom:1.5em;">
<strong>Figure:</strong> Animated trajectory of neural network latent space representations across 1995 video frames. Red points indicate ictal (seizure) states, blue points show interictal (non-seizure) states, and orange triangles mark misclassified frames. The visualization demonstrates how a 64-dimensional latent space, reduced to 2D using UMAP, captures distinct dynamics between brain states, achieving 82.6% classification accuracy through K-means clustering.
</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Key Findings</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">1. Spatial Stability vs. Directional Chaos</h4>

Our analysis revealed that epileptic and non-epileptic brain states differ fundamentally in their movement patterns through neural state space:

<ul style="margin-top:0.5em;">
<li><strong>Ictal (Seizure) States</strong>: Characterized by <em>spatial stability</em> but <em>directional chaos</em>
  <ul>
    <li>Confined to smaller spatial regions (68.9° angular velocity)</li>
    <li>Erratic, unpredictable directional changes</li>
    <li>High moment-to-moment angular variability</li>
  </ul>
</li>
<li><strong>Interictal (Normal) States</strong>: Display <em>spatial exploration</em> with <em>directional consistency</em>
  <ul>
    <li>Cover wider spatial territory (43.0° angular velocity)</li>
    <li>Smoother, more predictable trajectories</li>
    <li>Lower directional variability</li>
  </ul>
</li>
</ul>

<div style="margin-top:1em;">
This finding challenges conventional assumptions about seizure dynamics and suggests that the <em>quality</em> of movement (directional consistency) may be more diagnostically relevant than spatial extent.
</div>

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">2. Classification Performance</h4>

<ul style="margin-top:0.5em;">
<li><strong>82.6% accuracy</strong> distinguishing ictal from interictal states using K-means clustering on UMAP-reduced latent representations</li>
<li><strong>351 misclassified frames</strong> out of 1995 total frames</li>
<li>Performance achieved through novel spatiotemporal preprocessing pipeline that balances class representation</li>
</ul>

</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Methodology</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">Neural Network Architecture</h4>

We trained an autoencoder neural network on masked zebrafish brain imaging data:
<ul style="margin-top:0.5em;">
<li><strong>Input</strong>: 2000 frames of brain imaging data with spatial masking</li>
<li><strong>Latent Space</strong>: 64-dimensional bottleneck layer capturing essential brain state features</li>
<li><strong>Training</strong>: Balanced standardization approach to prevent class-biased learning</li>
</ul>

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">Dimensionality Reduction with UMAP</h4>

The 64-dimensional latent representations were reduced to 2D using UMAP (Uniform Manifold Approximation and Projection):
<ul style="margin-top:0.5em;">
<li><strong>Why UMAP?</strong> Preserves both local neighborhood structure and global topology of high-dimensional data</li>
<li><strong>Optimization</strong>: Tested 16 different parameter combinations to identify optimal configuration</li>
<li><strong>Result</strong>: Clear visual separation between ictal and interictal trajectories while maintaining temporal coherence</li>
</ul>

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">Trajectory Analysis</h4>

We computed 18 distinct physical quantities to characterize movement patterns:
<ul style="margin-top:0.5em;">
<li><strong>Spatial metrics</strong>: Total distance, displacement, tortuosity</li>
<li><strong>Velocity measures</strong>: Speed, acceleration, angular velocity</li>
<li><strong>Directional analysis</strong>: Angular changes, directional consistency</li>
<li><strong>Temporal dynamics</strong>: Frame-to-frame variability, smoothness</li>
</ul>

These metrics revealed the spatial stability vs. directional chaos paradigm that fundamentally distinguishes seizure from non-seizure brain activity.

</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Clinical Implications</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">Novel Seizure Characterization</h4>

The "spatial stability vs. directional chaos" paradigm offers:
<ul style="margin-top:0.5em;">
<li><strong>New diagnostic markers</strong>: Directional variability as a seizure indicator</li>
<li><strong>Treatment targets</strong>: Focus on stabilizing directional consistency rather than spatial confinement</li>
<li><strong>Predictive potential</strong>: Trajectory smoothness may serve as early warning signal</li>
</ul>

<h4 style="font-family:Times New Roman; font-size:0.9em; margin-top:1.5em;">Methodological Advances</h4>

Our custom preprocessing pipeline demonstrates:
<ul style="margin-top:0.5em;">
<li><strong>Importance of balanced training</strong>: Achieving 82.6% accuracy vs. lower performance with raw data approaches</li>
<li><strong>Latent space utility</strong>: Neural network representations capture clinically meaningful brain state differences</li>
<li><strong>UMAP effectiveness</strong>: Successfully visualizes complex brain dynamics in interpretable 2D space</li>
</ul>

</div>

<h3 style="font-family:Times New Roman; font-size:1em; margin-top:2em;">Future Directions</h3>

<div style="font-family:Times New Roman; font-size:0.75em;">

This work opens several promising research avenues:
<ul style="margin-top:0.5em;">
<li><strong>Real-time monitoring</strong>: Implementing trajectory analysis for live seizure detection</li>
<li><strong>Intervention timing</strong>: Using directional metrics to identify optimal treatment windows</li>
<li><strong>Cross-species validation</strong>: Testing the spatial stability vs. directional chaos paradigm in human epilepsy data</li>
<li><strong>Mechanistic understanding</strong>: Connecting movement patterns to underlying neural circuit dynamics</li>
</ul>

</div>

<div style="font-family:Times New Roman; font-size:0.75em; margin-top:2em; padding:1em; background-color:#f5f5f5; border-left:4px solid #333;">
<strong>Related Research:</strong> This project builds upon our previous work on <a href="/Project/">zebrafish spatiotemporal brain analysis</a>, extending the methodology to incorporate neural network latent representations and advanced trajectory analysis. The custom preprocessing pipeline developed here represents a significant methodological advancement for handling imbalanced neuroimaging datasets.
</div>
