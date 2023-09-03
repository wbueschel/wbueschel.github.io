---
layout: page
title: MIRIA
description: A Mixed-Reality Interaction Analysis Toolkit
img: assets/img/miria/teaser.jpg
importance: 2
category: work
related_publications: MIRIA2021
---

MIRIA, short for **Mi**xed **R**eality **I**nteraction **A**nalysis Toolkit, is a system for the analysis of spatial interaction data in mixed reality. MIRIA specifically supports *in-situ* data analysis by using situated, immersive visualizations.
I wrote MIRIA in C# for the Unity engine, targeting Microsoft's HoloLens series of AR headsets.

MIRIA can import data, such as motion tracking data, from CSV files and visualize it in several different 2D and 3D visualizations, most importantly as 3D trajectories in space. MIRIA supports multiple co-located users and doesn't need an additional server or tracking system, making it useful for usage in a wide range of environments.
<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include video.html path="https://www.youtube-nocookie.com/embed/mnFZ-skGH5s?si=qjIK8avlrXN3CDlV" class="rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The official video gives a short overview of the project.
</div>

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/miria/2.jpg" title="3D models and touch visualization" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/miria/3.jpg" title="video overlays" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/miria/4.jpg" title="multiple trajectories" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The trajectory visualizations in MIRIA are supported by additional 2D views, 3D models, and even image or video data.
</div>

<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/miria/1.jpg" title="showcase" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is a typical MIRIA setup, showing most of its features: spatio-temporal interaction data is visualized as 3D trajectories, with accompanying 2D views.
</div>


For more details about MIRIA, please take a look at the main project [website](https://imld.de/miria) or check out the [git repository](https://github.com/imldresden/miria)!
Additionally, if you would like to cite MIRIA in your research, please cite our CHI '21 [paper](https://doi.org/10.1145/3411764.3445651).