---
layout: page
title: project 6
description: a project with no image
img:
importance: 4
category: Past Research
---

**INVESTIGATING THE ROLE OF BASAL GANGLIA NEURONS IN MOVEMENT GENERATION AND THEIR MODULATION DUE TO DEEP BRAIN STIMULATION (DBS)**
We performed an in-depth quantitative analysis of the firing pattern of the Globus Pallidus Internus (GPi) nuclei within the basal ganglia. These neurons relay information between the somatosensory and the motor cortex, and are responsible for the planning of movement related activity. Deep brain stimulation at high frequencies applied to these neurons during parkinson’s disease significantly alleviates motor symptoms, but the underlying mechanism is not yet fully known. We developed data-driven point process spiking models to quantify the effect of an input spike train on an output spike train, and applied this approach by modeling the GPi neurons as receiving inputs from their own history, the spike train of the Globus Pallidus externus neurons, and the sequence of DBS pulses [1]. We found that high frequency stimulation (as opposed to low frequency stimulation) to the subthalamic nucleus (STN) affects these neurons in a therapeutic way due to the positioning of the GPi neurons in a recurrent loop. We also modeled the oscillatory activity of the GPi neurons while the subjects were performing a direction-related motor task, and found that the occurrence of gamma oscillations is stronger during the planning of movement in directionally tuned neurons, whereas the occurrence of beta oscillations is stronger during the remainder of the trial [2].

We also developed a number of methods to aid these scientific analyses. Typically, one may record from a number of neurons in a specific area while the subject performs a task. The selection of task relevant neurons to model is an important step, and we developed a novel step-wise method to do so [3]. Moreover, groups of neurons may be acting together to produce a certain output, i.e. they may have the same input-output functionality. We developed a novel method to isolate these groups in recorded populations by building aggregate models of populations of neurons [4]. These methods can be applied to analyze a large variety of neuronal populations to build efficient models that allow us to discover scientific mechanisms.

[1] Saxena S. et al., “Point Process Models show Temporal Dependencies in Basal Ganglia Nuclei under Deep Brain Stimulation.” Proceedings of the IEEE Engineering in Medicine and Biology Conference, 2010.

[2] Saxena S. et al., “Modulations in Oscillatory Activity of Globus Pallidus internus Neurons During a Directed Hand Movement Task – A Primary Mechanism for Motor Planning.” Frontiers in Systems Neuroscience, 2019

[3] Kahn K., Saxena S., Eskandar E.N., Thakor N., Schieber M., Gale J.T., Averbeck B., Eden U. and Sarma S.V. “A Systematic Approach to Selecting Task Relevant Neurons.” Journal of Neuroscience Methods, 2015.

[4] Saxena S., Santaniello S., Gale J.T., Montgomery E. and Sarma S.V. “Aggregate Input-Output Models of Neuronal Populations.” IEEE Transactions on Biomedical Engineering, vol. 59, 2012.
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
