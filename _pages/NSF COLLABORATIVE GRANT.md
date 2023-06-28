---
layout: textlay
permalink: /NSFCOLLABORATIVEGRANT/
title: NSF COLLABORATIVE GRANT
description:
nav: false
nav_order: 4
---
# NSF COLLABORATIVE GRANT: ROLE OF SPONTANEOUS MOVEMENTS DURING DECISION-MAKING.
Cognitive tasks such as decision-making are performed by different subjects in different ways. An important manifestation of this subject-to-subject variability is through spontaneous movements during task performance. For example, people may tap the floor or move their eyes while learning a cognitive task; similarly, mice display idiosyncratic whisker, facial, or other movements.

Since both spontaneous movements and cognitive tasks modulate cortical activity, modeling and interpreting neural activity during decision-making is a major challenge. Deciphering the function and quantifying the neural origin of spontaneous movements while explicitly modeling individual neural dynamics is a crucial first step in understanding the neural basis of cognitive behaviors. Elucidating the role of spontaneous movements in cognition will also be important for assessing and developing novel therapies for neurobehavioral disorders such as attention deficit hyperactivity disorder.

It has not been possible to fully understand large-scale neural and behavioral data during cognitive tasks because neural activity is strongly modulated by movements during the task, and the effect of spontaneous, uninstructed movements on learning and cognition is not well understood. A significant challenge in disentangling the neural dynamics related to movements from those related to cognitive tasks is the presence of subject-to-subject variability. Traditionally, the variability is resolved by focusing on the representations that are present across a large number of subjects. In contrast, we want to explicitly model spontaneous movements and subject-to-subject variability by decoupling it from the across-subject part of the task. For this, we plan to leverage across-subject similarity in neural activity in mice by learning subject-independent dynamical models, while separately quantifying subject-specific dynamics.

Furthermore, the next generation of neurostimulation algorithms should not require extensive training on each subject. For this goal, we will use a trained across-subject model as the initial model for new subjects, while refining it further with individual data. This transfer learning approach will lead to effective model-based control strategies to design closed-loop neurostimulation. In an integrative computational and experimental approach, these models will be used to investigate the contribution of high-dimensional cortical activity to spontaneous movements and cognitive tasks.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/latent.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/csvae.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/mice.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
