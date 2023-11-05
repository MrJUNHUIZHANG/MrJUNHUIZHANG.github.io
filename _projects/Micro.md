---
layout: page
title: Reliable Control for Microgrids with Guaranteed Performances
description: How can we guarantee the performances including safety and sparisity during the whole operation process?
img: assets/img/Micro1.jpg
importance: 2
category: work
related_publications: zhang2023novel, zhang2022sparse
---

**Sparse and safe control for Microgrids.** In inverter-intensive microgrids (MGs), the inverters and external grids are expected to reach a synchronized desired frequency under regulations. To this end, the active power set-point acting as a control from a high-level controller is designed while considering two important performance metrics “sparsity” and “safety”, which are to reduce the information exchange between controllers and ensure that the frequency keeps in safety regions during the whole operation process.  <strong><i style="color:#e74d3c"> Our proposed control design framework allows the sparse linear feedback controller (SLFC) to be unified with a family of conditions for safe control using control barrier functions (CBF). </i></strong> A quadratic programming (QP) problem is then constructed, and the real-time control policy is obtained by solving the QP problem. Importantly, we also found that the real-time control for each inverter depends on the cross-layer communication network topology, which is the union of the one between controllers from SLFC and the one determined by the power flow network. 

<div class="row justify-content-sm-center">
    <div class="col-sm-13 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Micro4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   QP-based sparse and safe control
</div>



