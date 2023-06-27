---
layout: page
title: project 2
description: a project with a background image
img: assets/img/3.jpg
importance: 2
category: work
---
**NSF COLLABORATIVE GRANT: ROLE OF SPONTANEOUS MOVEMENTS DURING DECISION-MAKING.** 
Cognitive tasks such as decision-making are performed by different subjects in different ways. An important manifestation of this subject-to-subject variability is through spontaneous movements during task performance. For example, people may tap the floor or move their eyes while learning a cognitive task; similarly, mice display idiosyncratic whisker, facial, or other movements.

Since both spontaneous movements and cognitive tasks modulate cortical activity, modeling and interpreting neural activity during decision-making is a major challenge. Deciphering the function and quantifying the neural origin of spontaneous movements while explicitly modeling individual neural dynamics is a crucial first step in understanding the neural basis of cognitive behaviors. Elucidating the role of spontaneous movements in cognition will also be important for assessing and developing novel therapies for neurobehavioral disorders such as attention deficit hyperactivity disorder.

It has not been possible to fully understand large-scale neural and behavioral data during cognitive tasks because neural activity is strongly modulated by movements during the task, and the effect of spontaneous, uninstructed movements on learning and cognition is not well understood. A significant challenge in disentangling the neural dynamics related to movements from those related to cognitive tasks is the presence of subject-to-subject variability. Traditionally, the variability is resolved by focusing on the representations that are present across a large number of subjects. In contrast, we want to explicitly model spontaneous movements and subject-to-subject variability by decoupling it from the across-subject part of the task. For this, we plan to leverage across-subject similarity in neural activity in mice by learning subject-independent dynamical models, while separately quantifying subject-specific dynamics.

Furthermore, the next generation of neurostimulation algorithms should not require extensive training on each subject. For this goal, we will use a trained across-subject model as the initial model for new subjects, while refining it further with individual data. This transfer learning approach will lead to effective model-based control strategies to design closed-loop neurostimulation. In an integrative computational and experimental approach, these models will be used to investigate the contribution of high-dimensional cortical activity to spontaneous movements and cognitive tasks.

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
