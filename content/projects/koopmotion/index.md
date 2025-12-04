---
date: 2025-10-01
image:
  caption: Example of learnt vector fields (gray) from training demonstrations (red), with matching trajectories (black).
  focal_point: Smart
summary: ' ' #  (CoRL 2025) We learn dynamical systems from demonstrations for motion planning with the Koopman operator.
tags:
- dynamical systems
- predictive modeling 
- active sensing
- koopman operator theory 
- data-driven
- marine robotics
- climate change
title: Learning from Demonstrations with Koopman Operators # KoopMotion - Learning Almost Divergence Free Koopman Flow Fields for Motion Planning
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
conference_prefix: CoRL 2025 


links:
  - type: site
    url: https://alicekl.github.io/koop-motion/
  - type: code 
    url: https://github.com/alicekl/koopmotion
---

## Project Description
We use a Koopman-based approach for learning dynamical systems from demonstrations. Our sample-efficient method captures nonlinearities in demonstrations, allows us to learn attractors that bring the system towards the desired demonstration when away, mimics the demonstration motion, and stops when the system reaches the end of the demonstration.
{style="text-align: justify;"}

Beyond this, since we adopt a Koopman based approach, we model the nonlinear dynamics by lifting the system into a higher dimensional yet linear space, where the dynamics evolve linearly. This enables linear analaysis as well as physically interpretable feature extraction, where the state space can be partitioned into regions exihibiting similar dynamics, revealing system attractors. 
{style="text-align: justify;"}

**Relevant Publication**:
**Li, Alice K.**, Thales C. Silva, Victoria Edwards, Vijay Kumar, and M. Ani Hsieh. "KoopMotion: Learning Almost Divergence Free Koopman Flow Fields for Motion Planning." <i> CoRL 2025.  </i>
<u> <a href="https://arxiv.org/abs/2509.09074" target="_blank" rel="noopener"> Link to paper. </a> </u> 
{style="text-align: justify;"}
