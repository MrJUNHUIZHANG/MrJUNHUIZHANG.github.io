---
layout: page
title: Gray-box Model
description: How can we use partial knowledge of systems to improve data-driven model?
img: assets/img/gray1.jpg
importance: 1
category: work
giscus_comments: true
---

**Gray-box model for distribution systems.** Inspired by physics-informed machine learning (PINN), we developed a novel gray-box modeling approach for distribution systems with inverter-based resources (IBRs). The proposed gray-box modeling method aims to improve estimation accuracy by taking advantage of both physics-based (white-box) and data-driven (black-box) modeling approaches. To this end,  <strong><i style="color:#e74d3c"> the gray-box modeling framework is constructed by encoding prior physical knowledge of the system in a white-box model and then embedding the output of the white-box model into the input of a black-box model (machine learning approach).</i></strong> Furthermore, case studies demonstrate that our gray-box modeling approach effectively improves estimation accuracy compared to purely physics-based or data-driven methods. 

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gray2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The architecture of gray-box modeling algorithm.
</div>

