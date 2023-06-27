---
layout: page
title: project 1
description: We are broadly interested in topics on the interface of statistical inference, recurrent neural networks, control theory, and neuroscience.
img: assets/img/12.jpg
importance: 1
category: work
---


**BRAIN INITIATIVE R01: ELUCIDATING PRINCIPLES OF SENSORIMOTOR CONTROL USING DEEP LEARNING.**
How do distributed neural circuits drive purposeful movements from the complex musculoskeletal system? This understanding and characterization will be critical towards the application of principled neurostimulation to specific brain regions to study the effect of neural circuit perturbations on behavior, and conversely towards predictions of the neural activity during perturbations in the behavior.

Breakneck advances in hardware and machine learning techniques have led to vast improvements in our ability to record and model large-scale multi-regional neural data. Our broad research goal is to advance the current state-of-the-art for modeling the neural control of movements by incorporating large-scale measurements and biological constraints into theoretical models of sensorimotor control.

To that end, we are developing biologically-inspired goal- and data- driven artificial intelligence methods to elucidate the neurodynamical basis of sensorimotor control. Using these tools, we hope to elucidate principles of sensorimotor control by incorporating recorded neural data in succinct and interpretable biologically-inspired models of the relationships between the measured biological data and the corresponding behavior.

This is a critical step towards (a) elucidating the computational role of neural activity from different brain regions in controlling complex behavior, (b) allowing us to further refine theoretical models of movement generation based on data, and (c) understanding where and how to stimulate the brain in order to efficiently apply neurostimulation for achieving desired behavior. 


To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
