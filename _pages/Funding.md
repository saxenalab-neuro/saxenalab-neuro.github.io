---
layout: textlay
permalink: /fundings/
title: funding
description: Edit the `_data/repositories.yml` and change the `github_users` and `github_repos` lists to include your own GitHub profile and repositories.
nav: true
nav_order: 4
---


# BRAIN INITIATIVE R01: ELUCIDATING PRINCIPLES OF SENSORIMOTOR CONTROL USING DEEP LEARNING.
How do distributed neural circuits drive purposeful movements from the complex musculoskeletal system? This understanding and characterization will be critical towards the application of principled neurostimulation to specific brain regions to study the effect of neural circuit perturbations on behavior, and conversely towards predictions of the neural activity during perturbations in the behavior.

Breakneck advances in hardware and machine learning techniques have led to vast improvements in our ability to record and model large-scale multi-regional neural data. Our broad research goal is to advance the current state-of-the-art for modeling the neural control of movements by incorporating large-scale measurements and biological constraints into theoretical models of sensorimotor control.

To that end, we are developing biologically-inspired goal- and data- driven artificial intelligence methods to elucidate the neurodynamical basis of sensorimotor control. Using these tools, we hope to elucidate principles of sensorimotor control by incorporating recorded neural data in succinct and interpretable biologically-inspired models of the relationships between the measured biological data and the corresponding behavior.

This is a critical step towards (a) elucidating the computational role of neural activity from different brain regions in controlling complex behavior, (b) allowing us to further refine theoretical models of movement generation based on data, and (c) understanding where and how to stimulate the brain in order to efficiently apply neurostimulation for achieving desired behavior. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nih/arm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nih/sov.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nih/mk.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# NSF COLLABORATIVE GRANT: ROLE OF SPONTANEOUS MOVEMENTS DURING DECISION-MAKING.
Cognitive tasks such as decision-making are performed by different subjects in different ways. An important manifestation of this subject-to-subject variability is through spontaneous movements during task performance. For example, people may tap the floor or move their eyes while learning a cognitive task; similarly, mice display idiosyncratic whisker, facial, or other movements.

Since both spontaneous movements and cognitive tasks modulate cortical activity, modeling and interpreting neural activity during decision-making is a major challenge. Deciphering the function and quantifying the neural origin of spontaneous movements while explicitly modeling individual neural dynamics is a crucial first step in understanding the neural basis of cognitive behaviors. Elucidating the role of spontaneous movements in cognition will also be important for assessing and developing novel therapies for neurobehavioral disorders such as attention deficit hyperactivity disorder.

It has not been possible to fully understand large-scale neural and behavioral data during cognitive tasks because neural activity is strongly modulated by movements during the task, and the effect of spontaneous, uninstructed movements on learning and cognition is not well understood. A significant challenge in disentangling the neural dynamics related to movements from those related to cognitive tasks is the presence of subject-to-subject variability. Traditionally, the variability is resolved by focusing on the representations that are present across a large number of subjects. In contrast, we want to explicitly model spontaneous movements and subject-to-subject variability by decoupling it from the across-subject part of the task. For this, we plan to leverage across-subject similarity in neural activity in mice by learning subject-independent dynamical models, while separately quantifying subject-specific dynamics.

Furthermore, the next generation of neurostimulation algorithms should not require extensive training on each subject. For this goal, we will use a trained across-subject model as the initial model for new subjects, while refining it further with individual data. This transfer learning approach will lead to effective model-based control strategies to design closed-loop neurostimulation. In an integrative computational and experimental approach, these models will be used to investigate the contribution of high-dimensional cortical activity to spontaneous movements and cognitive tasks.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/mice.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/csvae.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/latent.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
