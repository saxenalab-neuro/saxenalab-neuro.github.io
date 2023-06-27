---
layout: page
title: project 3
description: a project that redirects to another website
img: assets/img/7.jpg
redirect: 
importance: 3
category: work
---


**INTERPRETABLE DIMENSIONALITY REDUCTION OF NEURAL POPULATION ACTIVITY, AND DECODING ITS RELATIONSHIP TO HIGH-DIMENSIONAL BEHAVIOR**
![]({{ site.url }}{{ site.baseurl }}/images/respic/LocaNMF.png){: style="width: 250px; float: left; margin: 0px  10px"}
Dimensionality reduction methods for neural population activity are becoming essential with the advent of novel recording techniques that can simultaneously record the activity of thousands of neurons in the brain [1]. While recording from multiple regions of the brain, how does one best incorporate prior information about anatomical regions while accurately representing the data? Widefield calcium imaging methods offer a global view of the activity of the mouse dorsal cortex, with temporal resolution of around 30Hz. In order to study inter-areal interactions across multiple recording days and multiple subjects, we need to transform these signals into a common subspace while respecting anatomical region specificity. To perform such interpretable dimensionality reduction, we developed LocaNMF (Localized semi-Nonnegative Matrix Factorization), an efficient algorithm to robustly decompose widefield calcium activity into region-based components [2]. Using LocaNMF, we analyzed the neural correlates of task and behavior variables across mice and revealed, for the first time, that the inter-areal correlations across mice are very similar while the mice are performing the same task. We also developed efficient dimensionality reduction and segmentation methods for mouse behavioral videos into ‘behavioral syllables’, across different recording sessions and subjects. These methods comprise Behavenet, a behavioral analysis toolbox [3], using which we can now efficiently decode the relationship between the multi-regional neural activity and the ongoing behavior.

[1] Saxena S., Cunningham J.P. “Towards the Neural Population Doctrine” Current Opinion in Neurobiology, vol. 55, 2019.

[2] Saxena S., et al. “Localized semi-nonnegative matrix factorization (LocaNMF) of widefield calcium imaging data.” PLOS Computational Biology, 2020. Featured on the cover page!

[3] Batty E., Whiteway M., Saxena S., et al. “BehaveNet: nonlinear embedding and Bayesian neural decoding of behavioral videos” Advances in Neural Information Processing Systems (NeurIPS), 2019.


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
