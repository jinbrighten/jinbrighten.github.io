---
layout: page
permalink: /publications/
title: publications
description: Asterisks (*) denote equal contribution.
nav: true
nav_order: 1
---

<h2>ongoing work</h2>

<div class="ongoing-work">

  <div class="ongoing-item">
    <h3>Interaction-Constrained 6-DoF Object Pose Tracking</h3>
    <p>A constraint-guided pose-tracking system that uses affordance-based interaction priors from the manipulating body — a hand grasping or rotating an object — to validate and refine neural pose estimates at runtime within tight latency and energy budgets on mobile devices.</p>
  </div>

  <div class="ongoing-item">
    <h3>SpatialBlend: Relational Reconstruction for Cross-Space Presence in Heterogeneous Spaces</h3>
    <p>A runtime framework that integrates embodiment signals (6-DoF, pose, voice) to drive a remote-avatar motion backend, adapting to reconstructed cross-space interaction behaviors across heterogeneous physical environments. Evaluated through a user study on Meta Quest 3.</p>
  </div>

  <div class="ongoing-item">
    <h3>Failure-Aware Monitoring Code Synthesis for Robotics</h3>
    <p>Synthesizes runtime monitoring code for robot policies by exploring and validating potential failure modes in simulation, so that deployed monitors can detect the failure patterns observed during simulated rollouts.</p>
  </div>

</div>

<h2>publications</h2>

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
