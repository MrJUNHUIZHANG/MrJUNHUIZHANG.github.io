---
layout: page
title: Reliable Control for Microgrids with Guaranteed Performances
description: How can we guarantee the performances including safety and sparisity during the whole operation process?
img: assets/img/Micro1.jpg
importance: 2
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

**Sparse and safe control for Microgrids.** In inverter-intensive microgrids (MGs), the inverters and external grids are expected to reach a synchronized desired frequency under regulations. To this end, the active power set-point acting as a control from a high-level controller is designed while considering two important performance metrics “sparsity” and “safety”, which are to reduce the information exchange between controllers and ensure that the frequency keeps in safety regions during the whole operation process.  <strong><i style="color:#e74d3c">IEEE Transactions on Neural Networks and Learning Systems Our proposed control design framework allows the sparse linear feedback controller (SLFC) to be unified with a family of conditions for safe control using control barrier functions (CBF). </i></strong> A quadratic programming (QP) problem is then constructed, and the real-time control policy is obtained by solving the QP problem. Importantly, we also found that the real-time control for each inverter depends on the cross-layer communication network topology, which is the union of the one between controllers from SLFC and the one determined by the power flow network. 

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Micro2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
