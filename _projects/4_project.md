---
layout: page
title: project 4
description: another without an image
img:
importance: 3
category: Past Research
---
**COMPUTATIONAL PRINCIPLES UNDERLYING SPEED CONTROL IN THE PRIMARY MOTOR CORTEX**
How do we make the same movement but faster? Getting a clear answer to this question will help us design neuroprosthetic devices that can flexibly generate movements at different speeds. In a collaboration with Mark Churchland, we trained recurrent neural networks (RNNs) to directly generate the muscle activity during cycling movements at different speeds (experimental data collected in Mark Churchland’s laboratory). Surprisingly, we find that the networks made qualitative and quantitative predictions for the neural activity in the primary motor cortex of non-human macaques. We examine differences in the dynamics displayed by neural and muscle signals during movement at different speeds, using both computational and theoretical models.

Saxena S., Russo A., Cunningham J., Churchland M. “Network principles predict motor cortex population activity across movement speeds” eLife, 2022.

**FUNDAMENTAL LIMITATIONS OF THE SENSORIMOTOR CONTROL SYSTEM**
Is there a limit to how fast we can move? We examined the fundamental limitations of the sensorimotor control system, specifically while tracking fast movements. The ability to move fast and accurately track moving objects is constrained by the biophysics of neurons and dynamics of the muscles involved. Yet, the corresponding tradeoffs between these factors and tracking motor commands have not been rigorously quantified. We use feedback control principles to identify performance limitations of the sensorimotor control system to track fast periodic movements [1]. Moreover, given neural trajectories in the motor and premotor cortices of a nonhuman primate during complicated reach and grasp behaviors, we can learn these systems-level models accurately and efficiently [2]. This body of work has important implications in sensorimotor control. For example, if the primary motor cortex is compromised due to disease or damage, the theory suggests ways to manipulate muscle dynamics by adding the necessary compensatory forces using an assistive neuroprosthetic device to restore motor performance and, more important, fast and agile movements. Just how one should compensate can be informed by theory developed in [1].

[1] Saxena S., Sarma S.V., Dahleh M. “Performance Limitations in Sensorimotor Control: Trade-offs between Neural Computing and Accuracy in Fast Tracking.” Neural Computation, 2020.

[2] Saxena S., D’Aleo R., Schieber M., Dahleh M., Sarma S.V. “Reconstructing Neural Activity and Kinematics Using a Systems-Level Model of Sensorimotor Control” Proceedings of the IEEE Engineering in Medicine and Biology Conference, 2018.


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
